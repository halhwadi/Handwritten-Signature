# Handwritten Signature
 Detect the Genuine and Forged signatuers



<b>Content</b>

This Dataset contains Genuine and Forged signatures of 30 people. Each person has 5 Genuine signatures which they made themselves and 5 Forged signatures someone else made.
 The naming of images is explained here.
 NFI-00602023 is an image of signature of person number 023 done by person 006. This is a forged signature. NFI-02103021 is an image of signature of person number 021 done by person 021. This is a genuine signature.


<b>Source:</b>

Kaggle ([link](https://www.kaggle.com/divyanshrai/handwritten-signatures))

<br>

<b>Dataset Structure:</B>

  <b>Training Dataset folder:</B>

  Dataset\_Signature\_Final\Dataset

  <b>Validation and Testing Dataset folder:</B>

  sample\_Signature\sample\_Signature

<br>

<b>Usage:</B>

1. Download the dataset ([link](https://www.kaggle.com/divyanshrai/handwritten-signatures))\**
2. Run the script.py ([file](https://github.com/halhwadi/handwritten-signature/blob/main/Script.ipynb))

   \**There are 2 or 3 subfolders which are not named properly, please make sure that all folders which contain the images are named:

     &quot;real&quot; for Genuine signatures

     &quot;forge&quot; for forged Genuine

<br>
<B>visualization:</B>

Label = 1 (Matching signatures)

Label = 0 (Mismatching signatures)

![](https://github.com/halhwadi/handwritten-signature/blob/main/Visulization.jpg)

<br>
<B>Model Structure:</B>

![](https://github.com/halhwadi/handwritten-signature/blob/main/Model_structure.jpg)

<br>
<B>Training:</B>

![](https://github.com/halhwadi/handwritten-signature/blob/main/training.jpg)

![](https://github.com/halhwadi/handwritten-signature/blob/main/tensorboard.jpg)


<br>
<B>Prediction:</B>

<br>
<B>Matching:</B>

![](https://github.com/halhwadi/handwritten-signature/blob/main/prediction_matching.jpg)

<br>
<B>Nonmatching:<?B>

![](https://github.com/halhwadi/handwritten-signature/blob/main/prediction_nonmatching.jpg)
