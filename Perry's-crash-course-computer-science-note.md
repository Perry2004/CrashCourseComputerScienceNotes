## Early Computing
    1. Abacus - the earliest calculate instrument. 
		a. Add and subtract. 
		b. The development of the scape of the society. 
		c. 1, 10, 100, 100 .... 
		d. No need to remember add in the head. 
	2. Step Reckoner - German polymath Gottfried Leibniz in 1694. 
		a. Multiplication and division. 
		b. First machine can do all four operations. 
		c. Problems: 
			i. Take few days to get the result. 
			ii. Too expensive. 
	3. Pre-computed Tables 
		a. Look up the answer instead of using the step reckoner for a few days. 
	4. Difference Engine 
		a. Could approximate polynomials. 
		b. Ultimately abandoned. 
		c. One was constructed by historians in 1991, and it worked. 
	5. Analytical Engine - General Purpose Computer
		a. Ahead of its time.  
		b. Never fully constructed. 
	6. Ada Lovelace - English Mathematician, World's First Programmer. 
		a. Wrote hypothetical programs for the Analytical Engine. 
	7. Tabulating Machine (Electro-Mechanical) - Herman Hollerith. 
		a. Use punch card to represent data. 
		b. Helped the US Census. 
		c. Founded the Tabulating Machine Company, which later merged with other machine makers in 1924 to become the IBM. 

## Electronic Computing 
	1. Harvard Mark I - One of the largest electro-mechanical computers. 
		a. Be built to run simulations for the Manhattan Project. 
		b. Roughly 3000 relays. 
		c. Relays: electrically-controlled mechanical switches. 
		d. Problems 
			i. Slow switching speed. 
			ii. Wear and tear. 
	2. Thermionic Valve - developed by English physicist John Ambrose Fleming in 1904. 
		a. Houses two electrodes inside an airtight glass bulb. 
		b. One of the electrodes could be heated to emit electrons,  the other electrode could then attract these electrons. 
		c. Only positive charged will work. 
	3. Diode 
		a. Electronic components that permits the one-way flow of current. 
	4. Triode Vacuum Tubes - developed by American inventor Lee de Forest.  
		a. Add a third electrode that sits between the two electrodes of valve. 
		b. Positive charge: permit the flow of electrons. 
		c. Negative charge: prevent the flow of electrons. 
		d. No moving parts: faster. 
	5. Vacuum Tubes 
		a. No moving parts, faster than relays and can be used for longer times. 
		b. Marked the shift from electro-mechanical computing to electronic computing. 
	6. Colossus MK 1 - the first large-scale use of vacuum tubes for computing. 
		a. Was used to decrypt Nazi communications. 
		b. 1600 vacuum cubes. 
		c. The first programable electronic computer. 
			i. By plugging hundreds of wires into plugboards. 
	7. ENIACT - The Electronic Numerical Integrator and Calculator, completed in 1946.
		a. World's first truly general purpose, programmable, electronic computer. 
	8. Transistor - Invented by John Bardeen, Walter Brattain, and William Shockley in 1947, Bell Laboratory. 
		a. Semiconductor 
			i. Set between two electrodes. 
			ii. Sometimes can conduct electricity, sometimes resist it. 
		b. Gate electrode 
			i. Manipulate the conductivity of the semiconducting material by changing the electrical charge of the gate. 
		c. Faster, smaller (nowadays smaller than 50 nanometers), and more stable (solid state component). 
	9. IBM 608 - the first fully transistor-powered, commercially-available computer. 
	10. Silicon Valley - Santa Clara Valley, between San Francisco and San Jose, California, named by the most common material used to create semiconductors. 
	11. Shockley Semiconductor - employees later founded Fairchild Semiconductors - employees later founded Intel - the world's largest computer chip maker today. 

## Boolean Logic & Logic Gates 
	1. Binary 
		a. Use two states to represent information. 
		b. 1 / 0, true / false. 
	2. Boolean Algebra 
		a. Values of variables are true and false. 
		b. NOT 
			i. Negate a Boolean value.
		c. AND
			i. Two inputs, one output. 
			ii. If the both inputs are true, the output is true. 
		d. OR
			i. Two inputs, one output. 
			ii. Only one input has to be true for the output to be true. 
		e. Exclusive OR (XOR) 
			i. If both inputs are true, the XOR is false. 

## Representing Numbers and Letters 
	1. Use binary to represent number. 
		a. Add digits to the front. 
		b. Base-two notation. 
		c. 101
			i. 1 four
			ii. 0 two 
			iii. 1 one. 
	2. bit 
		a. One binary digit, 1 or 0. 
	3. Byte 
		a. 1 byte = 8 bits. 
		b. 1 kilobyte = 210 bytes. 
	4. Represent positive and negative numbers 
		a. Use the first bit for the sign. 
		b. Use the remaining 31 bits for the number itself. 
	5. Floating Point Numbers 
		a. IEEE 754 - 32-bit floating point number. 
			i. First bit for the sign of the number. 
			ii. Next 8 bits for the exponent. 
			iii. Remaining 23 bits for the significand. 
	6. Represent Text 
		a. ASCII - the American Standard Code for Information Interchange, invented in 1963. 
			i. 7 bit code, can store 128 different values. 
			ii. Allow different computers made by different companies to exchange data. 
			iii. Limitation only for English. 
				2) Too many characters in Asian languages. 
		b. Unicode - devised in 192. 
			i. 16 bits code, can store over a million values. 

## How Computer Calculate - the ALU 
	1. ALU - Arithmetic & Logic Unit 
		a. Intel 74181 - the most famous ALU. 
			i. The first complete ALU that fit entirely inside of a single chip. 
			ii. Can handle 4-bit inputs. 
			iii. About 70 logic gates. 
			iv. Couldn't multiply or divide. 
		b. An arithmetic Unit 
			i. Half adder
			ii. Full adder 
			iii. 8-bit ripple carry adder 
			iv. Overflow Occurs when the result of an addition is too large to be represented by the number of bits you are using. 
			v. Carry-Look-Ahead adder - faster in modern computers. 
			vi. Operations can be done by the ALU. ADD
				2) ADD with CARRY 
				3) SUBTRACT 
				4) SUBTRACT with BORROW 
				5) NEGATE 
				6) INCREMENT 
				7) DECREMENT 
				8) PASS THROUGH 
		c. The logic union 
			i. Perform logical operations, like AND, OR and NOT. 
			ii. Perform simple numerical tests. 
		d. Flags 
			i. 1-bit code. 
			ii. For particulate states and statuses. overflow 
				2) zero 
				3) negative 

## Registers and RAM 
	1. AND-OR latch 
		b. Gated latch 
	2. Register 
		a. A group of latches. 
		b. Can hold a single number. 
		c. The number of bits in a register is called its width. 
		d. 16 * 16 matrix for 62 bits. 
	3. Memory address 
		a. Multiplexer 
			i. To convert from an address into something that selects the right row or column. 
	5. Random Access Memory 
		a. Can access any memory location, at any time, and in a random order. 

## The Central Processing Union 
	1. Instruction Address Register 
		a. Stores the memory address of the current instruction. 
	2. the Instruction Register 
		a. Stores the current instruction.  
	3. CPU operation (control unit) 
		a. Phase 1 - Fetch Phase 
			i. Retrieve the first instruction. 
		b. Phase 2 - Decode Phase 
			i. Figure out what the instruction is. 
		c. Phase 3 - Execute Phase 
	4. Clock 
		a. Keep the CPU ticking along. 
		b. Trigger an electrical signal at a precise and regular interval. 
	5. Clock speed / Hertz
		a. The speed at which a CPU can carry out each step of the fetch-decode-execute cycle. 
	6. Intel 4004 - the first single-chip CPU, released in 1971. 
		a. 4-bit CPU. 
		b. 740 Kilohertz clock speed. 
		c. Few gigahertz clock speed for todays computer chips. 
	7. Overclocking 
		a. Modify the clock to speed up the tempo of the CPU. 
	8. Underclocking 
		a. Save power. 
	9. Dynamic frequency scaling 
		a. Processors can increase or decrease their clock speed based on demand. 
		
## Instructions & Programs 
	1. CPU is a piece of hardware which is controlled by easy-to-modify software. 
	2. Software gives hardware capabilities that they cannot do by itself. 
	3. Cannot use 4-bit code represent some value 
		a. variable length instructions 
			i. Make the value longer, but harder to read. 
	4. Intel 4004 
		a. 46 instructions. 
		b. 8-bit immediate values. 

## Advanced CPU Designs 
	1. Make processor faster 
		a. Improve the switching time of the transistors inside the chip. 
		b. Put a little piece of RAM right on the CPU -- called a cache. 
		c. Instruction pipelining. 
		d. Run several streams of instructions at once -- multi-core processor
		e. Use multiple independent CPU. 
	2. Bus 
		a. Wires than transmit data between CPU and RAM. 
	3. Cache 
		a.  a little piece of RAM on the CPU. 
		b. Usually KB or MB. 
		c. Cache hit
			i. Data requested in RAM is already stored in the cache. 
		d. Cache miss 
			i. Data requested in RAM is not already stored in the cache. 
		e. Can always be used to store some middle value. 
		f. Dirty bit 
			i. The place used to record the mismatch between cache and RAM. 
			ii. The dirty bit will be checked before sync. 
				1) If it's dirty, the old data is written back to RAM before loading in the new block. 
		g. Sync will happen when the cache is full but a new block of memory is being requested by the processor. 
	4. Instruction pipelining 
		a. Parallelize the operation. 
		b. Problems 
			i. Data dependencies. 
			ii. Conditional jump instructions. 
		c. Out-of-order execution 
			i. Processor dynamically reorder instructions with dependencies. 
		d. Speculative execution 
			i. When facing a JUMP instruction, advanced CPUs guess which way they are going to go, and start filling their pipeline with instructions based off that guess. 
		e. Superscalar  
			i. Processor that can execute more than one instruction per clock cycle. 
	5. Multi-core processor 
		a. Processors that have several independent processing units inside of a single CPU chip. 
		
		
## Early Programming 
	1. Programmable textile loom - developed by Joseph Marie Jacquard in 1801. 
		a. Use punch cards. 
		b. Cheap, reliable, fairly human-readable. 
	2. Plug boards 
		a. Control panels that were full of little sockets into which a programmer would plug cables. 
		b. By the 1920s, these boards were made swappable to make programming more comfortable. 
		c. ENIAC - the world's first general-purpose electronic computer, completed in 1946. 
			i. Use a ton of plug boards. 
			ii. Take up to few weeks to switch programs. 
	3. Stored-program computers 
		a. Store a entire program in the computer memory. 
		b. Can store not only programs, but also data. 
	4. Von Neumann Architecture 
		a. Unifying the program and data into a single shared memory. 
		b. A processing unit containing an ALU, data registers and instruction register and instruction address register. 
		c. A memory to store both data and instructions. 
	5. Punch cards 
		a. Write the contents of the card into the computer's memory. 
		b. Get data out of the computer. 
		c. Punched paper tape 
	6. Panel programming 
		a. Use huge panels full of switches and buttons. 
		b. Indicator lights can display the status of various functions and values in memory. 
		
## The First Programming Languages 
	1. Machine Code 
		a. Codes that can be read directly by the computer. 
		b. Pseudo-code 
			i. An informal, high-level description of a program. 
	2. Mnemonics - Slightly higher-level languages that were more human-readable than machine code in 1940s ~1050s. 
		a. Assembler 
			i. Reusable helper binary programs that read in text-based instructions and automatically assemble them into the corresponding binary instructions. 
			ii. Auto-linking JUMPs to labels. 
	3. Arithmetic Language Version 0 - A-0
		a. Use the first compiler built in 1952.
			i. A special program to transform "source" code written in a programming language into a low-level language. 
	4. Variables 
		a. Abstractions for needed memory locations. 
	5. FORTRAN - formula translation, released by IBM in 1957. 
		a. Twenty times shorter than assembly codes. 
		b. A small increase in computation time. 
	6. the Committee on Data Systems Languages 
		a. To guide the development of a common programming language that can run on every computers. 
		b. Common Business-Oriented Language - COBOL. 
			i. Write once, run anywhere. 
	7. Other languages 
		a. 1960s, ALGOL, LISP, BASIC. 
		b. 1970s, Pascal, C, Smalltalk. 
		c. 1980s, C++, Objective-C, Perl. 
		d. 1990s, Python, Ruby, Java. 
		e. 2000s, Swift, C#, Go. 

## Programming Basics - Statements and Functions 
	1. Statements 
		a. Syntax 
			i. The set of rules that govern the structure and composition of statements in a language. 
		b. Control Flow Statements 
			i. if statement - conditional statements. 
			ii. While statement - conditional loop. 
	2. Functions 
		a. Package part of  codes that can implement some functions. 
		b. Modularizing programs. 

## Intro to Algorism 
	1. Big O notation
		a. The relationship of input size to the number of steps the algorithm takes to run characterizes the complexity of the algorithm. 
		b. It gives an approximation of how fast, or slow, and algorithm is going to be. 
	2. Sorting Algorithm
		a. Selection sort O(n * n). 
		b.  Merge sort O(log n). 
	3. Graph Search
		a. Brute force approach - try every paths O(n !). 
		b. Dijkstra - conceived in 1956 O(n2).  
			i. A few years later, O(n log n + l). 

## Data Structure 
	1. Array 
		a. Index 
			i. Offset from the first address. 
	2. Strings 
		a. Array of characters. 
		b. A null value to stop. 
	3. Matrix (two dimensional array)
		a. Array of array. 
	4. Struct 
		a. Groups of variables that are bundled together. 
		b. Store several pieces of data at once. 
	5. Linked list 
		a. Structure that contains several nodes. 
		b. Each node point to the next node in the list. 
		c. Can be dynamically extended or shortened. 
	6. Queue 
		a. First-in First-out - FIFO. 
	7. Stacks 
		a. Last-in First-out - LIFO.  
		b. Push - in, pop - out. 
	8. Trees 
		a. Nodes with two pointers. 
		b. Root 
			i. The beginning of the tree. 
		c. Children node
			i. Nodes that hang from other nodes. 
		d. Parents node 
			i. Nodes above children. 
		e. Leaf nodes 
			i. Nodes that have no children nodes. 
		f. One-way pace. 
	9. Graph 
		a. Nodes that can point to anything. 
		
## Alan Turing 
	1. Alan Mathison Turing - born in London in 1912. 
	2. Decision problem 
		a. Is there an algorithm that takes, as input, a statement written in formal logic, and produces a "yes" or "no" answer that's always accurate? 
		b. Alonzo Church - American mathematician first presented a solution in 1935. 
			i. Lambda Calculus. 
				1) No such universal algorithm could exist. 
		c. Turing Machine 
			i. Mathematical model of computation. 
			ii. Paper tapes can store symbols. 
			iii. A read/write head - read or modify symbols. 
			iv. State variable. 
			v. Rules. 
	3. Turing complete 
		a. Computing system that is as powerful as Turing machine. 
		b. Modern computing systems are all Turing Complete. 
	4. Halting problem 
		a. Is there an algorithm that can determine, given a description of a Turing Machine and the input from its tape, whether the machine will run forever or halt? 
		b. Reasoning 
			i. H is a hypothetical Turing machine that will always outputs either Yes, it halts, or no, it doesn't. 
			ii. If there existed a program whose halting behavior was not decidable by H, it would mean the Halting Problem is unsolvable. 
			iii. B is a new machine will be opposite with the output of H. 
			iv. Ask H what B will do when asked to evaluate itself. 
			v. Therefore, the Halting Problem cannot be solved by Turing machine. 
			vi. The computer have limitation. No matter how much time or memory you have, there are some problems that cannot be solved ever. 
			vii. Church-Turing thesis. 
	5. Decrypt German communications - Enigma Machine. 
		a. Encryption 
			i. Each gears have 26 possible rotational positions. 
			ii. Billions of possible settings. 
		b. the Bombe 
		c. the Manchester Mark 1 - an early and influential stored-program computer. 
	6. Artificial intelligence
		a. A computer would deserve to be called intelligent if it could deceive a human into believing that it was human - Turing test. 
		b. A completely automated public Turing test to tell computers and humans apart - CAPTCHA. 
			i. Being used on the Internet to prevent automated systems from doing things like posing spam on websites. 

## Software Engineering 
	1. Object Oriented Programming
		a. Package functions into hierarchies, and pull related code together into "objects". 
		b. Objects can contain other objects, functions and variables. 
	2. Documentation 
		a. What each function in the code does. 
	3. Application programming interface - API. 
		a. Allows the right people access to the right functions and date. 
	4. Integrated Development Environments - IDE. 
	5. Source Control 
		a. Code repository - a centralized servers that store code for projects. 
		b. Rolled back - to an earlier, stable version. 
	6. Beta software
		a. A version of software that's mostly complete. 
		b. Not fully tested. 
	7. Alpha version 
		a. Software that are tested internally. 

## Integrated Circuits & Moore's Law 
	1. Integrated Circuits - ICs.  
		a. Germanium. 
		b. Silicon. 
	2. Printed circuit boards - PCB. 
		a. Have all the metal wires etched into the board and connect components together. 
	3. Photolithography 
		a. Use light to transfer complex patterns to a material. 
		b. Wafer
			i. A slice of silicon. 
	4. Moore's Law - released by Gordon Moore in 1965. 
		a. Approximately every two years, thanks to the advances in materials and manufacturing, you could fit TWICE the number of transistors into the same amount of space. 
	5. Intel - Integrated and Electronics - founded by Robert Noyce and Gordon Moore in 1968. .
	6. Very-large-scale integration - VLSI. 
		a. Automatically generate chip designs. 
	7. The end of Moore's law
		a. Due to the wavelengths of light used in photolithography, there are limits on how fine we can make features on a photomask. 
		b. Quantum tunneling. 
			i. The electrons may jump across the gap. 

## Operating System 
	1. Operating System - OS. 
		a. Just programs. 
		b. Have special privileges on the hardware. 
		c. Can run and manage other programs. 
		d. Batch processing. 
			i. Automatically run several programs one by one. 
		e. Intermediaries between software programs and hardware peripherals. 
			i. Provide a software abstraction through APIs - device drivers. 
		f. Multitasking 
		g. Atlas supervisor - finished in 1962. 
			i. Can run several programs at the same time on its single CPU. 
		h. Allocate each program its own block of memory. 
		i. Virtualize memory 
			i. Programs can assume their memory always starts at address 0. 
			ii. Dynamic memory allocation. 
			iii. Memory protection, get every program better isolated. 
		j. Several users 
			i. One terminal for one user. 
			ii. Time sharing. Each user can only use part of the resources. 
	2. Peripherals 
		a. All devices connected to a computer. 
	3. Unix 
		a. Separate the OS into two parts. '
			i. Core functionality - Kernel.
			ii. Useful tools.  

## Memory & Storage 
	1. Delay line memory 
		a. Can only read one bit at one time. 
		b. Sequential memory, cyclic-access memory. 
		c. Magnetostrictive delay lines 
			i. Use metal wire that could be twisted. 
	2. Magnetic core memory 
		a. Can access any bit at any times. 
	3. Magnetic tape 
		a. A long, thin and flexible strip of magnetic material, stored in reels. 
		b. Magnetic drum memory 
			i. A metal cylinder coated in a magnetic material for recording data. 
			ii. Thousands of revolutions per minutes. 
		c. Hard disc drive 
			i. Thin. Can be stacked. 
		d. Floppy disc 
	4. Compact Disc - CD 
		a. Have little physical divots in their surface that cause light to be reflected differently. 
	5. Solid state 
		a. Solid state drive - SSD. 
		b. No need to move, faster.

## File & File Systems 
	1. File format 
		a. Text format - txt. 
			i. ASCII in binary. 
		b. Wave - WAV 
			i. Audio. 
			ii. Amplitude. 
		c. Meta data 
			i. Data about data. 
			ii. Header of a file. 
		d. Bitmap - BMP. 
			i. Image. 
			ii. Image width. 
			iii. Image height. 
			iv. Number of image planes. 
			v. Color depth. 
			vi. RGB values. 
	2. Directory file 
		a. The file that records where other files are located. 
		b. Name + . + File extension. 
	3. File system 
		a. The part of an operating system that manages and keep track of stored files. 
		b. Flap file system 
			i. All the files are store in one level. 
		c. Hierarchical file system 
			i. Extra metadata -- directory. 
			ii. Just need to change the directory when moving. 

## Compression 
	1. Compression 
		a. Squeezes data into a smaller size. 
		b. Reduce repeated or redundant information. 
			i. Run-length encoding. 
			ii. Lossless compression. 
		c. Don't forget to be awesome - DFTBA. 
			i. A dictionary that stores the mapping from codes to data. 
			ii. Generate compact codes for blocks. 
				1) Huffman Tree 
					a) Layout all the possible blocks and their frequencies. 
					b) Select the two with the lowest frequencies at every round. 
					c) Combine them into a little tree, which have a combined frequency of 2. 
					d) Repeat. 
					e) Label each branch with a 0 or 1. 
					f) The tree is arranged by frequency. 
		d. Lossless compressed file formats 
			i. GIF, PNG, PDF, ZIP. 
		e. Lossy compression techniques 
			i. Perceptual coding 
				1) Discard or reduce precision in a manner that aligns with human perception. 
			ii. JPEG 
				1) Break images up into blocks of 8 * 8 pixels. 
			iii. Temporal redundancy 
				1) In a video, a lot of pixels between frames are going to be the same. 
			iv. MPEG-4
				1) 20 to 200 times smaller than the original file. 

## Keyboards & Command Line Interfaces 
	1. Keyboards 
		a. QWERT 
		b. Ten-finger, touch-typing. 
		c. Teletype machine. 
	2. Command line interface 
		a. Human type the commands, and return. 
		b. The computer type back. 
		c. The screens replaced teletype machines in 1970s. 
		d. Terminals 
			i. Virtual teletype or glass teletype machines. 

## Screen & 2D Graphics 
	1. Screens were first separated from the keyboard and were used to show some temporary values. 
	2. Cathode ray tubes - CRT 
		a. Shoot electrons out of an emitter at a phosphor-coated screen. 
		b. The paths can be manipulated with electromagnetic fields. 
		c. Vector scanning 
			i. Direct the electron beam to trace out shape. 
		d. Raster scanning 
			i. Repeatedly follow a fixed path, scanning line by line. 
	3. Liquid crystal displays - LCDs. 
		a. Render crisp dots onto the screen - pixels. 
		b. Use raster scanning to update RGB pixels. 
	4. Character generator - the first graphics cards. 
		a. Read-only memory - ROM stores graphics for each character - dot matrix pattern. 
		b. A memory place reserved for graphics - screen buffer. 
		c. Cannot draw other shape. 

## The Cold War and Consumerism 
	1. Use computer to navigate in the space - Apollo. 
		a. Integrated circuits. 
	2. Missals 
	3. Initially, the US semiconductor industry boomed, buoyed by high-profit government contracts. 
	4. In 1950s and 1960s, the Japanese semiconductor has dominated the market. 

## The Personal Computer Revolution 
	1. At the first 30 years, it was too expensive to have a personal computer. 
	2. Developments 
		a. Single-chip CPUs. 
		b. Integrated circuits. 
		c. Cheaper and reliable storage. 
		d. Low-cost display. 
	3. Microcomputer 
		a. Cheaper and smaller than normal computer. 
	4. Open architecture 
		a. Allow third parties to create new hardware and peripherals. 
	5. Only Apple kept significant market share without IBM compatibility. 
		a. Closed architecture. 
		b. Macintosh - using Graphic User Interface. 

## Graphical User Interface 
	1. Douglas Engelbart - the forefather of modern GUIs. 
		a. oN-Line System - NLS. 
		b. Create the first computer mouse. 
		c. Windows, icons, menus, and a pointer - WIMP interface. 
		d. A basic set of widgets. 
	2. Create a GUI program 
		a. Create a window. 
		b. A text box and a button. 
		c. Event-driven programming. 
			i. Code can fire at any time, and in different orders, in response to events. 
	3. Mac OS 
		a. Succeeded at the first period. 
	4. Windows 1.0 -- Windows 95. 
		a. Start menu, taskbar, windows explorer file manager. 

## 3D Graphics 
	1. 3D projection 
		a. Wireframe rendering 
		b. Mesh 
		c. Why most triangles? 
			i. Three points in a plane, there is only one answer. 
		d. Scanline Rendering 
			i. Translate a polygon to filled pixels. 
			ii. Read the three points that make up the polygon. 
			iii. Find the lowest and highest Y values. 
			iv. Calculate where a line running through the center of a row. 
			v. Fill in the pixels between the two intersections. 
		e. Antialiasing 
			i. Adjust the color based on how much the polygon cuts through each pixel. 
		f. Occlusion 
			i. Use a sort algorithm - painter's algorithm. 
			ii. Z-Buffering 
				1) Keep tract the distance of the screen to a polygon. 
		g. Back-face culling 
			i. Ignore the back face of polygons.  
		h. Shading 
			i. Some polygons are brighter, and some polygons are darker. 
			ii. Flat shading. 
				1) Noticeable, not smooth. 
		i. Textures 
			i. Texture mapping 
				1) Map the coordinates between polygon's and the texture's. 
	2. Make rendering faster 
		a. Special hardware. 
		b. Divide up a 3D scene into many smaller parts and run them in parallel. 
	3. Graphics processing unit - GPU. 
		a. Have ROM for graphics processing. 

## Computer Networks 
	2. Local area networks - LANs. 
		a. Small networks of close-by computers. 
		b. Ethernet - developed in the early 1970s at Xerox Parc. 
			i. A series of computers are connected to a single, common ethernet cable. 
			ii. Each computer have a Media Access Control Address - MAC address. 
			iii. Carrier Sense Multiple Access - CSMA. 
				1) The carrier is any shared transmission medium that carries data. 
			iv. When several computer wants to transport data at the same time, there will cause an collision. 
			v. Solutions 
				1) Stop the transmitting and wait for a random period and try again. 
				2) Wait longer is it faced collision again - Exponential bakeoff. 
			vi. Collision domain: the number of devices on a given shared carrier.  
				1) Solution 
					a) Separate the net to several collision domains, and add a switch. 
					b) The switch sits between two networks, and only passes data between them if necessary.
		c. Routing  
			i. Circuit switching. 
				1) Early telephone. Connect different wires manually. 
			ii. Message switching. 
				1) Like mail works. Send the message position by position. 
				2) Can use different routes, therefore more reliable and more fault-tolerant. 
				3) Disadvantages 
					a) Messages are sometimes big and may clog up the network. 
						i) The solution is to chop up big transmissions into many small pieces, called packets. 
			iii. Hop count: the numbers of hops a message takes along a route. 

## The Internet 
	1. Computer connects to the LAN of the router, then connects to a WAN of. a Internet Service Provider - ISP. 
	2. IP protocol 
		a. A standard that Internet packets have to conform. 
			i. Metadata that stored in front of the data payload. 
	3. User datagram protocol - UDP. 
		a. UD header sits inside the data payload. 
			i. Port number
				1) Every program wanting to access the internet will ask its host computer's Operating System to be given a unique port. 
				2) When the packet arrives, the Operating System will read the port number and give the packet to the right program. 
			ii. Checksum 
				1) Allow the data to be verified for correctness. 
					a) By checking the sum of the data. 
	4. Transmission control protocol - TCP 
		a. TCP header sits inside the data payload of IP packets - TCP/IP. 
			i. Port number. 
			ii. Checksum. 
				1) Once the computer has correctly received a packet, the data passes the checksum. 
				2) If the sender doesn't receive the checksum, it will send again later. 
			iii. Sequential numbers of packets. 
				1) Even the data comes in all scrambled, the TCP implementation in your computer's operating system can piece it all together correctly. 
			iv. Can send many packets. 
	5. When a computer want to connect to a website, it needs two things -- an IP address and a port. 
	6. Domain name system - DNS. 
		a. A service that maps domain names to addresses. 
		b. DNS is stored in a tree data structure. 
			i. Top level domains - TLD. 
				1) At the top. 
				2) .com, .gov, .net, .org, .edu, .uk ...
			ii. Second level domains 
				1) google.com, dftba.com ... 
			iii. Sub-domains 
				1) drive.google.com ...
	7. Physical layer. 
		a. Electric signals, radio signals...
	8. Data-linker layer. 
		a. MAC address... 
	9. Network layer. 
		a. The place all the switching and routing technologies operate. 
	10. Transport layer. 
		a. TCP, UDP ... 
	11. Session layer. 
		a. Open a connection, transmit messages, and shut the connection by using TCP and UDP and so on. 
	12. Presentation layer. 
	13. Application layer. 
	14. Five layers of the Open System Interconnection - OSI model. 

## The World Wide Web 
	1. The world wide web runs on top of the internet. 
	2. Can be accessed with a special program called a web browser. 
	3. The fundamental building block of the web is a single page. 
	4. Hypertext 
		a. Text containing h6yperlinks. 
		b. Each hypertext page needs a unique address. This is specified by a Uniform resource locator - URL. 
	5. Hypertext transfer protocol 
		a. Get. 
			i. Get the page of the giving address. 
		b. Status code 
			i. 400 - 499 are for client errors. 
		c. Using HTML to markup the webpage. 
	6. Web browsers 
		a. Mosaic 
			i. The first browser that can display both images and texts in one window. 
	7. Search engine
		a. JumpStation - the earliest web search engine that operated like the ones we use today. 
		b. A web crawler. 
			i. Software that followed all the links it could find on the web. 
		c. An ever enlarging index. 
			i. A search algorithm that consulted the index. 
	8. Net neutrality 
		a. Network neutrality is the principle that all packets on the internet should be treated equally. It doesn't matter if the packets are my email or you streaming this video, they should all chug along at the same speed and priority. 
		b. Throttled 
			i. Intentionally given less bandwidth and lower priority. 
			
## Cybersecurity 
	1. Secrecy - confidentiality means that only authorized people should be able to access or read specific computer systems and data. 
	2. Integrity means that only authorized people should have the ability to use or modify systems and data. 
	3. Availability means that authorized people should always have access to their systems and data. 
	4. Denial of Service Attack - DOS 
	5. Threat model 
		a. Security experts start a specification of who your "enemy" is, at an abstract level. 
	6. Two main security questions 
		a. Who are you? 
			i. Authentication 
				1) What you know? 
				2) What you have? 
				3) What you are? 
		b. What should you have access to? 
			i. Read 
			ii. Write 
			iii. Execute 
	7. Security kernel / trusted computing base. 
		a. A minimal set of operating system software that's close to provably secure. 
	8. Independent verification & validation 
		a. Works by having code audited by a crowd of security-minded developers. 
	9. We can use sandbox application to achieve isolation. 
 
## Hackers & Cyber Attack 
	1. Social engineering 
		a. A person is manipulated into divulging confidential information, or configuring a computer system so that it permits entry by attackers. 
	2. Fishing 
		a. A fake website that looks like the real official website. 
		b. Ask the user to enter the username and password. 
	3. Pretexting 
		a. Attackers call up a company and then confidently pretend to be from their IT department. 
		b. Often attackers will call a first number, and then ask to be transferred to a second, so that the phone number appears to be internal to the company.
	4. Trojan horses 
		a. Programs that masquerade as harmless attachments, but actually contain malicious software - malware. 
			i. Steal data. 
			ii. Ransomware. 
	5. Brute force 
		a. Try every possible passwords until get into the system. 
	6. NAND mirroring 
		a. If you have physical access to the computer, you can attach wires to the device's memory chip and make a perfect copy of its contents. 
		b. Try brute force until the system ask you to wait. 
		c. Reflash the memory with the original copy. 
		d. Try more passwords with no waiting. 
	7. Exploit 
		a. Find and take advantage of a bug in a system, and successfully utilizing a bug to gain capabilities or access. 
			i. Buffer overflow 
				1) Use the overflow value to overwrite some important value. 
				2) is_admin = true. 
	8. Code injection
		a. Use Structured query language - SQL. 
		b. Username = "whatever"; DROP TABLE users;"; 
			i. Delete the whole table. 
		c. No need to break into the system. 
		d. No need to know the username and password. 
	9. Worms 
		a. A program that jump from computer to computer automatically. 
		b. Botnet 
			i. Use other people's computer. 
			ii. Launch Distributed denial of service - DDoS attacks against servers. 
				1) All the computers in the botnet send a flood of dummy messages. 

## Cryptography 
	1. Cryptography - crypto and graphy. 
		a. Secret writing. 
		b. Cipher 
			i. An algorithm that converts plain text into ciphertext. 
	2. Substitution ciphers 
		a. Replace every letter in a message with something else according to a translation.
		b. Caesar cipher
			i. Shift the letters in a message forward by three places. 
		c. Drawback 
			i. Letter frequencies are preserved. 
	3. Permutation ciphers 
		a. Columnar transposition cipher 
			i. Fill the messages in a grid. 
			ii. Read characters in a different order. 
	4. Enigma 
		a. Rotors 
			i. One side have electrical contacts for all 26 letters. 
			ii. More than 3 rotors. 
			iii. Switch after enter a single letter. 
		b. Encrypting and decrypting have the same processes. 
		c. Drawback 
			i. It's impossible for a letter to be encrypted as itself. 
	5. Data encryption standard - developed by IBM and the NSA in 1977. 
		a. Originally used binary keys that were 56 bits long. 
			i. Unsafe after1990s. 
	6. Advanced encryption standard - AES. 
		a. Use bigger keys - 256bits in size. 
		b. AES chops data up into 16-byte blocks, and then applies a series of substitutions and permutations, based on the key value, plus some other operations to obscure the message, and this process is repeated ten or more times for each block. 
	7. Key exchange 
		a. An algorithm that lets two computers agree on a key without ever sending one. 
		b. Use one-way function. 
			i. Diffie-Hellman key exchange 
				1) The one-way function is modular exponentiation. 

## Machine Learning & Artificial Intelligence 
	1. Classifier 
		a. Features 
			i. Values that usefully characterize the things we wish to classify. 
		b. Labeled data. 
		c. Decision boundary. 
		d. Confusion matrix 
			i. A table that shows where a classifier gets things right and wrong. 
		e. Decision 
			i. 
	2. Artificial neural networks 
		a.  Neural are cells that transmit and process messages using chemical and electrical signals.
		b. Each takes a series of inputs, combines them, and emits a signal. 
		c. Input layers. 
		d. Hidden layer. 
		e. Output layer. 
	3. Weak or narrow AI 
		a. Can only focus on one field. 
	4. Strong AI 
		a. AI that are similar to human.  

## Computer Vision 
	1. Color tracking algorithm. 
	2. Vertically color change. 
	3. Convolution 
		a. Operation of applying a kernel to a patch of pixels. 
		b. Get color differences. 
		c. Prewitt operators 
			i. Edge enhancing kernels. 
		d. Convolutional neural network. 
			i. Usually have many layers. 

## Natural Language Processing 
	1. Phrase structure rules 
		a. Encapsulate the gramma of language. 
	2. Speech recognition.
	3. Fast Fourier Transform 
		a. Converse wave form to frequencies.  
 
## Robots 
	1. Robots 
		a. Machines capable of carrying out a series of actions automatically. 
		b. The word was first used in a 1920 Czech play  to denote artificial, humanoid characters. 
	2. Automaton 
		a. Robots with no electricity. 
	3. Computer numerical control - CNC. 
		a. Could run programs that instructed a machine to perform a series of operations. 
	4. Unimate - the first commercial industrial robot, sold to General Motors in 1960. 
		a. Lift hot pieces of metal and stacked them. 
		b. Have systematic tasks stored in a drum memory. 
		c. Invented by George Devol. 
	5. Negative feedback control loop 
	6. Proportional-integral-derivative controller - PID controllers.
		a. Get the actual speed. 
		b. Compute the proportion value - the difference between the desire value and the actual value. 
		c. Compute the integral value - the sum of a error over a window of time. 
		d. Compute the derivative value - the rate of change between the desired and actual values. 
	7. Androids 
		a. Robots that look and act like humans. 
	8. Three laws of robotics - written by science fiction writer Isaac Asimov in 1942 in his short story "Runaround". 
		0. A robot may not harm humanity, or, by inaction, allow humanity to come to harm. 
		1. A robot may not injure a human being or, through inaction, allow a human being to come to harm. 
		2. A robot must obey the orders given it by human beings except where such orders would conflict with the First Law. 
		3. A robot must protect its own existence as long as much protection does not conflict with the First or Second Laws. 

## Psychology of Computing 
	1. Usability 
		a. The degree to which a human-made artifact can be used to achieve an objective effectively and efficiently. 
		b. Visual perception 
			i. People are good at ordering intensities of colors. 
			ii. Humans are terrible at ordering colors. 
		c. Humans can read, remember and process information more effectively when it's chunked. 
	2. Affordances 
		a. Affordances provide strong clues to the operations of things. 
			i. Plates are for pushing. 
			ii. Knobs are for turning. 
			iii. Slots are for inserting things into. 
	3. Affect - articulated by Rosalind Picard in her 1995 paper on Affective Computing. 
		a. Adapt computers behavior to respond appropriately to their users' emotional state. 
	4. Computer-mediated communication - CMC 
		a. Synchronous communication - Facebook. 
		b. Asynchronous communication - Email. 
	5. Human-robot interaction - HRI. 
		a. How people perceive different robots behaviors and forms. 
		b. How robots can interpret human social cues to blend in and not be awkward. 
	6. Uncanny valley 
		a. The drip in realism between almost-human and actually-human. 

## Educational Technology 
	1. Massive open online courses - MOOC. 
		a. Videos of lectures from famous professors. 
	2. Domain model 
		a. A formal representation of a knowledge, procedures and skills of a particular discipline. 
	3. Student model 
		a. A model that tracks, among other things, what part of knowledge a student has mastered and where they still need practice. 
		b. Bayesian knowledge tracing 
			i. The algorithm treats student knowledge as a set of latent variables, which are variables whose true value is hidden from an outside observer, like the software. 
			ii.  Will update its estimate of the students' knowledge based on the correctness of each interaction using that skill. 
			iii. Four probabilities that will be recorded.
				1) Probability that a student has learned. 
				2) Probability of guess. 
				3) Probability of slip. 
				4) Probability of transit. 
			
## The Singularity, Skynet, and the Future of Computing 
	1. Ubiquitous computing - articulated by Mark Weiser in the 1990s. 
		a. Compute in everything imaginable. 
		b. Make computing indistinguishable. 
	2. Not everything in the future need AI. 
	3. What is Intelligence? 
		a. Processing power. 
		b. Singularity - first used by John Von Neumann. 
			i. A runaway technological growth, especially with respect to a intelligence explosion. 
	4. Cyborgs 
		a. Humans and technology merge to enhance their intellect and physiology. 
	5. Digital ascension 
		a. Would involve people dying in the flesh and being uploaded into a computer and remaining conscious. 
	6. We're in a golden age of computing. 
