# Frankenstein

This is a prototype for trying to intercept signals over Metropoloitan Networks and turn them into readable source.
This also hopefully once fully developed will be able to run and just continuously scan, intercept and finger crosed inject TV signal.

User guide:
step-by-step guide

1. **Install Rust:**
   If you haven't already installed Rust, you can do so by following the instructions on the official Rust website: [Install Rust](https://www.rust-lang.org/tools/install).

2. **Add Dependencies:**
   Make sure to add the necessary dependencies to your `Cargo.toml` file. In this case, you need to add the `gtk` crate. Open your `Cargo.toml` file and add the following lines:

   ```toml
   [dependencies]
   gtk = "0.9.2"
   ```

3. **Copy the Code:**
   Copy the provided Rust code into a new Rust file, let's name it `main.rs`.

4. **Paste the Code:**
   Paste the copied code into your `main.rs` file.

5. **Run the Code:**
   Open a terminal or command prompt, navigate to the directory where your `main.rs` file is located, and run the following command:

   ```
   cargo run
   ```

6. **Test the GUI:**
   After compiling, the GUI window should appear with a dropdown menu containing three options: "Linux Observation Task," "Network Traffic," "Windows Observation Task," and "MP4 Analysis Task." Select one of the options from the dropdown menu and click the "Execute Task" button. You should see the output printed in the terminal/console.
