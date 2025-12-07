# PythonExpress
Our project is going to be a reimagined take on the classic game Snake. It will have virtually the same functionalities as the original, including randomly spawning people to pick up, the train growing in length per person, and losing if the train runs into itself or the walls.

To run PythonExpress, simply run the main.py file.
This file calls on the other Python files to draw the game and compute the game logic.

# Requirements
Make sure to have Python installed, 
Libraries/Modules imported: 
        
    easygui, pygame, random, os, csv, datetime, enum

# File Structure
For Windows:

    PythonExpress/
        game/
            graphics/
                car_down.png
                car_left.png
                car_right.png
                car_up.png
                old_person.png
                person.png
                train_down.png
                train_left.png
                train_right.png
                train_up.png
            gameBoard.py
            gameLogic.py
            main.py
            oldPeople.py
            people.py
            playerProfile.py
            train.py
            profiles.csv

For Mac:

    PythonExpress/
        game/
            gameBoard.py
            gameLogic.py
            main.py
            oldPeople.py
            people.py
            playerProfile.py
            train.py
        graphics/
            car_down.png
            car_left.png
            car_right.png
            car_up.png
            old_person.png
            person.png
            train_down.png
            train_left.png
            train_right.png
            train_up.png
        profiles.csv
