# Motivation

Whoop whoop whoop -a nuclear plant is suffering a blackout, Rolls Royces' power engines kicked in to keep the fuel rods at a safe cool temperatures. Suddenlyn one of the engines fails, it sets on fire!

To prevent a fallout from happening, you have 36 hours to program a drone that:
- takes off when the start-light switches from red to green.
- autonmomously flies through the plant.
- identifies the buring engine and sends out a picture of it.
- lands safely on the starting pad.

That was Rolls Royces' challenge to us during the StartHack 2018 hackathon in St. Gallen, 23-25 February 2018.

# User Guide

The code is as structured as a hackathon permits it to be ;) You may start your exploration in the _fly.py_ file.

Upon completion of the training, the algorithm stores the [model](https://github.com/ckauth/AI_Noelinis/blob/master/training/NoeliniModel.dnn). You may test the performance of the model on single images of your choice with this [script](https://github.com/ckauth/AI_Noelinis/blob/master/training/evaluate_model.py).
