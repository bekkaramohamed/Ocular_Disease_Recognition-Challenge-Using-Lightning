### Ocular Disease Recognition Challenge on Kaggle 

Ocular Disease Intelligent Recognition (ODIR) is a structured ophthalmic database of 5,000 patients with age, color fundus photographs from left and right eyes, and doctors' diagnostic keywords.

### Objectives 
Develop a multi-label classification model for eye disease recognition.

### Running the Notebook 🚀
To run this notebook:

1. **Create a Kaggle Account and Set Up Kaggle API** 
   - Register on Kaggle and download the Kaggle API token.
   - Load the Kaggle API token in the notebook to download the dataset.

2. **Mount Google Drive** 📂
   - Log in to Google Drive from the notebook to save files.
   - Ensure all outputs and checkpoints are saved securely.

3. **Training and Evaluation** 🧠
   - You can train the notebook to evaluate performance.
   - Alternatively, use the pre-trained `best-checkpoints.ckpt` file for inference.

### Results 🌟
The model was trained using a separate Python script with 30 epochs.
We achieved approximately 70% accuracy.
The model showed promising results but did not fully converge during training. 
Consider running the model for more epochs and using the Optuna framework to optimize hyperparameters for potentially better performance.

---

Feel free to explore and modify the notebook to enhance the model's performance and explore new possibilities in ophthalmic disease recognition! 👁️
