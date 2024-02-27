# Copy-Clipboard
Copy-Clipboard is a simple practice project aimed at providing a command-line interface for managing clipboard data using a JSON file as storage.

## Features
- Save Data: Save data from the clipboard with a specified key into a JSON file.
- Load Data: Load previously saved data from the JSON file back into the clipboard using a specified key.
- List Data: Display all the data currently stored in the JSON file.
- Command-Line Interface: Execute different actions (save, load, list) via command-line arguments.
- JSON File Management: Utilize a JSON file (clipboard.json by default) to store clipboard data persistently.

## Usage
Saving Data:

```
python copy_clipboard.py save
```

## Loading Data:

```
python copy_clipboard.py load
```


Listing Data:
```
python copy_clipboard.py list
```

## Requirements:
Python 3.9
clipboard module (install via pip install clipboard)

## Installation
Clone the repository:

```
git clone https://github.com/your_username/copy-clipboard.git
```

## Install required dependencies:

```
pip install clipboard
```

## Run the script:

```
python copy_clipboard.py [command]
```
