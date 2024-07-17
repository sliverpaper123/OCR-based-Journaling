# OCR-based-Journaling
Developed a comprehensive system to automate the process of invoice journaling using advanced machine  learning techniques.

The OCR model was developed from scratch by using CNN for text detection and RCNN for text extraction, after which the trained model is then used by another model which uses Bi-lateral LSTM to categorize the data into the required columns and rows, then gets pushed to the database.
