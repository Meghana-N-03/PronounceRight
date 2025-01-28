# PronounceRight
# Mispronunciation Detection and Correction System

Mispronunciation detection and correction play a vital role in speech recognition systems, language learning platforms, and speech therapy tools. Accurate pronunciation is essential for effective communication, yet non-native speakers often struggle with phonemes absent in their native languages.  

This project introduces a framework for detecting and correcting mispronunciations in phonetic sequences, specifically tailored for an American English accent. The system utilizes **phonemic representations in the International Phonetic Alphabet (IPA)** and employs a two-step process:

1. **Detection**: A deep learning model, **Bidirectional Long Short-Term Memory (BiLSTM)**, identifies phoneme-level discrepancies within the input sequence.  
2. **Correction**: Once a mispronunciation is detected, an **Edit Distance-based algorithm** suggests the most likely corrected phoneme sequence.  

---

### **Key Features**
- **High Detection Accuracy**: The BiLSTM model achieves an impressive accuracy of **90.98%** in detecting mispronunciations.  
- **Efficient Correction**: The Edit Distance correction algorithm provides accurate phoneme corrections, with a success rate of **86.9%**.  
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
   
   ![image](https://github.com/user-attachments/assets/1175d718-e914-4008-a8d2-1a2145d6ac09)
   when the word is pronounced right 
   ![image](https://github.com/user-attachments/assets/c613fb76-72f1-4b0c-8301-3767d2bc850f)

   when the word is mispronounced
   ![image](https://github.com/user-attachments/assets/c6e9dcdb-40fa-412f-9b23-3dec9a8e8004)

  



2. **Real-Time Feedback**
   feedback when the word is pronounced right 
   ![image](https://github.com/user-attachments/assets/07a8440a-8a61-434f-94b3-ab13a02daa76)

   feedback when the word is mispronounced
   ![image](https://github.com/user-attachments/assets/36d5322a-a618-4306-9b55-548e66136dcc)



3. **Correction Suggestions**
    speech output to listen correct pronunciation and download the same 
   
   ![image](https://github.com/user-attachments/assets/84e7bf88-6f73-4d02-80ce-d78451cdc233)
   ![image](https://github.com/user-attachments/assets/b4f9f9f3-686b-4324-8c3c-6a2c12bc5e66)


   


---

### **How It Works**
1. **Input**: Users provide a phoneme sequence (in IPA format).  
2. **Detection**: The BiLSTM model identifies any discrepancies at the phoneme level.  
3. **Correction**: The system uses Edit Distance algorithms to propose accurate phoneme sequences.  
4. **Output**: Users receive corrections in both visual and speech formats.





