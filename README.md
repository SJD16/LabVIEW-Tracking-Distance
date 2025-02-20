# LabVIEW-Tracking-Distance
Color-Based Object Tracking and Distance Measurement in LabVIEW

This program was developed to calculate the **distance between two objects** in each frame of a video. To achieve this, you must first provide **sample images** for object recognition using the **Vision Assistant**:  


## **Configuration Steps**
### 1️⃣ Set Up ROI (Region of Interest)

- If necessary, adjust the **ROI** in the **Vision Assistant**.
  ![imagen](https://github.com/user-attachments/assets/c7c8abb2-b407-4a8a-9995-a8f1c9c117fa)
### 2️⃣ Save Sample Images
- Ensure the samples are saved in some folder as shown:  
  ![crop](https://github.com/user-attachments/assets/a1ad9a7d-6df0-42af-b2c1-3fd7945a24bb)

### 3️⃣ Run the Program  
- The program will prompt you to **open a video** in **AVI format** or another **compatible format**.  
- **⚠️ Important:** The video **must have no sound**, as audio is not supported.

### 4️⃣ Program Output  
- If the program runs correctly, you will see:  
  - 📊 **A graph** displaying the distance measurement over time.  
    ![Image](https://github.com/user-attachments/assets/5fc139db-403e-4f29-a5df-ebe02b2373b5)
  - 🎥 **A filtered video** with multiple layers.  
    - You should see **only the color of the markers**.  
    - The **two tracked points** will be connected by a **line**.  
    ![Image](https://github.com/user-attachments/assets/56198dd3-d535-467c-b0ef-ee1b02b953b8)


---

## **🛠 Troubleshooting**
If the markers are not correctly detected, reconfigure the **Vision Assistant** and adjust the following parameters:  

- **🔹 Max of Matches**  
  - Set this value to **0** to ensure the program **tracks a point or marker**.  

- **🔹 Minimum Score**  
  - If set **too low**, the program may detect **too many false positives**, leading to incorrect tracking.  
  - If set **too high**, the program might **not recognize any markers**, resulting in **no measurements**.  











