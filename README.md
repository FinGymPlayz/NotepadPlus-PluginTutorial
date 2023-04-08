# How to make a NotepadPlus Plugin

Plugins allow you to modifiy notepadplus, by changing the theme, making window. And much more!

# 1. Setting up your environment

To set up your programming environment, you first need an IDE. I personally recoment <a href="https://code.visualstudio.com/download">Visual Studio Code</a>. This is a IDE that works for most operating systems, including <i>Windows, Mac and Linux</i>. When you have downloaded your IDE of choice, you will have to make sure that .py files will open in your IDE. To do this, Please follow the steps below!

Create a .py file

<img src="https://raw.githubusercontent.com/FinGymPlayz/NotepadPlus-PluginTutorial/main/file_creation.png" width=150>

Right Click on the file and hover over <i>Open With</i> and select <i>Choose another app</i>

<img src="https://raw.githubusercontent.com/FinGymPlayz/NotepadPlus-PluginTutorial/main/choose_another_app.png" width=300>

From there click the IDE of choice, in my example, i would choose <a href="https://code.visualstudio.com/download">Visual Studio Code</a>.

<img src="https://raw.githubusercontent.com/FinGymPlayz/NotepadPlus-PluginTutorial/main/chose.png" width=250>

Then from now you can close of the window that just opend, and delete the file you just created

# 2. Launching the console, and clearing old plugin data.

To use the NotepadPlus console, you first have to <i>launch the program</i><br>
and then type<br>
<i>>con</i><br>
This will open up a console window.<br><br>
<br>
We have now launched our console, we now need to type a few commands in here to get started. We first need to remove any other plugins. So we can type<br><br>
`cleardir` --> Clears everything in the plugin directory<br>
<br>
and<br>
<br>
`removeplugin` --> This will remove the main code to the other plugins.

# 3. Creating our plugin via the console

To create our plugin, we have to run some more commands, this includes<br>
<br>
`build` --> Creates the main files for the plugin<br>
<br>
`pluginpy` --> Creates the main code file for our plugin<br>
<br>
Now we have made the main files for the plugin, we can use the template code for the plugin by typing:<br>
<br>
`plugindefaults` --> template code for the plugin
<br>

# 4. Coding the plugin in our IDE

We have now set up our plugin via the console, but now we need to actually make the plugin function,<br>
You can edit the code by typing in the console<br>
<br>
`plugin` --> launches the plugin code for you to edit
<br>
