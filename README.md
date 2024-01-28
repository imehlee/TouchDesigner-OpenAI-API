# TouchDesigner-OpenAI-API

TouchDesigner version: 2023.11340

##install python 3.11.0

macOS > terminal.app    
windows > cmd

3.
```pip install openai```

4.
Touchdesigner > setting (or preference) > Python 64-bit Module Path

macOS    
```/Library/Frameworks/Python.framework/Versions/3.11/lib/python3.11/site-packages```    
    
windows    
```C:\Users\ USERNAME \AppData\Local\Programs\Python\Python311\Lib\site-packages```

5.
In this file, there is no API KEY. In textDAT 'text_apiKey', paste your own key.

6.
*ONLY Text to Speech* 
It requires you to specify a folder for TTS mp3 file. 
Create a folder and specify in Text_to_Speech base parameter "Folder".
