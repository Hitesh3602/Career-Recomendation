# Career-Recomendation

## Overview
This project is a web application that helps users navigate their career journey by providing a multiple-choice quiz. The quiz evaluates users' interests and preferences and recommends a suitable career path based on their answers. The application is built using HTML, CSS, and JavaScript.

## Features
- **Responsive Design:** The web application is designed to be mobile-friendly and responsive, ensuring a seamless user experience across different devices.
- **User-friendly Interface:** Easy-to-use quiz interface with clear questions and multiple-choice answers.
- **Career Recommendations:** Provides personalized career recommendations based on the user's answers to the quiz.
- **Session Storage:** Stores the career recommendation in the session storage, allowing users to view their results on a separate details page.
- **Navigation Bar:** Includes a navigation bar with links to Home, About, Services, and Contact Us pages.
- **Search Functionality:** A search input field in the navigation bar for easy navigation.

## Technologies Used
- **HTML5:** For structuring the content of the web application.
- **CSS3:** For styling the web application and ensuring a responsive design.
- **JavaScript:** For adding interactivity, handling form submissions, and storing/retrieving data from session storage.
- **Font Awesome:** For using icons in the web application.

## Project Structure
```
.
├── index.html         # Main HTML file containing the quiz and navigation bar
├── details.html       # HTML file for displaying detailed career recommendations
└── README.md          # This README file
```

## How to Use
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```
2. **Open `index.html` in a web browser:**
   ```bash
   open index.html
   ```
3. **Take the Quiz:**
   - Answer all the questions in the quiz by selecting the appropriate radio buttons.
   - Click the "Submit" button to see your career recommendation.
4. **View Detailed Recommendations:**
   - Click the "Know More" button to navigate to the details page for more information about your recommended career path.

## Customization
You can customize the quiz questions, answers, and career recommendations by modifying the `index.html` file. The `recommendCareer` function in the JavaScript code can be updated to include different criteria for career recommendations.

## Code Explanation
### HTML Structure
- The `index.html` file contains the main structure of the web application, including the navigation bar and the quiz form.
- The form consists of multiple questions, each with a set of radio buttons for the user to select their answers.

### CSS Styling
- The CSS styles are defined within the `<style>` tag in the `index.html` file. 
- The styles ensure the application is visually appealing and responsive.

### JavaScript Functionality
- The JavaScript code handles the form submission, evaluates the user's answers, and provides a career recommendation.
- The `recommendCareer` function calculates the user's most suitable career path based on their answers.
- The career recommendation is stored in `sessionStorage` and can be retrieved on the details page.




## Acknowledgements
- Icons by [Font Awesome](https://fontawesome.com/)
- Background color inspired by [Alice Blue](https://www.colorhexa.com/f0f8ff)


