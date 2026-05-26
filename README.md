Encrypted Cloud Image Retrieval System

About the Project
Encrypted Cloud Image Retrieval System is a deep learning based project developed for secure image storage and retrieval in cloud environments. The main goal of this project is to protect image privacy while allowing users to retrieve similar images efficiently.

In this project, XOR encryption is used to secure images before storing them in the cloud. For image retrieval, the system uses Content-Based Image Retrieval (CBIR) along with the VGG16 deep learning model to extract image features and identify similar images accurately.

To improve performance, frequently accessed image data is stored in cache memory, which helps reduce retrieval time and provides faster responses.


 Features
- Secure image encryption using XOR technique
- Content-Based Image Retrieval (CBIR)
- Deep learning feature extraction using VGG16
- Similar image searching
- Fast retrieval using cache memory
- Secure cloud image storage
- User-friendly web interface



 Technologies Used
- Python
- Flask
- TensorFlow / Keras
- VGG16
- OpenCV
- NumPy
- HTML
- CSS
- JavaScript
- Bootstrap



 Dataset Categories
The dataset includes multiple image categories such as:
- Animals
- Flowers
- Foods
- Horses
- Monuments
- Mountains and Snow
- African Villages and People


 How the System Works
1. The user uploads an image.
2. The image is encrypted using XOR encryption.
3. VGG16 extracts important image features.
4. Feature vectors are stored for retrieval.
5. CBIR compares image features and finds similar images.
6. Cache memory improves retrieval speed for repeated searches.


 Run the Project

```bash
cd Encrypted-Cloud-Image-Retrieval-System
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

Run the Application

```bash
python app.py
```



 Applications

* Secure cloud image storage
* Medical image protection
* Military image security
* Privacy-focused cloud systems
* Digital image management



 Future Improvements

* Advanced encryption techniques
* Real-time cloud deployment
* Multi-user authentication
* Better deep learning models
* AI-based image recommendations
