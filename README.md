The dataset is divided into two parts: ASD and TD. 
Each subfolder contains time-labeled subfolders representing individual data. 
Within these, new_A1 corresponds to the blank paradigm, new_A2 represents the overlap paradigm, new_C indicates the person-gaze paradigm, and new_D denotes the exogenous-cueing paradigm. 
Each paradigm folder contains four CSV files: emotion_predictions for facial expression features, EyesRegionNum for gaze features, Headpose for head pose features, and keypoints for facial landmark features.


You can download the packaged code from the release section and reproduce our experimental results by executing the following command:
.\your path\codes\dist\infer.exe  .\your path\dataset
Here, "dataset" must be the dataset provided by us.
