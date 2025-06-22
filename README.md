# MVS 3.8 Mainframe Mojo Channel Project

A personal collection of JCL jobs, COBOL programs, and a custom COBOL compiler setup designed to run on IBM's MVS 3.8 environment. This repository serves both as an archive and a reference hub for enthusiasts of classic mainframe systems.

## What's Inside

- **JCL/** — Sample Job Control Language scripts for batch job automation, dataset manipulation, and system setup.
- **COBOL/** — A library of COBOL programs written and tested under MVS 3.8, covering data processing, string handling, and I/O routines.
- **COMPILER/** — A fixed version of the compiler to allow the BCOB programs to be loaded in a load dataset. 

## Getting Started

To run these jobs and programs, you'll need:
- A working MVS 3.8 system or emulator (e.g., Hercules)
- TSO access or an equivalent batch environment
- Familiarity with submitting jobs via SDSF or JES2 queue

## Usage

Browse to the desired directory, review the code, and submit jobs through your emulator's preferred method. Some JCL files require editing parameters like `JOBNAME` or `DSN` before execution.

## Notes

This repository is a work-in-progress and part of a personal learning journey. Feedback and suggestions are welcome!

## License

MIT License — use freely, learn plenty.

## Author

Mainframe Mojo — feel free to reach out via GitHub or open an Issue for questions or suggestions.

