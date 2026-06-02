🤖 AI-Powered Healthcare Chatbot

An intelligent healthcare assistant built using Machine Learning and Natural Language Processing (NLP) that helps users understand their symptoms through natural conversations. The chatbot analyzes user-reported symptoms, asks dynamic follow-up questions, predicts potential diseases, and provides precautionary measures and health recommendations.

Note: This project is designed for educational and research purposes only and is not intended to replace professional medical advice.

🚀 Features
🩺 Natural language symptom extraction
🔍 Symptom synonym recognition
✍️ Typo and spelling mistake handling using fuzzy matching
💬 Dynamic follow-up questioning for improved accuracy
🤖 Disease prediction using Machine Learning
📊 Confidence score generation for predictions
📖 Disease descriptions and explanations
⚠️ Personalized precautionary measures
😊 Human-like conversational experience
📚 Medical knowledge base integration
🛠️ Tech Stack
Programming Language
Python
Libraries & Frameworks
Scikit-learn
Pandas
NumPy
Regex
Difflib / Fuzzy Matching
Machine Learning
Random Forest Classifier
Data Source
CSV-based Medical Symptom and Disease Dataset
🏗️ System Architecture
User enters symptoms in natural language.
NLP module extracts symptoms from the input.
Fuzzy matching corrects spelling mistakes and identifies symptom variations.
The chatbot maps extracted symptoms to the medical dataset.
Dynamic follow-up questions are generated based on probable diseases.
User responses refine the symptom profile.
Random Forest Classifier predicts the most likely disease.
Confidence scores are calculated.
The chatbot returns:
Predicted disease
Confidence level
Disease description
Precautionary measures
Health recommendations
📋 Example Conversation

User: I have a headache and slight fever.

Chatbot: How long have you been experiencing these symptoms?

User: Since yesterday.

Chatbot: Are you also experiencing body pain or fatigue?

User: Yes, I feel tired.

Prediction:

Disease: Viral Fever
Confidence Score: 87%

Recommended Precautions:

Stay hydrated
Get adequate rest
Monitor body temperature
Consult a healthcare professional if symptoms worsen
🧠 Machine Learning Model

The chatbot uses a Random Forest Classifier trained on symptom-disease datasets.

Why Random Forest?
Handles multiple symptom features effectively
Provides robust predictions
Reduces overfitting
Generates prediction confidence scores
Performs well on structured medical datasets
