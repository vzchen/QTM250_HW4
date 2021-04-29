# QTM250_HW4

## Training Workflow

To test the [speech-to-text API](https://cloud.google.com/speech-to-text/docs/reference/rest), upload an audio file to Google Cloud Storage. Next, obtain the URI link for that audio file. The formatting of the link is as follows: gs://<bucket_name>/<file_path>. Paste this link into the Jupyter Notebook as shown:

![Speech-to-Text Training](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_1.JPG)

The results will give a verbatim transcript as well as a confidence estimate for the accuracy:

![Speech-to-Text Results](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_2.JPG)

To test the [natrual language API](https://cloud.google.com/natural-language/docs/apis), paste an excerpt of text into the Jupyter Notebook as shown:

![Sentiment Analysis Training](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_3.JPG)

The results will give a measurement of polarity (ranging from -1.0 to 1.0) and magnitude (ranging from 0 to inf):

![Sentiment Analysis Results](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_4.JPG)

## Analysis Workflow

## Architecture Overview

