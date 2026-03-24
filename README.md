This project automates attendance system using openCV LBPH (Local Binary Patterns Histogram) face recognizer and deploys it locally in streamlit.
Step 1 Data Collection and Training: I have organized images of students in this case 3 students. The images are labeled with unique identifiers.
Then OpenCV's Local Binary Pattern Histogram (LBPH) is trained using this dataset for face recogntion.
Step 2: Face Detection - The system employs Haar Cascade Classifier to detect faces via webcam or camera feed. Detected faaces are cropped and
preprocessed (e.g., grayscale conversion, resizing) to standardize input for recognizing.
Step 3: Face Recognition - The LBPH model processes the detected faces and compare them with the stored dataset. A confidence threshold is set as well.
Step 4 Attendance Marking - Upon successful recognition, the system records the individual attendance along withd data and timestamp
