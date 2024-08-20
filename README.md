# Flutter GitHub Trend
Flutter GitHub Trend is a new Flutter project designed to showcase the latest trending repositories on GitHub.

Demo Video : 

## Features

- Trending Repositories
- Repository Details
- Filter by Stars
- Filter by Name

## Screenshot

<table>
  <tr>
     <td>Home</td>
     <td>Detail</td>
     <td>Search</td>
  </tr>
  <tr>
    <td><img src="arts/home.jpg" width=280 ></td>
    <td><img src="arts/detail.jpg" width=280 ></td>
    <td><img src="arts/search.jpg" width=280 ></td>
  </tr>
</table>

### How to Use the Repository

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```sh
     git clone https://github.com/rahdeva/flutter_github_trend
     ```
   - Navigate to the project directory:
     ```sh
     cd flutter_github_trend
     ```

2. **Ensure You Have the Latest IDE**
   - Make sure you're using the latest version of Android Studio or VSCode for the best development experience.

3. **Install FVM (Flutter Version Manager)**
   - FVM helps you manage Flutter SDK versions efficiently and avoids conflicts.
   - Install FVM by running the following command:
     ```sh
     dart pub global activate fvm
     ```
   - Once installed, use FVM to install the required Flutter version for this project:
     ```sh
     fvm install
     ```
   - Create an `.fvm` directory in your project to specify the Flutter version:
     ```sh
     fvm use <flutter-version>
     ```
   - Make sure to replace `<flutter-version>` with the required version specified in your project.

4. **Configure IDE to Use FVM**
   - For **VSCode**:
     - Install the **FVM** extension.
     - Open your project in VSCode.
     - Use the command palette (Ctrl+Shift+P) and select `FVM: Use` to set the Flutter SDK version for the project.

5. **Run the Project in Debug Mode**
   - After setting up FVM, run the project using the following command:
     ```sh
     fvm flutter run
     ```