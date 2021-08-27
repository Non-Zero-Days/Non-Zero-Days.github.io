## Visual Studio Code

### Prerequisites:
Install [Visual Studio Code](https://code.visualstudio.com/Download)

### Loose Agenda:
Gain familiarity with basic workflows in Visual Studio Code

### Step by Step
Create a directory for this exercise

Open Visual Studio Code

Select File > Open Folder and select the directory that was created in the first step

On the left side nav menu select the topmost icon to open the Explorer window (Alternatively, use the hot-key Ctrl+Shift+E)

Right click in the Explorer window, select "New File" then enter the name simple.txt

Enter some text into the file then Ctrl+S to save the file

Use the hotkey Ctrl+Shift+P to open a command window then search for and select New File

Name the file simple.md and enter the following code
```
# Title
## Subtitle
The following words are list items
- List Item 1
- List Item 2

This part is a code snippet
    ```
    <html></html>
    ```

[Sometimes you need to link stuff too](https://github.com/Non-Zero-Days/vs-code)

![Sometimes you need to embed an image](https://avatars2.githubusercontent.com/u/73706952?s=200&v=4)

Other times you just need to create **bold text** or *italic text*

```

Use the hotkey Ctrl+Shift+P then search for and select Markdown Open Preview

Create another new file named simple.html and start typing some simple code without formatting (Note that Visual Studio Code is making suggestions as you type the code)
```
<!DOCTYPE html>
<html>
<body>
<input type="button" />
</body>
</html>
```

Open the command window again with Ctrl+Shift+P then search for and select Format Document

Review the results and save the simple.html file

Use Ctrl+Shift+F to open the search window then search for 'html' (Note that the search tool is searching the contents of the files in the open folder)

Use Ctrl+Shift+X to open the extensions window then search for and install 'Browser Preview' by Kenneth Auchenberg

Navigate back to simple.html then use Ctrl+Shift+P to search for and select 'Open Active File in Preview'

Note that if you change the html (such as below) then you will have to refresh or re-run the 'Open Active File in Preview' command
```
<!DOCTYPE html>
<html>

<body>
    <input type="button" />
    <input type="text"/>
    <textarea></textarea>
</body>

</html>
```

Ctrl+Shift+E to open the Explorer window then right click and create a folder named 'folder-1' then right click the folder and create another folder named 'folder-2' (Note that these folders immediately compact down because they are empty)

Use Ctrl+Shift+P to search for and select 'Open Settings (UI)' - This is a settings page for almost all Visual Studio Code customizations/preferences

Search 'Compact Folders' then uncheck the setting

Note in the Explorer window that these folders are now use a nested experience instead

Back in settings, choose your preferred setting for this Compact Folders and feel free to browse for other customizations you may wish to make

Congratulations on a non-zero day!
