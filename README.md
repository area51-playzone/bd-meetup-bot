## Training and testing the NLU model

``python -m rasa_nlu.train -c config.yml --data data/nlu_data.md -o models --fixed_model_name nlu_model --project current --verbose``

## Training the dialogue management model

``python -m rasa_core.train -d domain.yml -s data/stories.md -o models/current/dialogue --epochs 200
``

## Testing the bot dialogue management system
````