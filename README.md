Pedestrian prediction
1. Preparation
Set dataset attribute of the config files in configs/.
2. Training
Run train_social_model.py.
Python train_social_model.py --config path/to/comfig.json [--out_root OUT_ROOT]
3. Testing
Run evaluate_social_model.py
Python train_social_model.py --trained_model_config path/to/config.json --trained_model_file path/to/trained_model.h5

run python3.5 human_track_predict.py --input test.mp4
