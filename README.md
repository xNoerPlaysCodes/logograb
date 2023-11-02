# logograb
Grab a logo, quick.
<br>

# Installation Instructions
## Direct Binary Download
### Windows
Step 1. Download `logograb-windows-x64.exe` from Releases tab.<br>
Step 2. Run the `.exe` file.<br>
Step 3. Enjoy!<br>

### Linux
// Make sure you have `libsfml` downloaded.
Step 1. Download `logograb-linux-x64` from Releases tab.<br>
Step 2. Run the binary.<br>
Step 3. Enjoy!<br>

### macOS
**Not Supported as of Now...**
<br>

## Compiling From Source
### Linux (g++)
Step 1. Download source files.<br>
Step 2. Run the `g++ -o main main.cpp -lsfml-graphics -lsfml-window -lsfml-system` command to compile the main.cpp file with lib sfml graphics, lib sfml window, and lib sfml system.<br>
Step 3. Run `./main`<br>
Step 4. Enjoy!<br>

### macOS (clang++)
Step 1. Download source files.<br>
Step 2. Run the `clang++ -o main main.cpp -I /path/to/SFML/include -L /path/to/SFML/lib -framework sfml-graphics -framework sfml-window -framework sfml-system` command to compile main.cpp file with lib sfml graphics, lib sfml window, and lib sfml system. (Replace /path/to/* with the paths)<br>
Step 3. Run `./main`<br>
Step 4. Enjoy!<br>

### Windows (WSL)
Follow Linux Instructions<br>

### Windows (g++)
Step 1. Download source files.<br>
Step 2. Run the `g++ -o main.exe main.cpp -I/path/to/SFML/include -L/path/to/SFML/lib -lsfml-graphics -lsfml-window -lsfml-system` command and replace `/path/to/*` with the correct paths.<br>
Step 3. Run `.\main`<br>
Step 4. Enjoy!
