# todo-app-flutter-rust
A simple ToDo app written in Flutter as frontend and Rust as backend.

## Setup Frontend
To start a new Flutter project in Visual Studio Code (VSCode), you can follow these steps:

1. **Install Flutter and Dart Extensions:** Make sure you have the Flutter and Dart extensions installed in VSCode. Open VSCode, go to the Extensions sidebar (or press `Ctrl+Shift+X`), and search for "Flutter" and "Dart" extensions. Install them if they're not already installed.

2. **Create a New Flutter Project:** Open VSCode and select a workspace or create a new one. Then, click on the Explorer sidebar icon (the one with the file icon) on the left side of the window.

3. **Open the Command Palette:** Open the Command Palette by going to the "View" menu and selecting "Command Palette" or by using the keyboard shortcut `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).

4. **Search for "Flutter: New Project" Command:** In the Command Palette, start typing "Flutter: New Project" and select it from the dropdown list as soon as it appears. Press Enter to confirm.

5. **Specify Project Location and Name:** Choose the location where you want to create your Flutter project. You can either select an existing folder or create a new one. Once you've selected the location, enter a name for your project and press Enter.

6. **Wait for Project Creation:** VSCode will create a new Flutter project based on the template. This process may take a few moments, as it sets up the project structure and downloads the necessary dependencies.

7. **Open the Project:** Once the project is created, VSCode will automatically open the project in a new window or a new instance of the editor.

Congratulations! You have successfully created a new Flutter project in VSCode. You can now explore the project structure, edit the code, and run the app using the available Flutter and Dart extensions in VSCode.

To run the Flutter app, you can open the integrated terminal in VSCode (`View` -> `Terminal`) and use the `flutter run` command to launch the app on an emulator or a physical device. Remember to have an emulator running or connect your device before running the app.

Now you're ready to start coding your Flutter project in VSCode!


## Setup Backend

To create a Rust binary program, you'll need to follow these steps:

1. Install Rust: Start by installing the Rust programming language on your system. You can download the Rust installation package from the official website: [https://www.rust-lang.org](https://www.rust-lang.org)

2. Set up your development environment: After installing Rust, open a terminal or command prompt and run the following command to ensure that Rust is properly installed:

```bash
$ rustc --version
```

If you see the version number, it means Rust is installed correctly.

3. Create a new Rust project: In your terminal, navigate to the directory where you want to create your Rust project. Run the following command to generate a new Rust project:

```bash
$ cargo new my_project_name
```

Replace `my_project_name` with the desired name for your project. This command will create a new directory with the project structure and necessary files.

4. Navigate to the project directory: Change to the project directory by running the following command:

```bash
$ cd my_project_name
```

Replace `my_project_name` with the actual name of your project.

5. Write your Rust code: Open your favorite text editor or integrated development environment (IDE) and edit the `src/main.rs` file. This is where you'll write your Rust code for the binary program.

6. Build the program: Once you've written your Rust code, go back to your terminal and run the following command to build your Rust binary:

```bash
$ cargo build --release
```

This command will compile your Rust code and create an optimized binary executable. The `--release` flag enables optimizations, resulting in a faster binary but with a slightly longer build time. If you omit `--release`, it will build a debug version instead.

7. Run the program: After the build completes successfully, you can run your Rust binary by executing the following command:

```bash
$ ./target/release/my_project_name
```

Replace `my_project_name` with the actual name of your project. If you built a debug version, replace `release` with `debug` in the command.

That's it! You've created a Rust binary program. You can iterate on your code, rebuild, and rerun the program as needed.


