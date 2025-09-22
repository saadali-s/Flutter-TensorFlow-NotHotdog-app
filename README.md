What if i told u there is an app on the market...

Not Hotdog Detector

A mobile app that detects hotdogs in images using a deep learning model. Built with Flutter and TensorFlow for real-time, on-device detection.

How It Works

Fine-tuned YOLOv2 Tiny on the COCO dataset to detect only the hotdog class.

Any image not detected as a hotdog is automatically treated as “Not Hotdog.”

Converted the trained YOLO model to TensorFlow (.pb) format and applied quantization for faster mobile inference.

Features

Real-time hotdog detection on mobile devices.

Lightweight model (~11 MB) for efficient on-device performance.

Cross-platform support with Flutter and React Native.


# Not Hotdog PWA

Detect hotdog  with [Tiny YOLO v2](https://pjreddie.com/darknet/yolov2/) and [TensorFlow.js](https://js.tensorflow.org/).




## Dependencies

* [tfjs](https://github.com/tensorflow/tfjs)
* [tfjs-yolo](https://github.com/shaqian/tfjs-yolo)

