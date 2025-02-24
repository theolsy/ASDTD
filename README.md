You can download the processed dataset named "dataset.zip"
The dataset is divided into two parts: ASD and TD. 
Each subfolder contains time-labeled subfolders representing individual data. 
Within these, new_A1 corresponds to the blank paradigm, new_A2 represents the overlap paradigm, new_C indicates the person-gaze paradigm, and new_D denotes the exogenous-cueing paradigm. 
Each paradigm folder contains four CSV files: "emotion_predictions.csv" for facial expression features, "EyesRegionNum.csv" for gaze features, "HeadposeNum.csv" for head pose features, and "keypoints.csv" for facial landmark features.


You can download the packaged code named "codes.zip" from the "Releases" section and reproduce our experimental results by executing the following command:
".\your path\codes\dist\infer.exe  .\your path\dataset"

Here, "dataset" must be the dataset provided by us.
