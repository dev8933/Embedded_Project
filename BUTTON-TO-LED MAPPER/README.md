BUTTON-TO-LED MAPPER
Most beginner firmware handles inputs with nested if/else
statements. This project takes a smarter approach, using a mapping table to link button presses to specific actions
like toggling or blinking LEDs.
It teaches you modular thinking, function pointers, andhow to separate logic from behavior, a foundational pattern in embedded systems.
🎯 Requirements
1. At least 2–3 buttons and LEDs connected to GPIO
pins
Define a struct with button pin and its associated action (this will be the function pointer)
Create an array of these mappings (like a software interrupt table)
Use a loop or interrupt to detect button presses and call the mapped function
In real-world products like microwaves every button is mapped to a function behind the scenes, not hardcoded.
This project builds that thinking muscle, teaching you how to build scalable, maintainable, and clean firmware, even for the smallest of tasks.
