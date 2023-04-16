Frequently Asked Questions (FAQ)
================================

Why is this not free?
------------------------

We all love open-source software like Godot for its accessibility and the freedom it gives to users. We then make games with it, which are - in most cases - commercial. 
Of course, game devlopers have fun while making games, in the best case, but they still have to pay their bills, thus charging for their work is perfectly valid. 
Many commercial platforms for acquiring assets, such as 3D models exist as well, such that artists can be remunerated for their work, even though it should fit a general purpose. 

This plugin is neither a game, nor does it contain assets for a game, but still months of development time have been spent to make it as useful as possible. 
As gratification alone cannot buy any food or pay rent, this plugin is being given away for a small amount of money. 
Considering the time you can save by using it, especially when using modular assets, it seems like a very fair price to me. 
The plan is, to keep developing the plugin, by adding new features and maintaining compatibility with major engine versions. 
As you receive the source code of the plugin directly, you are also free to make any changes as you see fit, if you ever need to change something. 
Your freedom of use is as unlimited as I can make it, and as much as I would like to give the plugin away for free entirely, I am grateful for everybody who appreciates my work by buying it fairly.


I can only find the C# version. Where is GDScript?
-----------------------------------------------------

At the moment, this plugin is written in C# only. The choice to develop it in C# was made, because of the large amounts of code and the frequent use of abstraction and high-level language features. 
This is much easer to handle with a powerful language with a powerful external IDE. As you might be aware, C# code can only be run in the Mono version of the Godot engine, which requires .Net or Mono to be installed, which might be annoying for some of you.
I am sorry for this inconvenience. Maybe I will translate the plugin to GDScript eventually, but for now it is the way it is.


Is there a way to use this plugin for 2D levels?
-------------------------------------------------------

Currently, the plugin only features tools for 3D levels, but I thought about adding tools for 2D as well. Separating the AssetPlacer into an AssetPlacer3D and a AssetPlacer2D (i.e. having two bottom panels) would be an option, that might be implemented in the future.


My assets show no preview thumbails. What is wrong?
------------------------------------------------------

This can happen sometimes, especially when you open a project for the first time on a different computer. If you want the preview for a .tscn file, then open the file and save it, this way the thumbnail is generated.
If you want to see the thumbnails of some 3D models, you have to reimport them (change them to be imported as a mesh and then back to import as a scene). 
Unfortunately, this requires restarting the editor at the moment, but if a more efficient alternative for this problem is found, I will try to implement it.


I added the plugin, but I cannot enable it!
----------------------------------------------------------------------

Make sure to press the "Build" button at the top right before you enable the plugin. If the button does not show up, create a new C# script in your project and delete it again. It should show up now. 
Once you built the plugin without errors (check the build output), you should be able to enable it in the project settings.
In case this does not fix a problem, feel free to write a comment on the `itch`_ page of the plugin, describing your issue and I will do my best to help! 


What can I use the source code for?
----------------------------------------

You bought the plugin, then you own it. You can modify the source code however you see fit, use it for any amount of projects on any number of machines. 
If it somehow is of use to you, you may also use parts of the code inside any game you are making. 


How long / for how many projects may I use the plugin? Will I receive updates?
-------------------------------------------------------------------------------------

There is no restriction to the usage, use it in any amount of projects for as long as you want! As long as the plugin is still in development, you will also receive accesss to any updates bringing new features, or compatibility with newer engine versions.


I found an issue with the plugin. Where should I report it?
---------------------------------------------------------------

Feel free to describe any issue you are having, or any other thoughts you have about the product as a commment on the `itch`_  page. 


You should implement this and that! Also, I had an idea for another tool!
--------------------------------------------------------------------------

As described in the other answers, you can always write a comment on the `itch`_ page of the plugin. 
Please take into account, however, that the focus of the development might lie in improving stability, and thus bugs will be prioritized over features. 
Also, not every feature is feasible to implement, since this is a one man project, and requests might also be declined for features that might only serve a specific use case or a very limited amount of users.


.. _itch: https://boolbadger.itch.io/assetplacer