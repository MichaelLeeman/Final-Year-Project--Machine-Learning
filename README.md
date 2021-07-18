# University Project: Machine Learning
This was my project I did for my final year at university. It's a 2D platform game with machine learning AI that's capable of racing the player to the end of the level. 

This repo only contains the scripts that I wrote to create the platformer game and to train the machine learning agents.


![](/images/Game.png)
## Table Of Contents
* [About](#about)
* [Technologies](#technologies)
* [Images](#images)

About:
--------------------------------------------------------------------------------------------
The project was split into two parts; create a 2D platformer game from scratch, and build and train the machine learning agents how to play the game.

The game was created in Unity and the machine learning agents were created using the Unity Machine Learning Agents SDK.

The machine learning AI was trained using PPO and with multi-agent training. The training was further optimised using curriculum learning and hyperparameter tuning.


Technologies:
---------------------------------------------------------------------------------------------

Project was created with:
* Unity
* C#
* TensorFlow

Images:
---------------------------------------------------------------------------------------------

![](/images/ObjectDetection.png)

This image shows the AI's circle-cast observation. The black lines originating from the player are ray-casts to help the AI detect objects. These ray-casts can help the AI to 'see' the ground, obstacles and the objectives.

![](/images/MultiVsSingleReward.png)

This graph shows how well the AI learns when using a single agent(green) compared to multiple agents(grey). The multi-agent training can be seen to achieve the maximium amount of cumulative rewards in less steps than single-agent training. Hence, it is quicker to train with multi-agent training than single-agent training.