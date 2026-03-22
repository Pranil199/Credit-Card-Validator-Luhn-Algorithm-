# 💳 Credit Card Validator (Luhn Algorithm)

A simple, interactive Python script that validates credit card numbers using the industry-standard **Luhn Algorithm** (Modulus 10). 

Designed to be easily runnable in a local Python environment or directly within **Google Colab**.

## ✨ Features
* **Sanitizes Input:** Automatically removes spaces and dashes (e.g., `1234-5678` becomes `12345678`).
* **Format Checking:** Ensures the input contains only numeric digits before processing.
* **Luhn Validation:** Accurately performs the Modulus 10 checksum to verify the card's structural validity.
* **Interactive Prompt:** Provides a user-friendly terminal prompt for testing multiple numbers.

## 🚀 How to Run

### Option 1: Using Google Colab (Recommended for quick testing)
1. Go to [Google Colab](https://colab.research.google.com/) and create a **New Notebook**.
2. Copy the code from `validator.py` (or paste the script provided) into the first cell.
3. Run the cell by pressing **Shift + Enter**.
4. Enter a credit card number into the input box that appears below the cell.

### Option 2: Running Locally
1. Ensure you have Python 3.x installed on your machine.
2. Clone this repository or download the `validator.py` file.
3. Open your terminal or command prompt.
4. Navigate to the folder containing the script and run:
   ```bash
   python validator.py
