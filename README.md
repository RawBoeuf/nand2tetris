# Terry's nand2tetris Repository
![Nand2Tetris](https://img.shields.io/badge/Nand2Tetris-Computer%20From%20Scratch-blue?style=for-the-badge&logo=hackaday)![From-NAND-to-Computer](https://img.shields.io/badge/From%20NAND%20Gates%20to%20Computer-green?style=for-the-badge)

## Part 1: Build a Modern Computer from First Principles: From Nand to Tetris
![Logic Gates](https://img.shields.io/badge/Logic%20Gates-Boolean%20Algebra-orange?style=flat-square)

This part focuses on the Hardware design part of their building a Computer from scratch, using their Hardware Simulator.
## To Do List:
- [x] **Module 1: Boolean Functions and Gate Logic** - Solutions: [Project Files](/projects/01/)

**Brief Summary:**

After introducing us to the basics of boolean algebra and truth tables in the introduction. Noam Nisan and Shimon Shocken move on to building elementary logic gates such as Not, And, Or, etc. from the humble universal logic gate "Nand". Since any expression where two truth tables are equivalent means the gates are logically equivalent, we can derive these gates from a single universal logic gate. For solutions see [Project Files](/projects/01/), but I ***HEAVILY*** recommend you try to explore truth table equivalencies before looking at my solutions.

- [x] **Module 2: Boolean Arithmetic and the ALU** - Solutions: [Project Files](/projects/02/)

**Brief Summary:**

Now that we've implemented the numerous elementary logic gates from Project 1, we will move on to designing the core logic unit of the CPU in modern computing architecture: the Arithmetic Logic Unit. First, we implement the HalfAdder chip which takes in two inputs: **'a'** and **'b'** and dispenses to outputs: **sum** and **carry**. FullAdder takes in three inputs instead of two. Add16 takes two 16 bit inputs. Inc16 wants you to increment the input by 1. For solutions see: [Project Files](/projects/02/), once again I ***HEAVILY*** recommend you try to explore truth table equivalencies before looking at my solutions and at the very least look at the logical diagrams and explanations that Noam and Shimon provide.

- [x] **Module 3: Memory** - Solutions: [Project Files](/projects/03/)

**Brief Summary:**

The arithmetic logic unit (ALU) is now implemented so we can start moving onto other parts of the computer like the registers and RAM. I didn't watch all the videos before attempting this, so I ended up taking a lot more time than I should have. If you don't want to go through the head slamming insanity that I went through to figure out the logic behind these chips on a fundamental level before translating it into actual HDL, I'd highly recommend you actually watch the videos. Shimon's explanation of the logic was very eye-opening as I realized in hind-sight I could've figured this out much quicker if I had this explained to me in such an easy way. If you're still in need of help after watching the videos, see these files for reference: [Project Files](/projects/03/)

- [ ] **Module 4: Machine Language**

**Brief Summary:**

- [ ] **Module 5: Computer Architecture**

**Brief Summary:**

- [ ] **Module 6: Assembler Roadmap**

**Brief Summary:**

## Useful Links:
1. nand2tetris Home Page - [nand2tetris.org](https://www.nand2tetris.org/)
2. nand2tetris IDE [nand2tetris.github.io/web-ide/chip/](https://nand2tetris.github.io/web-ide/chip/)
3. nand2tetris Coursera Page - [coursera.org/learn/build-a-computer/](https://www.coursera.org/learn/build-a-computer/)