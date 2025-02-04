
# **ASL_Teaching_Tool**  
A hand sign learning tool developed using computer vision and deep learning, later integrated into a web application using Flask.  

## **Data Collection**  
- Collected my own dataset for training.  
- Pre-processed images by resizing them to a constant **300x300 pixels** and applying white padding.  

## **Data Pre-Processing**  
- Applied **image color isolation** techniques to improve model generalization.  
- This preprocessing step helped with robustness but led to a slight accuracy trade-off.  

## **Model Implementation**  
- **Rescaled images** by normalizing pixel values (1/255).  
- Used **CNN** for feature extraction and **Fully Connected Layers** for classification.  
- Trained the model to recognize hand signs effectively.  

## **Website Integration (Flask-Based Web App)**  
### **1. Playground**  
- A space where users can freely test different hand signs and receive real-time feedback.  

### **2. Testing & Evaluation**  
- A **game-based evaluation system** where users sign each character to form a given word and earn points when the word is correctly spelled out.  

### **3. Learning Module**  
- Displays different hand signs on the left panel.  
- Users must mimic the shown sign correctly to proceed to the next sign.  
