<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# AI-Powered Handwritten Digit Recognizer

Final project for the Building AI course

## Summary

Create a simple AI model that recognizes handwritten digits (0-9) using a Convolutional Neural Network (CNN) and the MNIST dataset. The project will include a small web interface where users can draw a digit, and the AI will predict the number. 


## Background

This project solves the problem of digit recognition from handwritten inputs, which is a real-world challenge in multiple industries. Some common applications include:

* Digitizing handwritten documents (e.g., forms, bank checks).
* Automated data entry (reducing human error in manually entering numbers).
* Assistive technology (helping visually impaired users interact with technology).



## How is it used?



### How to Use the Solution?
* User Opens the Web App – A simple interface appears with a canvas where the user can draw a digit.
* User Draws a Number (0-9) – They use a mouse, stylus, or touch input to write a digit on the canvas.
* AI Processes the Input –
  * The image is preprocessed (resized, converted to grayscale, normalized).
  * The trained CNN model predicts the digit.
* Prediction is Displayed – The system shows:
  * The predicted digit (e.g., "You wrote: 7").
  * Confidence score (e.g., "I'm 92% sure").
* User Can Try Again – They can clear the canvas and test with different digits.

 ### When & Where is This Solution Needed?
* Educational Environments – Schools, coding workshops, AI learning.
* Banks & Financial Institutions – Digitizing handwritten numbers on checks.



Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat]()

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods


## Challenges

* Speed & Real-Time Processing
* Handling Multiple Languages & Symbols

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
