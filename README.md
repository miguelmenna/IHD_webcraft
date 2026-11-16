# 💧 Drinking Water Quality Checker

An educational and interactive website designed to provide accessible information about drinking water quality, pH levels, and water testing methods.

The project aims to make basic information about water quality easier to understand through a simple interface, educational content, visual resources, and an interactive pH checker.

## 📌 Project Overview

Access to information about drinking water quality is essential for public awareness and health education.

This project was developed to provide users with an accessible way to learn about drinking water, understand the importance of pH levels, and explore different methods of measuring water acidity and alkalinity.

The website combines educational content with interactive features, allowing users to enter a pH value and receive immediate feedback based on the implemented validation rules.

## 🎯 Project Objectives

The main objectives of this project are:

- Provide accessible educational information about drinking water.
- Explain the importance of pH measurements.
- Introduce different methods of testing water pH.
- Offer an interactive tool for checking entered pH values.
- Provide a simple navigation structure for different sections.
- Encourage awareness of water quality and testing methods.

## ✨ Main Features

### 1. Educational Content

The website introduces the concept of drinking water and explains why water quality is important for public health.

It also provides information about the role of pH in water quality, including its relationship with acidity, alkalinity, and water treatment processes.

### 2. Water pH Checker

The interactive pH checker allows users to enter a numerical pH value between 0 and 14.

The JavaScript implementation processes the submitted value and displays feedback according to the validation rules.

The interface includes:

- Numerical pH input.
- Input validation.
- Visual feedback through CSS classes.
- Success and error messages.
- Form reset functionality.

**Important:** The pH checker is an educational demonstration. It does not perform laboratory analysis or determine whether water is safe to drink.

### 3. Water Testing Methods

The website introduces two common methods of measuring water pH:

- Chemical pH indicators, such as test strips.
- Electronic pH meters.

Images are used to help users identify these testing devices and understand their basic purpose.

The website also provides general information about their costs.

### 4. Educational Video

An embedded YouTube video provides additional educational material related to water pH testing.

This feature allows users to access external visual explanations directly from the website.

### 5. Contact Form

The contact section includes a form where users can enter:

- Name.
- Email address.
- Message.

The interface includes required fields and JavaScript-based feedback to simulate a successful submission.

**Current limitation:** The contact form does not connect to a backend, email service, or database. It currently demonstrates the front-end interaction only.

### 6. Simple Navigation

The navigation menu provides direct access to the main website sections:

- About.
- Water Analysis.
- Contact.

Internal anchor links allow users to move between sections without navigating to separate pages.

## 🛠️ Technologies Used

| Technology | Application |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layout, colors, and visual presentation |
| JavaScript | Form validation and interactive behavior |
| YouTube Embed | Integration of educational video content |

### HTML5

HTML is responsible for the website structure, including:

- Semantic elements such as `header`, `nav`, `main`, and `section`.
- Navigation links.
- Forms and input fields.
- Images and alternative text.
- Embedded video content.

### CSS3

CSS is used to define the website's visual identity and presentation.

Some implemented features include:

- CSS custom properties (variables).
- Color palette management.
- Background images.
- Transparent backgrounds.
- Form styling.
- Button hover and focus effects.
- Error and success message styling.
- Responsive image sizing.

### JavaScript

JavaScript provides the interactive functionality of the website.

The implemented features include:

- DOM manipulation.
- Event listeners.
- Form submission handling.
- Input validation.
- Dynamic feedback messages.
- Temporary visual status indicators.
- Form reset handling.

## 🎨 Design and User Experience

The website uses a visual design centered around water-related colors and imagery.

Its styling includes:

- Blue as the primary color.
- White text and content elements.
- Gold-colored highlights and interactive buttons.
- A background image related to the project's theme.
- Centered content sections.
- Rounded containers and form elements.

The navigation and content organization aim to make the website straightforward to explore.

The project also incorporates basic accessibility practices, including:

- Labels associated with form fields.
- Alternative text for images.
- ARIA attributes for selected form elements.
- Visible keyboard focus indicators.
- Semantic HTML elements.

These features provide a foundation for accessibility, although further testing and improvements would be necessary to ensure broader accessibility compliance.

## 📂 Project Structure

```text
drinking-water-quality-checker/
│
├── index.html
├── style.css
├── script.js
│
├── agback.jpg
├── oque-e-agua-potavel.jpg
├── testeq.webp
├── testeE.webp
│
└── README.md
```

*Note: The structure above is a suggested organization. The JavaScript code should be moved into `script.js` if it is not already stored in a separate file.*

## ▶️ How to Run the Project

No complex installation or additional dependencies are required.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/drinking-water-quality-checker.git
```

### 2. Navigate to the project directory

```bash
cd drinking-water-quality-checker
```

### 3. Open the website

Open the `index.html` file in your preferred web browser.

Alternatively, use Visual Studio Code with the Live Server extension to run the project locally.

## ⚠️ Important Notes and Limitations

This project is an educational front-end application and should not be considered a professional water quality testing system.

Some important limitations include:

- The pH checker only evaluates the numerical value entered by the user.
- A pH measurement alone cannot determine whether water is safe for human consumption.
- The current implementation does not perform laboratory testing.
- The contact form does not send messages to an actual email address or backend.
- The website does not store user information or analysis results.
- The pH validation logic should be consolidated into a single implementation to avoid conflicting results.

The pH range used by the checker should also be aligned with the applicable drinking water standards before the tool is used for educational guidance.

## 🚀 Future Improvements

Possible improvements for future versions include:

- Implementing a more comprehensive and consistent pH validation system.
- Adding explanations for different pH ranges.
- Improving mobile responsiveness.
- Connecting the contact form to a backend or email service.
- Adding more educational content about drinking water treatment.
- Improving keyboard navigation and screen reader support.
- Adding automated tests for form validation.
- Providing multilingual support.
- Improving the visual presentation of pH results.

## 📚 Learning Objectives

This project provided practical experience with:

- Front-end web development.
- HTML semantic structure.
- CSS styling and custom properties.
- JavaScript event handling.
- DOM manipulation.
- Form validation.
- User interface design.
- Basic web accessibility practices.
- Embedding external multimedia content.

## 📝 Conclusion

Drinking Water Quality Checker is an educational web development project focused on making information about drinking water and pH measurements more accessible.

By combining educational content, interactive forms, visual resources, and a straightforward navigation structure, the project demonstrates the practical application of front-end development technologies to an everyday topic.

---

**Project Type:** Educational Website  
**Category:** Front-End Development  
**Technologies:** HTML5, CSS3, JavaScript
