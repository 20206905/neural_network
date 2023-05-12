# neural_network
The implementation for my dissertation "Predicting the Weight of a Human from a Photo".

# How to run

## Pre-requisites:
- Have Node.js installed.
- Have Visual Studio Code installed.
- Have Google Chrome installed.

## For Windows.

### neural_network
1) Next, enter "cd .." into the built-in terminal to go back into the parent directory.
2) Then, enter "cd neural_network" to enter the "neural_network" directory.
3) Then, enter "node app.js"
4) Then again, enter Google Chrome and navigate to "localhost:3000".
5) Enter into the Console to see the estimations for the images in the testing dataset, the Mean Absolute Error and Mean Absolute Percentage Error as well.

In the above the "anthropometricFeatures.json" file created in the "new" folder is loaded into the "sketch.js" file into an array called "data". A testing dataset is then taken from this at random, then the model is trained and tested. The results of the tests are in the Console along with the Mean Absolute Error and Mean Absolute Percentage Error.
