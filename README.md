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

Transcription accuracy was calculated based on the following [formula](https://www.rev.ai/blog/how-to-calculate-word-error-rate/#:~:text=To%20correctly%20calculate%20WER%2C%20we,rate%20of%20about%2038%20percent.): # of mistakes/total wordcount. Bar graphs were plotted in Google Sheets for comparison of accuracy, magnitude, and polarity:



## [Architecture Overview](https://drive.google.com/file/d/1YouR2gEjl6tFX6OE_bcwD8CucspcET0f/view?usp=sharing)

![draw.io](https://github.com/vzchen/QTM250_HW4/blob/main/READ.ME%20Images/draw.io.JPG)

