# 🧾 Azure Document Intelligence - DMart Bill Extraction
![exp](https://github.com/user-attachments/assets/3eac9761-9591-4ffa-9c41-904e62935825)


This project demonstrates how to use **Azure Document Intelligence (Form Recognizer)** to extract structured data from a **DMart bill** PDF/image, turning unstructured receipts into actionable digital data.

## 📌 Features

* 🧠 Uses Azure AI Document Intelligence to analyze printed/handwritten content
* 📤 Uploads DMart bill as an image or PDF
* 🗂️ Extracts structured fields: GSTIN, FSSAI No, Vendor Name, Address
* 📍 Tracks bounding boxes and confidence levels
* 🔧 Outputs clean, formatted text and metadata

---

## 🖼️ Sample Output

```
Line # 3 has word count 3 and text 'AVENUE SUPERMARTS LTD'
...Confidence: 0.992

Line # 5 has word count 3 and text 'GSTIN : 24AACCA8423H1ZW'
...Confidence: 0.987

Line # 6 has word count 2 and text 'FSSAI NO. 10715026000439'
...Confidence: 0.976

Line # 8 has word count 4 and text 'City Gold Multiplex Compound'
...Confidence: 0.992
```

---

## 🧰 Tech Stack

| Tool                        | Use                       |
| --------------------------- | ------------------------- |
| Azure Document Intelligence | OCR and layout extraction |
| Python (SDK)                | API calls + data parsing  |
| Google Colab                | Development & demo        |
| JSON                        | Structured API responses  |

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/azure-dmart-bill-extraction.git
cd azure-dmart-bill-extraction
```

### 2. Install Requirements

```bash
pip install azure-ai-formrecognizer
```

### 3. Add Azure Credentials

Create a `.env` file:

```env
AZURE_FORM_RECOGNIZER_ENDPOINT=https://<your-endpoint>.cognitiveservices.azure.com/
AZURE_FORM_RECOGNIZER_KEY=<your-key>
```

### 4. Run the Script

```bash
python extract_dmart_bill.py
```

---

## 📚 Use Case: Automating Retail Bill Processing

| Step                     |                           
| ------------------------ |  
| Create a Document intelligence| 
| Upload Dmart Bills and make it as url|
| Using python code for bill anaylsis|       

---

## 📁 File Structure

```
├── sample_dmart_bill.pdf
├── extract_dmart_bill.py
├── .env
├── README.md
```

---

## 🧠 What is Azure Document Intelligence?

Azure Document Intelligence (Form Recognizer) is an AI-powered service that uses pre-trained models to extract text, key-value pairs, and tables from documents with high accuracy.

🔗 [Learn more](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview)

---

## 📸 Screenshots

<img width="748" alt="Screenshot 2025-05-03 at 17 36 27" src="https://github.com/user-attachments/assets/96b2698d-4852-4935-8850-07f6894a53f5" />
<img width="1114" alt="Screenshot 2025-05-03 at 17 35 25" src="https://github.com/user-attachments/assets/396d61e1-d760-40df-bd97-cb6bc2a7b0be" />
<img width="1440" alt="Screenshot 2025-05-03 at 17 35 19" src="https://github.com/user-attachments/assets/5732710f-a56f-4f4b-a0eb-090b2c42a864" />
<img width="686" alt="Screenshot 2025-05-03 at 17 35 15" src="https://github.com/user-attachments/assets/c58f45ab-229c-44c7-bcf3-07e30704cd9f" />
![WhatsApp Image 2025-05-03 at 9 16 12 PM](https://github.com/user-attachments/assets/fe1b6cf4-0450-4f8e-bf62-b75b86db8434)

---

## 🤝 Contributing

Pull requests welcome! If you find a bug or want to add features, feel free to contribute.


---

## 🔗 Connect with Me

* LinkedIn: [Your Name](https://www.linkedin.com/in/ambatibhargavi/)
* YouTube: [Your Channel](https://www.youtube.com/@Bharudev)

---

> Made with ❤️ for automating retail document processing
