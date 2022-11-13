# American Sign Language Recognition with Machine Vision 

The goal of this research was to interpret the first four letters in the American Sign Language
fingerspelling alphabet using artificial intelligence and neural networks that can run efficiently on mobile
devices. 170 photos of the signs for A, B, C, and D were collected in various locations. The dataset was
augmented using filters to negate the importance of skin tone and lighting. A pre-trained Tensorflow
model (ssd_mobilenet_v2_fpnlite_320x320_coco17_tpu-8) was used to train a neural network that
identified signs from video in real-time with a mean average precision of 80%. A larger dataset would
improve precision and help the model generalize. This research has shown that given a sufficiently large
dataset, machine vision could be used to interpret static sign language gestures. 
