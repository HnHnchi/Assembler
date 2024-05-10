Assembler

Assembler is a Python class designed to assemble assembly code into binary representations. It implements a two-pass assembly process, where it first scans the code for labels and then translates instructions into their binary representations.

Features:

- Two-pass assembly process.
- Supports memory-reference instructions (MRI), register-reference instructions (RRI), and input-output instructions (IOI).
- Handles labels and translates instructions into binary representations.

Getting Started:

To use the Assembler class, simply import it into your Python script or environment. You can initialize an instance of the class with optional paths to text files containing the binary representations of MRI, RRI, and IOI instructions. Then, you can use the `assemble()` method to assemble assembly code into binary representations.

Example Usage:

Consider the following example assembly code (`example.asm`):

