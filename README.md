# lipsync-wav2lip
Created a Lip Synced video with the help of the video and audio links provided.

# ALGORITHM:
The algorithm consists of the following steps:

Pretrained ESRGAN on the given video with the speech of the target person.
Applied the Wav2Lip model to the source video and target audio.
Upsampled the output of Wav2Lip with ESRGAN.
Used BiSeNet to change only relevant pixels in video.
