# markdown_html
This is a simple Python script that converts Markdown files (.md) into HTML files using the markdown library. The project also includes a GUI built with tkinter, making it easy for users to select a Markdown file and convert it to HTML with a few clicks.

Features
Markdown to HTML Conversion: Convert .md files to .html.
Simple GUI: Built with tkinter for an easy-to-use graphical interface.
File Selection: Choose the input Markdown file and specify the output HTML file location.
Status Notifications: Display status updates and success/error messages.
Requirements
To run the project, you'll need to have the following Python packages installed:

markdown: For converting Markdown to HTML.
tkinter: For the GUI (usually comes pre-installed with Python).
messagebox: For pop-up notifications.
You can install the required dependencies using pip:

pip install markdown
Installation
Clone the repository or download the files to your local machine.

git clone https://github.com/Pratyaksh005/markdown-to-html-converter.git
Install the required dependencies:

pip install markdown
Run the GUI by executing gui.py:

python gui.py
Usage
When you launch the GUI, click on the Convert Markdown to HTML button.
Select the Markdown file (.md) that you want to convert.
Choose a location to save the resulting HTML file.
The status will update to reflect the progress of the conversion.
Once the conversion is complete, a success message will be displayed.
You can also use the Clear Selection button to reset the selection and start over.

File Structure
/markdown-to-html-converter
    ├── gui.py              # The main GUI script
    ├── main.py # Script that handles the conversion logic
    └── README.md           # Project documentation
