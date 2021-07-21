# My Book Suggestions
**My Book Suggestions** is a Windows Desktop Application that provides book suggestions to the client using an effective algorithm that outputs books based on user preferences.

## Download & Run the program (only Windows x64)
[Download MyBookSuggestions](https://github.com/RoyceAroc/MyBookSuggestions/blob/main/download.exe)

## Test and Setup Project Locally (for both Windows and macOS)
1. Clone this repository and `cd` into it:
    ```bash
    $ git clone https://github.com/RoyceAroc/MyBookSuggestions
    $ cd MyBookSuggestions
    ```
2. Install dependencies by the running the following node command
    ```bash
    $ npm install --save-dev electron
    ```
3. Run the program
    ```bash
    $ npm run start
    ```

## Additional steps to distribute the app on Windows and macOS

1. Run the following commands in the project folder
    ```bash
    $ npm install --save-dev @electron-forge/cli
    $ npx electron-forge import
    ```
2. Create the distributable by the running the following command
    ```bash
    $ npm run make
    ```
