
# Geospatial Name Entity Recognition

This project is an NER application which can extract names of cities, states and countries (places) from a natural language sentence. This project was selected as top 5 in India amongst 220 teams for the Smart India Hackathon 2023, on a problem statement by the Indian Space Research Organization (ISRO).


## Contributors

- [Aryan Shukla](https://www.github.com/aryanshukla7)
- [Shreya Jain](https://github.com/shreya5627)
- [Aashray Gupta](https://github.com/aashraygupta2003)
- [Aman Kumar](https://github.com/Aman-garg-IITian)


## Deployment

To deploy this project, simply run the ```main.ipynb``` notebook keeping ```states.csv```, ```cities.csv``` and ```countries.csv``` as well as the checkpoint for the re-trained [model](https://drive.google.com/drive/folders/1EU8MXSFWmifYHnJUdYSgd0dpR4PmNlH6?usp=sharing) that we trained on our local machine in correct path as mentioned in the notebook.

- After running the ```main.ipynb``` notebook, it should look something like this:
![Screenshot from 2023-12-26 11-03-59](https://github.com/aryanshukla7/Geospatial-NER/assets/79625246/249894d9-8c04-4b23-b4d9-3cbd0799dc8e)

- The streamlit version of the application can also be run by running the ```streamlit.ipynb``` notebook on google colab and uploading ```app.py```
- After running the ```streamlit.ipynb``` notebook it should look something like this:

![Screenshot from 2023-12-26 11-46-51](https://github.com/aryanshukla7/Geospatial-NER/assets/79625246/f50c47bb-bef8-4d09-bc51-015be0ce8bc1)


- Go to the link suggested by the __your url__ and enter the ip address obtained after running ```!wget -q -O - ipv4.icanhazip.com```

- After doing so, you will enter the Streamlit App,
![Screenshot from 2023-12-26 11-46-02](https://github.com/aryanshukla7/Geospatial-NER/assets/79625246/4891277c-70c9-4014-a858-ff583b02fb9c)

### Note:
- Make sure to replace the links of data files (from Data folder) and model checkpoint in the drive in the ```app.py``` file.
- The model also works for Hindi langauge sentences.
