Nexus AI Voice Assistant

Project Description

Nexus is an AI-based voice assistant that helps you manage files and folders, open applications, and browse websites through voice commands. It utilizes speech recognition and text-to-speech technologies to interact with the user.

Table of Contents

1. Introduction
2. Technologies Used
3. Requirements
4. Installation Instructions
5. Usage Instructions
6. Features
7. Documentation
8. Visuals
9. Conclusion

Introduction

The Nexus AI Voice Assistant allows users to perform various tasks on their computer using voice commands. It supports opening and closing files and folders, listing directory contents, and accessing websites. Nexus listens for a specific wake word to activate and then executes the given commands.

Technologies Used
Python
SpeechRecognition
pyttsx3
pygetwindow

Requirements
Python 3.6 or higher
Internet connection for speech recognition

Installation Instructions

1. Clone the repository:
git clone https://github.com/SamratChanda26/AI-Voice-Assistant.git

2. Navigate to the project directory:
cd AI-Voice-Assistant

3. Install the required dependencies:
pip install -r requirements.txt

Usage Instructions

1. Run the main script:
python nexus.py

2. Speak the wake word "wake up Nexus" to activate the assistant.

3. Provide commands such as "open YouTube," "list files in the current directory," or "shutdown."

Features

Voice Activation: Nexus listens for the wake word to activate.
File and Folder Management: Open, close, create, delete, rename, copy, and paste files and folders.
Web Browsing: Open specific websites like YouTube and Google.
Directory Navigation: Navigate through directories and list contents.
Time Announcement: Get the current time on command.

Documentation

The code structure and main functionalities are documented within the script. The following functions are key to the operation of Nexus:

takecommand(): Listens to and recognizes voice commands.
replace_words_with_symbols(text): Replaces spoken symbols with their corresponding characters.
open_file(file_path): Opens a specified file.
open_folder(folder_path): Opens a specified folder.
close_window(window_title): Closes a specified window.
list_files(): Lists files in the current directory.
list_folders(): Lists folders in the current directory.
create_folder(folder_name): Creates a new folder.
delete_file(file_path): Deletes a specified file.
delete_folder(folder_path): Deletes a specified folder.
rename_item(old_name, new_name, item_type): Renames a file or folder.
copy_item(item_name): Copies a file or folder.
cut_item(item_name): Cuts a file or folder.
paste_item(destination_path): Pastes a copied or cut file or folder.
wake_word_detection(): Detects the wake word to activate the assistant.

Conclusion
Nexus AI Voice Assistant provides a hands-free way to manage your computer through voice commands. It enhances productivity and ease of use by allowing users to perform various tasks using natural language. Future improvements can include more advanced voice recognition and integration with more applications.