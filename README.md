# 📰 NewsDigest

**NewsDigest** is a Streamlit application designed to transform your news bulletins into various writing styles using the power of OpenAI's language models. Whether you need a newspaper editorial, a creative piece, or a technical article, NewsDigest has got you covered!

## 🚀 Features

- **Multiple Writing Modes**: Choose from a variety of writing styles, including Newspaper Editorial, Creative, Informational, Poetry, Story, and more.
- **Contextual Input**: Provide up to three contexts with adjustable importance levels to guide the AI in crafting the content according to your specifications.
- **AI-Powered**: Leverages OpenAI's GPT-4 model to generate high-quality, stylistically accurate content based on your inputs.
- **Interactive Interface**: Simple and intuitive interface powered by Streamlit, allowing you to input your news bulletin and customize the output with ease.

## 🛠 How It Works

1. **Select a Writing Mode**: Choose the desired writing style from the dropdown menu.
2. **Enter Your News Bulletin**: Provide the text you want to transform.
3. **Provide Context**: Optionally, enter up to three contexts with their importance levels to tailor the output further.
4. **Generate the Content**: Click the "Create Conversation" button, and watch as your input is transformed into the chosen style!

## 📦 Installation

To run this app locally, follow these steps:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/likhitp/NewsDigest.git
    ```

2. **Navigate to the project directory**:

    ```bash
    cd newsdigest
    ```

3. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app**:

    ```bash
    streamlit run app.py
    ```

## 🎮 Usage

1. **Launch the Application**: Run the Streamlit app as described above.
2. **Select Your Mode**: Choose the writing style you want.
3. **Input Your Text**: Enter the news bulletin and any contextual information.
4. **Generate and Review**: Click the button to generate the content and review the AI-generated output.

## 🔧 Customization

- **Writing Modes**: You can easily add or modify the writing modes by editing the `modes` dictionary in the script.
- **API Key**: The application is set up to securely use the OpenAI API key, but ensure your key is securely stored using environment variables or Streamlit secrets.

## 🤝 Contributing

We welcome contributions! If you have suggestions for improvements or new features, please fork the repository and submit a pull request.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

**Developed with 💡 and ☕ by [Your Name]** 

**Explore the power of AI in news writing and beyond!**
