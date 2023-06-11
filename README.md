# YoutubePD_Audio
Repository for extracting audio and running baseline model for YoutubePD

## Extracting audio representations:
1) Run extract_video to download relevant video files
2) Run extract_audio to separate out audio from videos
3) Run clean_audio to generate cleaned subsets of the noisier audios - replace the original audios with cleaned audios based on testing. 
4) Install https://github.com/nttcslab/msm-mae (or any other audio feature extraction script)
5) Run MAE_Encoder to generate video-level representations of the audio

## Running baseline models:
1) Simply run through Baseline_Model/mae_mc.ipynb to generate baseline results
