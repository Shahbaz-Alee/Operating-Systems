# Operating System Simulator

This is an Operating System Simulator project developed as a final term project for the Operating Systems Lab course. The simulator is designed to mimic the functionality of an operating system, incorporating various features and concepts studied during the course.

## Features

- **Boot Message**: The operating system displays a custom boot message upon startup.
- **Multitasking**: The OS supports multitasking, allowing multiple processes to run concurrently.
- **Process Management**: Processes are managed efficiently, with each process having its own terminal to prevent output interference.
- **Task Management**: The OS supports various tasks, including Notepad, Calculator, Clock, File Management (Create, Copy, Move, Delete), Print File, and Minigames (Minesweeper, etc.).
- **Interrupts and Interrupt Handling**: Users can manually interrupt tasks to stop or minimize them, simulating real-world interruptions.
- **Resource Allocation**: Resources such as RAM, hard drive space, and CPU cores are managed effectively to optimize system performance.

## Getting Started

### Prerequisites

- C compiler (GCC recommended)
- CUPS (Common Unix Printing System) library for print functionality (optional)

### Compilation

1. Clone the repository to your local machine:

```
git clone https://github.com/ShahbazGhafil/Operating-Systems.git
```

2. Navigate to the project directory:

```
cd operating-system-simulator
```

### Running the Simulator

1. Run the compiled executable:

```
./main
```

## External Libraries

```
sudo apt-get install libsdl2-dev
```
```
sudo apt-get install libcups2-dev
```
## Instructor
- Dr. Numan Shafi

## Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
