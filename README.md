# PronounceRight
# Mispronunciation Detection and Correction System

Mispronunciation detection and correction play a vital role in speech recognition systems, language learning platforms, and speech therapy tools. Accurate pronunciation is essential for effective communication, yet non-native speakers often struggle with phonemes absent in their native languages.  

This project introduces a framework for detecting and correcting mispronunciations in phonetic sequences, specifically tailored for an American English accent. The system utilizes **phonemic representations in the International Phonetic Alphabet (IPA)** and employs a two-step process:

1. **Detection**: A deep learning model, **Bidirectional Long Short-Term Memory (BiLSTM)**, identifies phoneme-level discrepancies within the input sequence.  
2. **Correction**: Once a mispronunciation is detected, an **Bidirectional Long Short-Term Memory (BiLSTM)** suggests the most likely corrected phoneme sequence.  

---

### **Key Features**
- **High Detection Accuracy**: The BiLSTM model achieves an impressive accuracy of **90.98%** in detecting mispronunciations.  
- **Efficient Correction**: The  BiLSTM model provides accurate phoneme corrections, with a success rate of **72%**.  
- **Visual and Audio Feedback**: The system delivers corrections through both visual and speech outputs, enabling users to learn new pronunciations more effectively.  

---

### **Applications**
- **Language Learning**: Enhances pronunciation training for non-native speakers.  
- **Speech Therapy**: Assists in identifying and correcting speech impairments.  
- **Speech Recognition Systems**: Improves accuracy by addressing mispronunciation issues.

---

### **Screenshots**
*(Below are the UI screenshots of the project, showcasing its intuitive and interactive design for pronunciation learning.)*

1. **Main Interface**
   
  ![Screenshot 2025-01-28 204423](https://github.com/user-attachments/assets/46b04c7b-e9a0-4962-87e2-79a10e8fbb75)

   when the word is pronounced right 
![Screenshot 2025-01-28 204622](https://github.com/user-attachments/assets/2da717be-fb95-40e3-a143-2f0ea05efc76)


   when the word is mispronounced
  ![Screenshot 2025-01-28 205758](https://github.com/user-attachments/assets/d3baf5f5-ec94-47dc-8b15-3ca6094ab466)


  



2. **Real-Time Feedback**
  * feedback when the word is pronounced right (Visual output)
    
  ![Screenshot 2025-01-28 204644](https://github.com/user-attachments/assets/f215d8c7-3e18-4e19-998e-4a88851b1860)


   feedback when the word is mispronounced
   
 ![Screenshot 2025-01-28 205412](https://github.com/user-attachments/assets/ca59a321-ea79-472d-9644-b2ffd666b940)




3. **Correction Suggestions**
   
    * speech output to listen to the correct pronunciation and download the same for future reference. 
   
   ![image](https://github.com/user-attachments/assets/84e7bf88-6f73-4d02-80ce-d78451cdc233)
   ![image](https://github.com/user-attachments/assets/b4f9f9f3-686b-4324-8c3c-6a2c12bc5e66)


   


---

### **How It Works**
1. **Input**: User uploads a audio file.  
2. **Detection**: The BiLSTM model identifies any discrepancies at the phoneme level.  
3. **Correction**: The system uses  BiLSTM model to propose accurate phoneme sequences.  
4. **Output**: Users receive corrections in both visual and speech formats.





