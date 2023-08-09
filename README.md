# MOLECULAR DYNAMICS SIMULATION

## Setup Instructions for Windows

To run the MOLECULAR DYNAMICS SIMULATION on a Windows system, you need to set up the following prerequisites:


1. **C Compiler**: You need a C compiler to build and execute the simulation. Cygwin provides the GCC compiler. Once you have installed Cygwin, the C compiler should be available automatically.
 **Environment Variables**: 
      ```
      C:\cygwin64\bin\
      ```
      Add to Environment Variables.

2. **PovRay**: PovRay is a ray-tracing software that may be required for rendering visualizations in the MOLECULAR DYNAMICS SIMULATION. Add to path after installation
```
'C:\Program Files\POV-Ray\v3.7\bin'
```
## Running the Simulation

Once you have completed the setup process, you are ready to run the MOLECULAR DYNAMICS SIMULATION on your Windows system. Make sure to open the Windows shell environment (e.g., Command Prompt, PowerShell) and navigate to the appropriate directory where the simulation code is located.
Run the Cygwin64 Terminal from the windows shell with the command
```
C:\cygwin64\bin\bash.exe
```
To compile and execute the simulation, use the following commands:
```
./build.sh

```