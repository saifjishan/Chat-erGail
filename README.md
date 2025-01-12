# Project Chet er Gail 🎉

A web application built with Vue.js that generates humorous Bengali phrases when you input a name. This project combines a modern user interface with a touch of cultural humor, making it a lighthearted tool for entertainment. 😂

## Features ✨

- **Instant Phrase Generation:** ✍️ Enter a name and see a funny Bengali phrase appear instantly.
- **Customizable Templates:** 🗂️ The application uses a variety of phrase templates to keep the generated content fresh and entertaining.
- **History Tracking:** 📜 Keeps track of the phrases you've generated.
- **Responsive Design:** 📱💻 Works seamlessly on various devices, providing a consistent user experience.
- **Custom Fonts:** ✒️ Features unique typography with Alfa Slab One for prominent text and Lato for general content.

## Tech Stack 💻

- [Vue.js 3](https://vuejs.org/): A progressive JavaScript framework for building user interfaces.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript): The primary programming language for web development.
- [JSON](https://www.json.org/): Used for storing and managing phrase templates and generated history.
- Custom CSS: Provides the unique styling and visual appeal of the application.

## Project Structure 📂

```
Project-ChetErGail/
├── data/
│   ├── templates.json        # 📝 Stores the phrase templates
│   └── generated-content.json # 💾 Stores the history of generated phrases
├── src/
│   ├── components/
│   │   └── NameGenerator.vue # 🖋️ The main component for name input and phrase generation
│   └── utils/
│       └── nameReplacer.js   # ⚙️ Contains the logic for generating phrases
├── public/
│   └── Logo-Symbol.png      # 🖼️ Application logo
└── README.md                # ℹ️ This README file
```

## Setup 🛠️

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saifjishan/Project-ChetErGail.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Project-ChetErGail
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

   This will start the development server, and you can view the application in your browser at the address provided in the console (usually `http://localhost:5173/`).

## Usage 🚀

1. Open the application in your web browser.
2. Enter a name in the input field.
3. Click the "Generate" button to see a humorous Bengali phrase.
4. The generated phrases will be stored in the history.

## Color Scheme 🎨

- **Base Color:** `#f05a94`
- **Button Color:** `#5c1b34`
- **Button Shade:** `#fff0b3`

## Fonts ✒️

- **Generate Button:** Alfa Slab One
- **Text Input & Content:** Lato

## Contributing 🙌

Contributions are welcome! If you have suggestions for new features or encounter any issues, please feel free to submit a pull request or open an issue.

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author ✍️

[Saif Jishan](https://github.com/saifjishan)
