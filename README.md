# TouchDesigner-OpenAI-API

TouchDesigner version 2023.11340

## Install Python 3.11.0

Download link: https://www.python.org/downloads/release/python-3110/

- macOS > terminal.app    
- windows > cmd

```pip install openai```
or
```pip3 install openai```

## In TouchDesigner    
setting (or preference) > Python 64-bit Module Path

macOS    
```/Library/Frameworks/Python.framework/Versions/3.11/lib/python3.11/site-packages```    
    
windows    
```C:\Users\ USERNAME \AppData\Local\Programs\Python\Python311\Lib\site-packages```

- Save TouchDesigner project and Quit
- Restart project file, then drag and drop the TOX file.

### API-KEY
In this file, there is no API KEY. Paste your own key to "API Key" parameter.    
And you have to activate your API KEY


### Using Text to Speech    
It requires you to specify a folder for TTS mp3 file.    
Create a folder and specify in Text_to_Speech base parameter "Folder".


