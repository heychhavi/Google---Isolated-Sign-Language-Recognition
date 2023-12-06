# Google---Isolated-Sign-Language-Recognition
The data is in the form of a parquet file, for example, Train_landmark_files/[participant_id] / [seqence_id].parquet. In the training data, we have the landmark data. The landmarks were extracted from raw videos with the MediaPipe holistic model. It is a given that not every frame included hands that the model could detect or that were visible.
frame - The frame number in the raw video.
row_id - A unique identifier for the row.
type - The type of landmark. One of ['face', 'left_hand', 'pose', 'right_hand'].
landmark_index - The landmark index number. Details of the hand landmark locations can be found here.
[x/y/z] - The normalized spatial coordinates of the landmark. These are the only columns that will be provided to your submitted model for inference. The MediaPipe model is not fully trained to predict depth so you may wish to ignore the z values.
train.csv
path - The path to the landmark file.
participant_id - A unique identifier for the data contributor.
sequence_id - A unique identifier for the landmark sequence.
sign - The label for the landmark sequence.
