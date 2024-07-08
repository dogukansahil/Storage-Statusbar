# Storage Statusbar

Storage Statusbar is a small application that displays the disk space status in the menu bar. It is written in Python and uses the rumps library.

## Installation

### Requirements

- Python 3.x
- `psutil` and `rumps` libraries

### Step-by-Step Installation

1. Download and install Python: [Download Python](https://www.python.org/downloads/)

2. Install the required Python libraries:
    ```sh
    pip install psutil rumps
    ```

3. Download or clone the `ssb.py` file:
    ```sh
    git clone https://github.com/dogukansahil/Storage-Statusbar.git
    cd Storage-Statusbar
    ```

4. Run the application:
    ```sh
    python ssb.py
    ```

## Usage

When the application is running, the disk space information will be displayed in the menu bar. By default, it shows the free space in GB.

### Changing the Language

Click on the "Language" option in the menu to select a different language.

### Changing the Display Mode

Click on the "Change Display Mode" option in the menu to switch between displaying the disk space as a percentage or in GB.

### Supported Languages

- English (en)
- Simplified Chinese (zh-Hans)
- Spanish (es)
- Arabic (ar)
- Hindi (hi)
- French (fr)
- Russian (ru)
- Bengali (bn)
- Portuguese (pt)
- Japanese (ja)
- Turkish (tr)
- Traditional Chinese (zh-Hant)
- Italian (it)

## Uninstallation

1. Stop the application.
2. Delete the `Storage-Statusbar` directory:
    ```sh
    rm -rf Storage-Statusbar
    ```
3. Optionally, you can uninstall the installed Python libraries:
    ```sh
    pip uninstall psutil rumps
    ```

## License

This project is licensed under the MIT License. For more information, see the `LICENSE` file.
