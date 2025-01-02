# Face-Recognition
 Face Recognition System with Deep Learning  

This project demonstrates a **Face Recognition System** using a pre-trained FaceNet model. The system can perform:  
- **Face Verification**: Verifying if two images belong to the same person.  
- **Face Recognition**: Identifying a person from a database of authorized individuals.  

## Key Features  
- **Deep Learning Encoding**: Converts face images into a 128-dimensional encoding vector for comparison.  
- **Triplet Loss**: Ensures encodings of the same person are closer, while encodings of different individuals are farther apart.  
- **Real-Time Verification**: Checks identity based on pre-computed encodings in the database.  
