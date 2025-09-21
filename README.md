# DigiBuddy - Chatbot Prototype  

## Overview  
DigiBuddy is a **multilingual chatbot prototype** developed for the *Digital Literacy Program* website.  
It is designed to provide a **friendly, accessible, and engaging** experience for users through both **text** and **voice** interactions.  

The chatbot supports **three languages**: English, Hindi, and Hinglish (a blend of English and Hindi).  

Its primary focus is **usability, accessibility, and lightweight design**, making it adaptable for a broad range of users.  

---

## Key Features  

1. **Multilingual Support**  
   - Supports **English, Hindi, and Hinglish**  
   - Users can ask questions in these languages, and the chatbot provides relevant answers  

2. **Speech Recognition**  
   - Users can ask queries by speaking into their device  
   - Speech is transcribed into text using **Google’s Speech Recognition API**  

3. **Text-to-Speech Functionality**  
   - Chatbot responses are also read aloud via **Text-to-Speech (TTS)**  
   - Provides accessibility for users who prefer audio feedback  

4. **Custom-Built**  
   - Developed entirely with **HTML, CSS, and JavaScript**  
   - No third-party paid services or APIs (e.g., OpenAI) were used  
   - Core functionality relies on **Google Speech Recognition** and **Text-to-Speech APIs**  

5. **User-Friendly Interface**  
   - Simple, intuitive UI with buttons for **sending messages** and **activating speech input**  
   - Users can toggle easily between supported languages  

6. **Voice and Text Interaction**  
   - Queries can be entered either through **text input** or **voice input**  
   - Responses are delivered as **text** and **speech** outputs  

---

## Technologies Used  

| Technology                     | Purpose                                                                                          |
|--------------------------------|--------------------------------------------------------------------------------------------------|
| **HTML/CSS/JavaScript**        | Core structure, styling, and dynamic interactions of the chatbot                                  |
| **Google Speech Recognition**   | Transcribes spoken input into text using the Web Speech API                                       |
| **Google Text-to-Speech (TTS)** | Converts chatbot text responses into audio using SpeechSynthesis API                              |

**References**  
- [Google Speech Recognition Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API/Using_the_Web_Speech_API)  
- [Google Text-to-Speech Documentation](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis)   

---

## Features Summary  

1. **Multilingual Support**  
   - English, Hindi, and Hinglish support  
   - Provides relevant responses in the chosen language  

2. **Interactive Interface**  
   - **Speech-to-Text:** Microphone button allows spoken queries, transcribed into text  
   - **Text Chat:** Users can type their queries in the input field  
   - **Audio Responses:** Outputs spoken answers for improved accessibility  

3. **Custom Development**  
   - Developed entirely using **vanilla JavaScript, HTML, and CSS**  
   - No external AI models or subscriptions (e.g., OpenAI) were used  

---

## Limitations  

1. **Limited AI Capability**  
   - No natural language processing or advanced AI  
   - Relies on **predefined FAQs and keywords**  

2. **Speech Recognition Accuracy**  
   - Quality depends on Google Speech Recognition  
   - May misinterpret speech in noisy environments or with complex queries  

3. **Language Handling**  
   - Optimized for **English and Hindi (Devanagari script)**  
   - **Romanized Hindi** (e.g., *“kya hai browser”*) is **not supported**  
   - Correct input should be **“क्या है ब्राउज़र”** in Devanagari script  

4. **Limited Response Flexibility**  
   - Cannot manage unexpected or complex queries  
   - Restricted to programmed knowledge base  

## Demo Video

🎥 **Demo Video**: A full walkthrough video of the DigiBuddy chatbot is available below:  
[![Watch the Video](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)]([https://your-video-link.com](https://drive.google.com/file/d/1zXXZwTJ94vIPwcycJYlfME0leAiAfWl5/view?usp=sharing))  


📸 **Screenshots**:  
- Screenshot 1: Chat interface in English
  <img width="1919" height="776" alt="Image" src="https://github.com/user-attachments/assets/a18ad4a5-9eca-4434-99d4-09d0380669cd" />
- Screenshot 2: Chat interface in Hindi
  <img width="1262" height="389" alt="Image" src="https://github.com/user-attachments/assets/fb55d107-76b1-42e3-b105-6cf226584026" />
   
## Conclusion  
The **DigiBuddy chatbot prototype** is a lightweight, cost-effective, and accessible solution for answering basic queries.  

Its **speech-to-text** and **text-to-speech** features enhance accessibility and user engagement, while its **simple architecture** ensures ease of deployment without reliance on external AI services.  
