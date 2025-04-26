# Next word prediction
Simple application using transformer models to predict the next word or a masked word in a sentence.

The purpose is to demo and compare the main models available up to date.

The first load takes a long time since the application will download all the models. Beside 6 models running, inference time is acceptable even in CPU.

### Application
This app implements two variants of the same task (predict <mask> token). The first one considers the mask word in between a sentence and the second one predicts the word at the end of the sentence, simulating a prediction of the next word of the sentence.

The second variant is necessary to include a <mask> token where you want the model to predict the word.


### Running 

```
flask --app app run --debug
```

Open your browser http://localhost:5000






https://github.com/Biplab96Das/Next-word-prediction-using-Transformers/assets/31479620/3ae924d7-23a3-48a2-82e4-c62962ea1048

