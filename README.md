# MyProjectHyperDash
This is my final year project called HyperDash. A 2D platform game that uses machine-learning agents to race the player to the end of the level. 

Info:
--------------------------------------------------------------------------------------------
The source file uploaded onto keats contains the scripts that I independently wrote. Please refer to the GitHub repo to see the other scripts that were adapted or taken from an open-source library ( https://github.com/m-leeman/MyFinalYearProjectHyperDash)


Installation:
---------------------------------------------------------------------------------------------

HyperDash can be installed from the GitHub repo: https://github.com/m-leeman/MyFinalYearProjectHyperDash


To run HyperDash Unity has to be installed: https://store.unity.com/download?ref=personal

The Unity ML-agents toolkit version 4.0 also has to be installed: https://github.com/Unity-Technologies/ml-agents/tree/0.4.0b

Please follow the Unity ML-agents installation guide when installing the ML-agents toolkit: https://github.com/Unity-Technologies/ml-agents/blob/0.4.0b/docs/Installation.md

The TensorFlowSharp plugin also has to be installed: https://s3.amazonaws.com/unity-ml-agents/0.4/TFSharpPlugin.unitypackage

More details on the TensorFlowSharp installation can be found here: https://github.com/Unity-Technologies/ml-agents/blob/0.4.0b/docs/Using-TensorFlow-Sharp-in-Unity.md

After the plugin and toolkit have been installed please open the project in Unity and do the following to enable the ML-agents toolkit:

1) Go to Edit --> Project Settings --> Player 
2) Click the Other Settings tab and scroll down to "Scripting Define Symbols"
3) Type in "ENABLE_TENSORFLOW"


HyperDash can now be played in the Unity Editor by selecting the main menu scene in the scene folder and pressing the play button at the top. HyperDash can also be played by building the application in the file --->build settings and making sure that the main menu and main game scenes are selected as scenes 0 and 1 respectively before builiding and running the game. 
