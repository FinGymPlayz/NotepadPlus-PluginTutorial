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

# 4. Launching the plugin code file with our IDE

We have now set up our plugin via the console, but now we need to actually make the plugin function,<br>
You can edit the code by typing in the console<br>
<br>
`plugin` --> launches the plugin code for you to edit
<br>
This should open your IDE of choice, if not type the command `npnp` in the console, and open the plugin.py file in your IDE
<br>
# 5. Coding our plugin!

Now we are ready to code!<br>
<br>
There are many functions and classes you can use in notepadplus, if you are using <a href="https://code.visualstudio.com/download">Visual Studio Code</a> i recomend installing the following extensions:<br>
<br>
`Python`
<br>
`Code Runner`
<br>
There is too much to go over, so i may post a video, or make another repository about it!<br>
But i will go over that the `npp.main()` code block will run notepadplus!
# Testing your plugin

To test your plugin in <a href="https://code.visualstudio.com/download">Visual Studio Code</a>, you first have to install the [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) Extension.<br>
After installing the extension, you should be able to see a run button at the top right of the screen<br>
<img src="https://raw.githubusercontent.com/FinGymPlayz/NotepadPlus-PluginTutorial/main/run_btn.png"><br>
Click that to run your plugin!<br><br>


If you are on another IDE, type `run` in the NotepadPlus console!

# 6. Compiling our plugin

To compile our new plugin, you first have to make sure that the plugin code has saved!<br>
next type `compile` in the notepadplus console. and then choose a location in which you want to save the .zip file!<br><br>

When saved you can now send your plugin to friends and load them in by dragging the .zip in to the notepadplus window!

# Publishing your plugin to the webstore

If you want to publish your plugin to the notepadplus webstore, first, you need to create a [github account](https://github.com/)<br><br>
Next, Create a repository and call it something like <i>NotepadPlus-Plugins</i> and make sure its PUBLIC!<br><br>
Afterwards, you need to upload your plugin and get the link, [shown in this video.](https://youtu.be/r8772QHvOXo)<br><br>
After obtaining the link. You now need to create a json for your plugin by [using the template shown here](http://npnp.lifeserverf.org/json)<br><br>
Lastly head over to the [upload](http://npnp.lifeserverf.org/upload) website to then get it verified. This process can take up to 2+ days<br>You will then get an email back saying if your plugin has been verified or not. If it has been verified, your developer profile, and plugin will be on the webstore<br>

# What is a developer profile?

A developer profile is a profile that you will get after uploading your first plugin. It will contain your name, the amount of pluins you have uploaded, and all the plugins you have made! For users to find your developer page, they can ether search your name in the <i>Search For Plugin / Developer</i> tab. Or find one of your plugins on the browse menu, and click the open button, to the click your username in purple!

# Developer Tips

1. Always update to the latest version if this has not been done automaticually<br><br>

2. Explore the console by using the `help` command!
