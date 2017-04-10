Card Recognition using OpenCV3.2 and python3

Code from the blog post 
http://arnab.org/blog/so-i-suck-24-automating-card-games-using-opencv-and-python

Usage: 

  ./card_img.py filename num_cards training_image_filename training_labels_filename num_training_cards

Example:
  ./card_img.py test.jpg 4 train.png train.tsv 56
  
Note: The recognition method is not very robust; please see SIFT / SURF for a good algorithm.  