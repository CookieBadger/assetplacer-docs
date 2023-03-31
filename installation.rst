Installation
=============

The AssetPlacer is a paid plugin, therefore it is not available at Godot's built-in asset library. You can purchase the AssetPlacer plugin `here`_. 
Not all versions of Godot are supported by the plugin, so make sure you check that the plugin is compatible with the version you intend to use before you make your purchase. 
To install the plugin, follow the instructions below.

The AssetPlacer is developed in C#. Hence, to use it, you need to use a Mono version of the Godot engine, and have Mono or .Net installed.

1. Once purchased, retrieve and extract the downloadables. Make sure to choose the package that corresponds to your Godot version. 

2. Move the assetplacer folder into the addons folder of the Godot project, where you intend to use the plugin, such that the path to the plugin contents are ``res::/addons/assetplacer``. If the addons folder does not exist yet, create it. Note that it has to be called "addons".

.. image:: images/AssetPlacerFolder.png

3. In the top right corner of the editor, next to the play buttons, click the "Build" button.

4. Go to ``Project -> Project Settings -> Plugins`` and enable the AssetPlacer.

.. image:: images/ProjectSettings.png

5. On the bottom panel (next to Output, Animation, MSBuild, etc.), a new option "AssetPlacer" should have appeard. Click it, to open the AssetPlacer UI. 

.. image:: images/AssetPlacerBottomPanel.png

Congratulations, you are ready to use the AssetPlacer!



.. _here: https://boolbadger.itch.io/assetplacer