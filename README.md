# QTM250_HW4

## [Training Workflow](https://colab.research.google.com/drive/1biWF6uJCbi96N7AbqqyPpoyoCBUwICGZ#scrollTo=IOv47yiOn7m5)

To test the [speech-to-text API](https://cloud.google.com/speech-to-text/docs/reference/rest), upload an audio file to Google Cloud Storage. Next, obtain the URI link for that audio file. The formatting of the link is as follows: gs://<bucket_name>/<file_path>. Paste this link into the Jupyter Notebook as shown:

![Speech-to-Text Training](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_1.JPG)

The results will give a verbatim transcript as well as a confidence estimate for the accuracy:

![Speech-to-Text Results](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_2.JPG)

To test the [natural language API](https://cloud.google.com/natural-language/docs/apis), paste an excerpt of text into the Jupyter Notebook as shown:

![Sentiment Analysis Training](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_3.JPG)

The results will give a measurement of polarity (whether sentiment is + or -) and magnitude (strength of sentiment):

![Sentiment Analysis Results](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/capture_4.JPG)

## Analysis Workflow

## Architecture Overview

