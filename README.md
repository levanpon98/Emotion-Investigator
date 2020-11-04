[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# :sunglasses: Facial Expression Recognition Classifier Model 

A Facial Expression Recognition Classifier Model that takes
**Real-time Video input** and predicts the **Emotion of users** present in front of
Webcam. It also gives **Graphical Visualization** of Expressions when we feed in an
Image via Web Cam or manually !

![images](https://user-images.githubusercontent.com/57671048/98015631-031f3e80-1e23-11eb-9adc-70fd489cc004.png)


## :loop: Tech Stack used 
- Deep Learning Techniques : Convolutional Nueral Networks (CNN)
- Python
- Flask


## :golf: Predictions done by Model 
<img width="896" alt="sad" src="https://user-images.githubusercontent.com/57671048/98131077-f103d580-1ee0-11eb-9dc3-905f3884ee1b.png">
<img width="897" alt="angry" src="https://user-images.githubusercontent.com/57671048/98131265-1e508380-1ee1-11eb-92b5-12c7677c08c0.png">
<img width="884" alt="happy" src="https://user-images.githubusercontent.com/57671048/98131204-10026780-1ee1-11eb-999b-0182a68ce529.png">



## :boom: Steps to run the Project in your local device !!
- Fork this repository.
- Clone the repository to your System using `git clone`
- Example : `git clone https://github.com<your-github-username>/Facial-Expression-Recognition-Classifier-Model`
- Open any **Python** IDE and run the `fer_main.py` file to make Facial Expression Recognition of **Live Image** taken using your Web Cam !
- In case, If you want to try with Images you already had in your system follow the below steps
- Just upload them in `static` folder of the Folder `FER_on_Manually_Uploaded_Image` 
- Now open any **Python** IDE and run the `fer_main_Manual_U.py` file.


## :computer: Coding Structure:

- Import the required Packages and Libraries.
- Data analysis and Creating Training and Validation Batches.
- Create a CNN using 4 Convolutional Layers including *Batch Normalization*,
*Activation*, *Max Pooling*, *Dropout* Layers followed by *Flatten* Layer, 2 Fully
*Connected dense* Layers and finally Dense Layer with *SoftMax* Activation
Function.
- Compile the model using `Adam` Optimizer and categorical cross entropy
loss function.
- Training the model for 15 epochs and then Evaluating the model as well as
saving the model Weights in `.h5` Values
- Saving the model as `JSON` string.
- Creating a Class in a separate file to reload the model and its weights to
make predictions and return the probabilities of each emotion.
- Creating one more class in a Separate file which takes in the `Real-time
Video input` and returns frames of Images with a Circle detecting the face
and putting text of its emotion on it.
- A python script is also created which upon running yields the `Graphical`
`Visualization` of Emotions present in the Image provided.
- Finally creating a file which inherits form all the Classes defined by us and
deploys our application using *Flask*.

## :innocent: We can further improve the Validation Accuracy of the model by tuning the hyperparameters like:
- Learning Rate
- Epochs
- Batch Size
- Number of Layers in CNN
- Number of filters
- Size of filters
- Value in Dropout Layers
- Optimizers

## Future Scope of the Project :exclamation:
1. Making the **Frontend** Attractive :fire:
2. Suggesting **Music** based on Facial Emotion predicted :musical_note:
3. **Deploying** the Model :earth_asia:

## Steps to Contribute to this Project ! :point_down:
- Fork this repository
- Clone the repository to your System using `git clone https://github.com<your-github-username>/Facial-Expression-Recognition-Classifier-Model`
- Create a branch :-
   - Change to the repository directory on your computer `cd Facial-Expression-Recognition-Classifier-Model`
   - Now create a branch using the git checkout command: `git checkout -b your-new-branch-name`
- Make changes as per your requirement to solve the Issues mentioned in the `Future scope of the Project` and commit those changes.
- If you go to the project directory and execute the command git status, you'll see there are changes. Add those changes to the branch you just created using the `git add`
- Now commit those changes using the git commit command: `git commit -m "Added the feature of Suggesting Music"`
- Push your changes to GitHub using the command `git push origin <add-your-branch-name>`
- If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.
- Now describe the changes you made and submit the `pull request`.
- Wait for the Maintainers to review :)

### Any type of Contributions like Pull Requests, Issues are always welcomed ! :tada:
