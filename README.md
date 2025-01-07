# Frequently Asked Questions (FAQ) Page

This project showcases a simple FAQ (Frequently Asked Questions) layout using HTML, CSS, and Font Awesome icons. The design is clean and responsive, offering a user-friendly interface for displaying questions and their corresponding answers.

## Features
- **Responsive Layout**: Designed to adapt to various screen sizes.
- **Clean Design**: Minimalistic and visually appealing.
- **Font Awesome Integration**: Includes plus-circle icons for each question.

## Technologies Used
- **HTML**: For the page structure.
- **CSS**: For styling and layout.
- **Font Awesome**: For the icons used in the FAQ.

## Project Structure
```plaintext
.
├── index.html  # Main HTML file
└── styles.css  # Inline CSS (can be extracted into a separate file if needed)
```

## Code Overview
### HTML
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frequently Asked Questions</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>
<body>
    <div class="con">
        <h1>Frequently Asked Questions</h1>
        <div class="qn">
            <p>Why is the moon sometimes out during the day?</p>
            <i class="fa-solid fa-circle-plus"></i>  
        </div>
        <div class="qn">
            <p>Why is the sky blue?</p>
            <i class="fa-solid fa-circle-plus"></i>  
        </div>
        <div class="qn">
            <p>Will we ever discover aliens?</p>
            <i class="fa-solid fa-circle-plus"></i>  
        </div>
        <div class="qn">
            <p>How much does the earth weigh?</p>
            <i class="fa-solid fa-circle-plus"></i>  
        </div>
        <div class="qn">
            <p>How do airplanes stay up?</p>
            <i class="fa-solid fa-circle-plus"></i>  
        </div>
    </div>
</body>
</html>
```

### CSS
```css
body {
    background-color: rgb(236, 235, 233);
}

.con {
    width: 80%;
    height: 400px;
    background-color: rgb(255, 255, 255);
    padding: 10px;
    margin: 150px auto;
    border-radius: 20px;
}

.qn {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 0px 20px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.171);
}

h1 {
    margin-left: 18px;
}
```

## How to Run the Project
1. Download or clone the repository.
2. Open the `index.html` file in your web browser.

## Preview

![Screenshot 2025-01-07 154611](https://github.com/user-attachments/assets/87f9c52b-4058-46e7-a9ee-6a482063ef39)

## Future Enhancements
- Add JavaScript functionality to toggle answers on clicking the plus icon.
- Include animations for better user experience.
- Enhance the design with additional styling elements.

## License
This project is open-source and available under the [MIT License](LICENSE).
