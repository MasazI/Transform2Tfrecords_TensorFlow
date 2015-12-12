# Transform2Tfrecords_TensorFlow

'tfrecords' is The recommended format for TensorFlow. You can get tfrecords form images and labels list using this tool.

## dependencies
- OpenCV
- TensorFlow
- PIL

## how to use

Usage: python tfrecords_util.py examples_list_file name output_directory resize resize_height resize_width

- examples_list_file

image1_path label
image2_path label
...


- name

prefix of tfrecords's file. When you set train, you'll get train.tfrecords.


- resize
If you want to resize images, Set True.


---

Copyright (c) 2015 Masahiro Imai
Released under the MIT license
