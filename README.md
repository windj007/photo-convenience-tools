# photo-convenience-tools

Some tools to speed up photo sorting and editing.

I like digital photography. I use Canon 550D and make pictures in RAW mode, to process photos I use Darktable and Hugin.
Some time ago I realized that I more and more use my smartphone rather than my DSLR, mostly due to the fact that I need much time to process the photos sitting behind my laptop.
Despite smartphone has pretty good cam, it cannot compare even with 14bit RAW photos from DSLR, so I started to think, how can I speed up my photo pipeline.
To tackle with this, I decided to try to automate the process by applying my knowledge in machine learning.

This is very experimental.


# Idea

To implement a tool that consumes a folder with RAW photos and does the following things:
1. Predicts parameters of Darktable filters according to my style of photo editing and outputs them to Darktable .xmp files.
2. Detects panos and HDRs and processes them with Hugin and default parameters.

Having such a tool, only one manual pass is needed to fix some errors and fine-tune options.


# TODO

1. Write code to export RAW images to format suitable to serve as imput for ML.
2. Write code to export *.xmp files to format suitable to serve as target outcomes for ML.
3. Evaluate prediction quality.
4. Implement HDR and Pano detection.
5. Evaluation detection quality.
6. Wrap up everything to a tool.
7. ...
8. PROFIT!
