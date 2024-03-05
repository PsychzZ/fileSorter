# File Sorter

The File Sorter is a Python program that helps you organize and sort your files based on their file extensions.

## Features

- Sorts files in a specified directory based on their file extensions.
- Creates separate folders for each file extension and moves the corresponding files into their respective folders.
- Supports customizable file extensions and folder names.

## Usage

1. Clone the repository or download the fileSorter.py script.
2. Open a terminal and navigate to the directory where the fileSorter.py script is located.
3. Run the following command to execute the program:

   ```shell
   python fileSorter.py
   ```

# File Sorter

This is a Python program that automatically sorts files into different directories based on their file extensions.

## Prerequisites

- Python 3.x
- `watchdog` library (install using `pip install watchdog`)

## Usage

1. Open the `fileSorter.py` file in a text editor.
2. Fill in the paths for the source directory and destination directories according to your needs.
3. Run the program using the command `python fileSorter.py`.
4. The program will continuously monitor the source directory for any file changes.
5. When a new file is added or an existing file is modified, the program will move the file to the appropriate destination directory based on its file extension.
6. The program logs the file movements in the console.

## Configuration

You can configure the destination directories for different file types by modifying the following variables in the `fileSorter.py` file:

- `dest_dir_sfx`: Destination directory for small audio files or sound effects.
- `dest_dir_music`: Destination directory for music files.
- `dest_dir_video`: Destination directory for video files.
- `dest_dir_image`: Destination directory for image files.
- `dest_dir_documents`: Destination directory for document files.
- `dest_dir_presentation`: Destination directory for presentation files.
- `dest_dir_tables`: Destination directory for table files.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
