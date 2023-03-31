# CNN Genre Classification
Genre Classification project with GTZAN dataset, using CNN.

Test Accuracy: 91.16%

**Self-use instructions**:
* preparing:
> Download [data_10.json](https://drive.google.com/file/d/1N7soIwQJ9eOEhBn5F3FjcFtajWT4yGfk/view?usp=sharing) file.

> Download [BestModel_weight_set.h5](https://drive.google.com/file/d/1-H3Vt_FVLbRV4HZzJ1QmUUZdV5lF8eta/view?usp=sharing) file.

>	Change in code 'DATA_PATH' to your desired file destination.

> Change in code 'model.save_weights' and 'model.load_weights' to desired destination.
* training
> Train the model or use directly trained model(in case of that, in 'Model preparation and training', run first 3 and last code sections only).

> Test, Visualize the Classification results, and use web app made by [Gradio](https://gradio.app/) library.

- there is no need to use 'preprocessing' section, otherwise:

* optional(by using preprocessing):
> download [GTZAN dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

> Change in code 'DATASET_PATH' to the destination of your dataset.

> Change 'DATA_PATH' to './data_10.json'

This project was made by Liav Avitan, April 2023.

Credit:
VRUSHALI. (2021).   [Music Genre Classification Using CNN](https://www.kaggle.com/code/vrushaliingle/music-genre-classification-using-cnn/notebook).


