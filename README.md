# handwritten signature
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

1. Download the dataset ([link](https://www.kaggle.com/divyanshrai/handwritten-signatures))\*
2. Run the script.py ([file](https://github.com/halhwadi/handwritten-signature/blob/main/Script.ipynb))

\* there are 2 or 3 subfolders which are not named properly, please make sure that all folders which contain the images are named:

&quot;real&quot; for Genuine signatures

&quot;forge&quot; for forged Genuine

<br>
<B>visualization:</B>

Label = 1 (Matching signatures)

Label = 0 (Nonmatching signatures)

![](RackMultipart20210524-4-1fc29x2_html_9c3a096a1fbf0b71.png)

<br>
<B>Model Structure:</B>

![](RackMultipart20210524-4-1fc29x2_html_5d3fa3f25d609c30.png)

<br>
<B>Training:</B>

![](RackMultipart20210524-4-1fc29x2_html_a061e56feab8b4d9.png)

![](RackMultipart20210524-4-1fc29x2_html_deb9a1210d4457b3.png)


<br>
<B>Prediction:</B>

<br>
<B>Matching:</B>

![](RackMultipart20210524-4-1fc29x2_html_9d9552707121fa3e.png)

<br>
<B>Nonmatching:<?B>

![](RackMultipart20210524-4-1fc29x2_html_cbc80e1abb8318d.png)
