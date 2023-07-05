# OMAPS2

We expand the [OMAPS Dataset](https://github.com/itec-hust/OMAPS) and construct a new one called OMAPS2 with a total duration of 421 minutes and 206 records. We used a Logitech C922 PRO camera which contains two microphones to record the additional 100 videos. The camera was directly above the piano keyboard, ensuring the entire piano keyboard area is recorded. The resolution of the image camera is 1920 × 1080, the frame rate is 30, and the audio sampling rate is 48kHz. Three piano amateurs played on Yamaha electronic piano to generate audio and MIDI files. And then, we manually aligned the MIDI files with the corresponding video frames to obtain accurate annotation. In the OMAPS2 dataset, 146 songs are used as the training set, 20 songs are used as the validation set, and 40 songs are used as the test set.

| Split | Performace | Duration,minutes | Size, GB | Notes  |
| ----- | ---------- | ---------------- | -------- | ------ |
| Train | 146        | 284              | 4.79      | 106243 |
| Valid | 20         | 44               | 0.75     | 16449  |
| Test  | 40         | 75               | 1.28      | 27371  |
| Total | 206        | 403              | 6.82      | 150063 |

Because the dataset is too large, we store the data in BaiduYun Disk oneline. (link：https://pan.baidu.com/s/1C8N18rKzUlGpqU7zhdJQng code: itec) 
<img src="record.png" alt="record" style="zoom:24%;" />

## Some details about the dataset we shared in BaiduYun Disk:
1. The 'train', 'valid', and 'test' folders contain 'video' and 'wav' folders, which consist of audio and video information respectively.
2.  The json files named "Aligned audio" and "aligned video" respectively refer to the labels that are aligned with the audio information and video information.
