# ECE1512_project

This project is a simple appraoch to generating latex markup from equations image of handwritten equations image provided in the dataset- CHORME compare to the current state of art seq2seq model. The approach is an OCR based image segmentation and then classifying segments of the image for characters. The approach works well only on basic equations. 
Since the handwritten dataset of equations image is not very big I have attempted to use transfer learning by using a trained CNN on the character dataset provided by Kaggle https://www.kaggle.com/xainano/handwrittenmathsymbols. For more details refer to the report report_ece1512.pdf.
