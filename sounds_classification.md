## Reducing Emissions in Car Carriers: An AI-Based Alert System

As a kid me and my parents often went to places like Sardinia or some greek Island. As we wanted to take our car with us, we always used an auto ferry to get there. Life was good, until we got to the moment of disembarking. All passengers were called to the car decks to wait by their cars. These decks can get quite warm, especially in the mediterranian summer, so a lot of people had the idea to get into their cars and turn the engine on in order to get the air conditioning to work. While this was nice for them, it is not ideal to have a lot of cars with engines running in a confined space with limited ventilation, as this further increases the temperature and, more importantly, increases the amount of exhaust fumes all passengers outside of cars have to breath. While there were signs that said it is not allowed to leave the car off, the sailors where too busy with the docking operations to enforce this.
With this project we wanted to create an AI that can be used to recognise the sound of idling engines in order to give automated warnings, either visual or acoustic. This can be used at any place where cars are not supposed to be left running in confined spaces, such as ships, enclosed trains and underground parkings. 

This project was developed in collaboration with a friend, [Matthias Bressan](https://matthiasbressan.github.io/).

### 1. The data
We took the database from kaggle [8kUrbanSounds database](https://www.kaggle.com/datasets/chrisfilo/urbansound8k). This data set contains urban sounds (including engine idling) in .wav file of lenght of up to 4 seconds.

### 2. Preprocessing
Firstly we created a balance dataset to train our model to distinguish engine idling between all the other city sounds.to create the dataset we took all the engine idling files and the same amount of all the other classes with a random distribution. 



<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 3. Our model

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Results

### 5. Next steps and improvements
Use a larger data set to retrain the ne

