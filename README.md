# 🍽️ Chef Claude - AI-Powered Recipe Generator

Chef Claude is a React app that helps you generate delicious recipes using AI! Simply enter your ingredients, and the app will fetch a recipe using the Hugging Face Mistral model. 🧑‍🍳✨

---

## 🚀 Features

### 📝 Add Ingredients
- Users can input ingredients into a form.
- Each ingredient is added to a list dynamically.
- Supports multiple ingredient entries.

### 🤖 AI-Generated Recipes
- Uses Hugging Face's **Mistral AI model** to generate recipes.
- Fetches recipe data in **Markdown format**.
- Displays the recipe with proper formatting.

### 🔄 Dynamic Updates
- Updates the ingredient list in real time.
- Generates a new recipe each time ingredients are changed.

---

## 🛠️ Technologies Used

### 📦 React
- **React Hooks** (`useState`) for managing state.
- **Component-based structure** for modularity.

### 📜 react-markdown
- Converts AI-generated Markdown recipes into properly formatted HTML.
- Ensures recipe readability with headings, lists, and bold text.

### 🤗 Hugging Face Inference
- Fetches AI-generated recipes using Hugging Face's API.
- **HfInference library** makes API calls seamless.

### 🧠 Hugging Face Mistral Model
- A powerful language model that understands ingredients and generates unique recipes.
- Takes user-inputted ingredients and returns structured recipe markdown.

---

## 🎯 How to Use

1. **Enter ingredients** one by one in the input field.
2. **Click the "Add Ingredient" button** to add them to the list.
3. **Generate a recipe** by clicking the provided button.
4. **View the AI-generated recipe** displayed on the screen.

---

## 📌 Future Enhancements

✅ Support for multiple cuisines 🍜
✅ Improved UI with images and styling 🎨
✅ Speech-to-text input for ingredients 🎙️
✅ Save recipes for future use 📂

---

## 🙌 Acknowledgements

This project was built as part of the **Scrimba** Frontend Developer Path. A huge thanks to Scrimba for providing an interactive and engaging learning experience! 🎓🚀

---

Happy Cooking! 🍳🔥

