Deploying a Sentiment Analysis Model


```
				Project Folders Tree			
				

Project
|
|__serve
|  |
|  |__model.py                 (model_class)
|  |
|  |__predict.py               (model_fn, input_fn, output_fn, predict_fn)
|  |
|  |__requirements.txt         (libs)
|  | 
|  |__utils.py                 (refine_rev, tokenize_pad_rev)
|
|__train
|  |
|  |__model.py                 (model_class)
|  |
|  |__requirements.txt         (libs)
|  |
|  |__train.py                 (model_fn, data_loader, train_fn, main_fn[get_arg, 
|                              train_model, save_data])
|
|__website
|  |
|  |__index.html               (Web_App)
|
|__SageMaker Project.ipynb     (main file and guide)
|
|__Web App Diagram.svg         (pic used in main file)
|
|__README.md                   (guide to start)

```
