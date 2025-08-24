Hello everyone,

After I finished my Machine Learning courses I took over the summer, I decided to do a project by myself and I want this project to related to something I like. And then I decided
working with a deck of cards would be a great fit. So now there is my first ever Machine Learning project. The main idea of this project is that it inroduces a deep learning model 
built with TensorFlow which classifies/recognizes a card from its picture. 

Since I'm very new to the coding and ML projects, I regard the notes from the course [Advance Learning Algorithms](https://www.coursera.org/learn/advanced-learning-algorithms) as a 
template and then built my model on it. However, the notes I had was classifying handwritten numbers from 0,1,..,9 whereas my project classifies 52 different cards. That's why after 
some point on, code changed drastically from the original template. 

Since I wanted to be involved in every step of this project, I collected most of the data online but I also included some pictures I took. I also used pictures taken by me while 
testing my model. I trained my model with over 8500 pictures (including augmentations such as rotating) where the original pictures can be found in this [link](https://drive.google.com/file/d/10xMGaRIGqsNgeBzlzgHh_A74Z4eKSQd_/view?usp=sharing).
After training, I tested my model with 4 decks of cards (208 cards in total) and at the end, it worked with over 85% accuracy. The data about its accuracty can be found on the 
related file in the repository. 

My two main goals after this project are: 
1. Working on card detection instead of recognition. Meaning that a model that can detect which cards are shown to it from their video or picture.
2. Building a project which can decide what actions to be taken on a card game based on your hand. 
