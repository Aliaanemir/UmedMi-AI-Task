# UmedMi-AI-Task

The solution to the required technical task
___
## Table of Contents

- [First Part - U Intern Task](#U-Intern-Task)
- [Second Part - Digit Recognizer](#Digit-Recognizer)
- [Third Part - Fake News Identifier](#Fake-News-Identifier)
___
## U Intern Task
### Part One

#### Q1
A loop is run 4 times (number of terms), a string of the number 'a' is created, and incremented by a digit,Then converted to an integer and added it to the total output.

#### Q2
Using Timeit, the time taken to execute the code snippet is calculated.

#### Q3
The input is splitted and divided into tuples, which are then sorted by sort() functions, which by default sorts ascendingly according to the elements' order in the tuple.

#### Q4 
To build a dictionary of the character's frequency, we loop through the letters in the sentence, append keys for new characters, and increment the ones previously present by 1.

#### Q5
The required conditions is checked by an if statement, and the functionality is tested on a list of the given cases.

#### Q6
Using datetime library, the current exams time is obtained, and the second element is incremented by 5 seconds.

#### Q7
The input coeficients are splitted, converted to float and put into a list, which is passed along with the value of X to the polyval() function.

#### Q8
The dimensions of the square matrix(NxN) is obtained from the user, then a loop lists every row in the matrix and appending it to the list mat to create the matrix, then the value of the matrix' determinant is obtain by numpy.linalg.det() function and rounded to two decimals.

### Part Two 
The GUI is made using tkinter library.

Functions used:
- click(): to display the clicked button's character.
- clear_display(): to clear the display whenever 'C' button is pressed.
- calculate(): to evalute the mathematical expression input by the user.

Buttons and entry architecture is then specified, along with the command finction of each button.
___
## Digit Recognizer
**Description**: 6 layers Sequential Convolutional Neural Network for digits recognition, trained on MNIST dataset.

**Tools**: 
- For Data Exploration and Preprocessing: pandas, numpy, matplotlib and seaborn.
- For Model training and evaluation: tensorflow.keras (layers: Dense, Flatten, Conv2D, MaxPool2D)

**Result**: The model labels the numbers in an image with accuracy 98.845%.

___
## Fake News Identifier

**Description**: 5 layers Sequential Recurrent Neural Network for identify whether news are real or fake, trained on both fake and real datasets from kaggle.

**Tools**: 
- For Data Exploration and Preprocessing: pandas, numpy, matplotlib, seaborn, re, tensorflow.keras.preprocessing and pickle.
- For Model training and evaluation: tensorflow.keras (layers: Dense,Embedding,LSTM,Dropout)

**Result**: The model categorize the news with accuracy 98.920%.
