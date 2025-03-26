# Glossy_llm
🚀 Fine-Tuning Phi-2 with 4-bit DoRA PEFT
📌 Overview
This project fine-tunes Microsoft Phi-2 using 4-bit LoRA and DoRA (Decoupled LoRA) for efficient training on low-cost hardware. The goal is to optimize text-to-gloss generation while reducing memory usage.

⚙️ Dependencies
Ensure the following packages are installed:

Python 3.8+

PyTorch (with CUDA support for GPU)

Hugging Face Libraries: transformers, datasets

Quantization & PEFT: bitsandbytes, peft, dora

Other Utilities: scikit-learn, pandas, numpy

📂 Dataset
The dataset consists of text-gloss pairs in CSV format. Ensure data is preprocessed and tokenized before training.

🚀 Training Process
Load Phi-2 with 4-bit LoRA & DoRA

Tokenize and split the dataset

Configure training parameters

Train using Hugging Face Trainer with early stopping

💾 Model Usage
After training, the model can be saved locally or pushed to Hugging Face Hub for deployment.

📜 License
This project is licensed under the MIT License.

📬 Contact
For inquiries, reach out via GitHub or Email.
