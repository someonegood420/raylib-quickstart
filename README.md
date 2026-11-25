# Raylib Quickstart

Get your project up and running in 3 simple steps:

1. **Get and Rename the Repository**

   Clone or download this repository, then rename the root folder to your desired project name (*do not name it `raylib`*).

   ```bash
   git clone https://github.com/raylib-extras/raylib-quickstart.git <your-project-name>
   ```

2. **Generate Solution Files**

   Run the build script to generate your Visual Studio solution:

   ```cmd
   build-VisualStudio2026.bat
   ```

3. **Build the Project**

   Compile your project using `msbuild` with the target solution file:

   ```cmd
   msbuild .\<your-project-name>.slnx /p:Configuration=Release /p:Platform=x64
   ```

---

> **Note:** Your source code files are located in the `src/` directory (e.g., `src/main.c` or `src/main.cpp`). Add or edit your code there before building. Refer to https://www.raylib.com/cheatsheet/cheatsheet.html to learn about raylib
