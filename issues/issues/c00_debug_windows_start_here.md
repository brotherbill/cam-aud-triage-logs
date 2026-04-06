# D on Windows – Start Here

## 1. Goal
- Press F5 in VS Code on Windows and:
  - Build a D program
  - Run it in the integrated terminal
  - Hit breakpoints reliably

## 2. Tools Required
- DMD
- VS Code
- Code-D extension
- Microsoft C++ Build Tools (if needed)
- Terminal configuration

## 3. Installation Steps
1. Install D compiler
2. Install VS Code
3. Install extensions
4. Configure tasks.json
5. Configure launch.json

## 4. Verification Program
```d
import std.stdio;

void main() {
    writeln("D on Windows is working.");
}