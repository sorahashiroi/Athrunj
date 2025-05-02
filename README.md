# 🔖Athrunj
Refrigerator & Receipt-Based Meal Recommendation App

# 💡Description
This project is an application that suggests optimal meal plans based on the ingredients in your fridge or the items purchased (from receipts). Users can upload receipts or input the ingredients available to them, and the app will suggest easy-to-make recipes.

## 🪔Features

- **Receipt OCR Parsing**: Extract ingredients and prices from uploaded receipt images.
- **Ingredient Management**: Users can register ingredients in their fridge, manage stock, and track expiration dates.
- **Meal Recommendation**: Suggest Japanese recipes based on available ingredients.
- **Healthy Suggestions**: Propose balanced and healthy meal options considering nutritional values.

## ⚒Technologies Used

- **OCR Engine**: Tesseract
- **Recipe Recommendation System**: Custom-built (based on ingredient lists)
- **Framework**: Streamlit (for Web App)
- **Languages**: Python 3.x
- **Libraries**:
  - `Pandas`: For data processing
  - `Tesseract`: For OCR (receipt parsing)
  - `scikit-learn`: For recommendation algorithms
  - `Streamlit`: For UI development
