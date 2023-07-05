**Proofreading Tool** 

The Proofreading Tool is a project that combines computer vision and natural language processing techniques to perform grammar error correction on scanned or digitally captured documents. It utilizes YOLO for text detection, Tesseract for optical character recognition (OCR), and a T5 model for the grammar error correction task.

Features
Text Detection: The YOLO (You Only Look Once) algorithm is employed to detect text regions in images or documents. It provides bounding box coordinates for each detected text region.

Optical Character Recognition (OCR): The detected text regions are then passed through Tesseract, a popular OCR engine. Tesseract converts the text regions into machine-readable text.

Grammar Error Correction: The OCR-generated text is processed using a T5 model, which is fine-tuned for the specific task of grammar error correction. The T5 model examines the text and suggests corrections for any detected grammar errors.

Installation
Clone the repository:


git clone https://github.com/eshangujar/proofreading-tool.git
Install the required dependencies:


pip install -r requirements.txt

The YOLO weights for text detection can be downloaded from darknet: https://pjreddie.com/darknet/yolo/.



Contributing
Contributions to the Proofreading Tool are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.




