# Fixing broken Repository
IITB Racing Team Trainee Assignment 1 for software module, focusing on learning git and building good git practices.
## Introduction
A program that generates random sensor data, and creates a log and a tmp file, along with a fake executable and cache file in a cache folder.

## Compile
Below are commands to compile `src/program.cpp` on common platforms.

**Windows (MSVC, in "Developer Command Prompt for VS"):**

	cl /EHsc src\program.cpp /Fe:sensor.exe

**Windows (MinGW / g++):**

	g++ -std=c++17 src\program.cpp -o sensor.exe

**macOS (clang++):**

	clang++ -std=c++17 src/program.cpp -o sensor

**Linux (g++):**

	g++ -std=c++17 src/program.cpp -o sensor

## Outputs
### **Sensor readings**
Generated in `output/sensor_data.txt`. Contain 5 Readings which are randomly generated.
### **Log file**
`run.log` is created which contains the time the program is executed at.
### **tmp file**
`temp.tmp` is created which contains a random value.
### **Fake Executable**
`program.exe` is created which contains the text `Fake executable artifact` and nothing else.
### **Cache file**
`cache/cache.data` is created containing random value.
### **Terminal output**
Success message is shown in terminal

## Contributors
[Sailesh Kumar Sahoo](https://github.com/sa1Lx) <br>
[Raghav Aggarwal](https://github.com/raghavaggarwal2k7)

## License
Licensed under [MIT](https://opensource.org/licenses/MIT).