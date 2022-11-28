# DS4002Project3
# AI Is Scary

## Contents Overview:
This repository includes 3 folders:
- The DATA folder contains the .csv file that holds our data as well as a data dictionary
- The FIGURES folder contains the figures produced throughout our analysis
- The SRC folder contains the source code for our analysis

## SRC Folder:
### Installing and Building
Download any files in this section to your local computer. These files are written in Python, and it is recommended to use Visual Studio Code to execute.

### Usage
- First download the code file(s) from the SRC folder and the .csv file from the  DATA folder.
- The only piece of code that will need to be edited for correct usage is the file path. This appears in the second and third code chunks of the 'downloading images' section. Edit the path provided to the location of where you would like to store the poster images on your local computer.
- Code should be run chunk by chunk in a Jupyter Notebook if you wish to see all visualizations/plots.

## DATA Folder:

### Data Collection Process
The data we used for this project was sourced from different Letterboxd listings. We found lists of popular movies by genre, and used a Chrome extension called WebScraper to gather the movie title, poster URL, and genre. This information was stored in a .csv file that is located in the DATA folder.

### Access
The scraped and cleaned data can be found in the DATA folder, but the sites we scraped from for each genre can be found below:

<a href="https://letterboxd.com/darrencb/list/vote-best-comedy-films-of-all-time/">Comedy</a> | 
<a href="https://letterboxd.com/darrencb/list/letterboxds-top-250-horror-films/">Horror</a> | 
<a href="https://letterboxd.com/top10ner/list/100-fantastic-family-friendly-flicks/">Family</a> | 
<a href="https://letterboxd.com/darrencb/list/vote-best-romance-films-of-all-time/">Romance</a> | 
<a href="https://letterboxd.com/thefilmstage/list/the-film-stages-50-best-action-movies-of/">Action</a> | 
<a href="https://letterboxd.com/ccarneiro0707/list/timeout-100-best-thriller-films-of-all-time/">Thriller</a>

### Dictionary
Click this <a href="https://github.com/trnorrgard/DS4002Project3/blob/main/DATA/datadict">link</a> to access the data dictionary.

### Data Context
We wanted to develop a model that could predict movie genre based on its poster. Our data was scraped from multiple user-generated movie lists on Letterboxd, "a social media website for film lovers." Letterboxd contains accurate film data for over 3 million of its users to share, track, and save for later.

## FIGURES Folder:

#### AllGenres (1, 2, 3)
These figures are the confusion matrices of 3 separate CNN models trained and tested on the same data. The first image is our model with with the worst results, the third in the model with the best results. The second image is just one of our models between the first and last, and we altered and tested several models but felt including the results of all of them would be redundant.

#### DataSample (and URL)
These figures are samples of our data frames that we used for this project. URLDataSample shows what the .csv file from the DATA folder looks like, and DataSample is an example of the data the model uses to make predictions.

#### HorrorComedy
This figure contains the loss score, accuracy score, and confusion matrix for a model trained and tested with just horror and comedy movies. 

#### HorrorFamily
This figure contains the loss score, accuracy score, and confusion matrix for a model trained and tested with just horror and family movies. 

#### RomanceAction
This figure contains the loss score, accuracy score, and confusion matrix for a model trained and tested with just romance and action movies. 

#### RomanceHorror
This figure contains the loss score, accuracy score, and confusion matrix for a model trained and tested with just romance and horror movies. 

#### ThrillerActionHorror
This figure contains the loss score, accuracy score, and confusion matrix for a model trained and tested with just thriller, action, and horror movies. 

## REFERENCES:

### Preparatory Assignments:
<a href="file:///Users/teagannorrgard/Downloads/MI1-2%20(updated%20version).pdff">Milestone 1, get new link</a>

<a href="file:///Users/teagannorrgard/ds4001/MI2%20-%202.pdf">Milestone 2, get new link</a>

### Acknowledgements
We would like to thank Professor Alonzi and our TA Harsh for their help and guidance with this project :)

### References

[1] Christie, Charlotte. “10 Greatest Movie Posters of All Time, Ranked.” CBR, 17 May 2022, https://www.cbr.com/greatest-movie-posters-of-all-time/. 

[2] Taskinemre. “Letterboxd Horror Movies Eda.” Kaggle, Kaggle, 2 Sept. 2022, https://www.kaggle.com/code/taskinemre/letterboxd-horror-movies-eda/notebook#Top-Rated-Horror-Movies. 

[3] “Convolutional Neural Network (CNN)  :   Tensorflow Core.” TensorFlow, https://www.tensorflow.org/tutorials/images/cnn. 

[4] “Automatic Photographic Composition Based on Convolutional Neural Network.” IEEE Xplore, https://ieeexplore.ieee.org/document/7991056. 

[5] Hong Jing, “Predict Movie Earnings with Posters.” Towards Data Science, Nov 17, 2019, https://towardsdatascience.com/predict-movie-earnings-with-posters-786e9fd82bdc. 
