##Text Classification using RoBERTa

This fine-tuned language model is designed specifically for the classification of doctors' prescriptions. It leverages two powerful transformer models for optimal accuracy. The majority of the classification tasks are handled using RoBERTa, which is well-suited for understanding context and language nuances across various prescription-related classes. However, for three specific classes, the model switches to RoBERTa with a zero-shot learning approach. This ensures that even without direct training data for these classes, the model can make accurate predictions based on semantic understanding.
The combination of RoBERTa's strong contextual capabilities and BERT's adaptability in zero-shot scenarios makes this LLM highly versatile for medical text classification.
