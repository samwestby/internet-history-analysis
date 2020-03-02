# internet-history-analysis
This project is a quick analysis of my BrowserHistory.json file from Google Chrome.

## Getting Going
Download this project and unzip it in your desired location.
Navigate to that location in a terminal.
Then create a virtual environment

    python3 -m virtualenv env

Activate it and install the required modules

Linux/Mac

    source env/bin/activate
    sudo apt-get install portaudio19-dev libffi-dev libssl-dev
    sudo python3 -m pip install -r requirements.txt
    
Windows

    source env/bin/activate
    python3 -m pip install -r requirements.txt
    
 ## Get your Chrome Browsing History
 Navigate to [takeout.google.com](https://takeout.google.com/)
 Deselect all options except "Chrome"
 Click on "All Chrome data included" and only select "Browsing History"
 Click "Next"
 Click "Export"
 Wait for an email saying your file is ready
 Open the email and click "Download"
 Unzip that folder
 Navigate to \takeout-XXXXXXX\Takeout\Chrome\BrowserHistory.json and copy that file into the directory for this project
 
 ## Execute
 In your terminal type
 
    jupyter notebook
    
 Follow the prompts to open the notebook.ipynb file.
 
 Run each cell in the notebook 
