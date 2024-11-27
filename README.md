In this project, I developed a 2D interactive game on an STM32F031x6 microcontroller, showcasing my proficiency in embedded systems, real-time processing, and low-level hardware interfacing.

Key Technical Features: 
Display & Graphics Handling: Utilized custom graphics arrays to render images on a small 16x16 pixel display. The game involves pixel-based graphics that are displayed in frames, with each sprite being represented as a 2D array. The putImage() function handles rendering images on specific coordinates, and I implemented sprite flipping to enable movement animation.

GPIO & Input Handling: The game uses GPIO pins to handle user inputs (up, down, left, right). Each input is debounced using software, with pull-up resistors enabled on the buttons. The pinMode() function configures input pins, and I used efficient polling to capture button presses in real-time, ensuring a responsive gameplay experience.

Real-Time Processing: The game runs in a loop that processes user input, moves the character, and redraws the display accordingly. I implemented a SysTick interrupt with a 1 ms timer resolution to manage time-sensitive tasks like delay and animation. The game state is updated at a fixed rate to ensure smooth gameplay.

Collision Detection & Interaction: Implemented a collision detection algorithm using geometric checks to determine if any part of the moving character overlaps with predefined target areas (e.g., if a sprite is inside a designated rectangle). This is crucial for detecting interactions like hitting obstacles or completing in-game tasks.

Optimized Performance: Focused on achieving the best performance by optimizing code for speed and memory usage. The game logic, such as input polling and graphics rendering, is streamlined to minimize processing overhead. I utilized efficient delay functions that rely on the SysTick timer to maintain timing accuracy without blocking the processor.

Low-Level System Configuration: Implemented low-level hardware interfacing by directly manipulating microcontroller registers, including configuring the GPIO pins, enabling interrupts, and managing the system clock. This provided a hands-on experience with the underlying hardware architecture.
