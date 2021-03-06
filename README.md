# Predicting Genre from Movie Posters

### ABSTRACT<br />
Advertising movies with posters is an incredibly significant part of the film industry's marketing strategy, which intends to increase viewership and profits. With a good movie poster, a film's theme and genre can be conveyed to a wider audience, making the movie appear intriguing and appealing. In this project, specifically, we want to find out if a model could be trained to detect the movie genre by learning the features of the poster. Our goal was to examine not only the visual aspects of the poster but also analyze the textual information, to see if it can reinforce the model. In combination with textual learning, ResNet50 was able to predict movie poster genres fairly accurately. This suggests that the visual elements included in movie posters of a given genre are relatively consistent.

File structure below:
/models (contains 3 code files)
- ResNet34.ipynb
- ResNet50-OCR.ipynb
- ResNet50.ipynb

/src
- Tesseract_Text_extractor.ipynb

/dataset
- Scrapper.ipynb
- imageResizing.ipynb
