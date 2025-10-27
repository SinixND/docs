# Basic
`(Statements <) Functions & Data < Modules < Layers < Architecture`

# Spliting / Separation / Grouping
- Split by dependencies (OS, libraries, hardware, ...)
- Split by layer (app, render, logic, audio, network, ...)- Split if used somewhere else?

# Module
Consists of:
- classes/    // Classes with private members and methods; one-ofs
- components/ // Plain old data (POD); defines application state; Usually used multiple times, managed by ECS?
- configs/    // changeable data (eg. window dimensions)
- data/       // persistent data (eg. constants or enums)
- entities/   // Organizes components (either POD/struct or Id);
- systems/    // Functions modifying components or entities
- utils/      // Functions used accross the application

# Questions
- Split what? Modules? Layers? 
- When split in new category? 2+ rule?
- Directory structure similar or different? Sort by architecture or type (like all classes, data, configs etc.
- Bottom-up or Top-down design? Both? Shift later from BU (beginning) to TD (later, once architecture becomes clear?

