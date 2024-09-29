# Time Table Web Page

This project is a simple **Time Table** layout designed with **HTML** and **CSS**. The page consists of a weekly timetable schedule that displays subjects and their respective timings for Monday through Friday. It also includes decorative images to enhance the visual appeal of the page.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Installation and Usage](#installation-and-usage)
- [Customization](#customization)

## Project Overview

The project showcases a weekly timetable divided into sections for each weekday. The timetable includes the following features:

- **Day-wise time schedule**: Each day (Monday through Friday) has a box displaying 5–6 subject timings.
- **Subject timings**: The timetable displays the subject name followed by its scheduled time.
- **Visual Design**: The page is decorated with a background image and various images aligned around the timetable. The layout has been given a soft color theme for each day to create a distinct visual identity.

### Key Features:

- **Responsive layout**: The timetable layout is flexbox-based, ensuring responsiveness across different screen sizes.
- **Typography**: It uses Google Fonts for a modern and clean look.
- **Images**: Decorative images add personality to the design.

## Technologies Used

- **HTML5**: Structure of the web page.
- **CSS3**: Styling and layout of the page.
- **Google Fonts**: For typography (`Fredoka` and `Poppins`).
- **Images**: Various decorative images for enhancing the appearance.

## Folder Structure

The following folder structure is used for this project:

```
📁 Project Root
├── 📁 images
│   ├── love.png
│   ├── drink.png
│   ├── pink-cosmos.png
│   ├── office-desk.png
│   ├── iphone.png
│   ├── hanami.png
│   └── digital-nomad.png
├── index.html
└── style.css
```

- **index.html**: Contains the structure and content of the timetable.
- **style.css**: Contains the styling rules for the layout and appearance.
- **images/**: Folder contains the images used in the design.

## Installation and Usage

### Steps to run this project locally:

1. **Clone or download the project files.**
   You can clone this repository or download the files as a ZIP.

   ```bash
   git clone <repository-url>
   ```

2. **Open the project folder** in your preferred text editor (such as VS Code).

3. **View the page locally**:
   Open the `index.html` file in a web browser to view the timetable.

### Important:

- Ensure that all images in the `images` folder are properly linked and exist in your local folder for correct display.
- Make sure the `style.css` is properly linked in the `<head>` of the `index.html` file as it controls the page styling.

## Customization

### Customizing Subjects and Timings:

1. **Modify the subjects and timings** directly in the `index.html` file.
   For example, if you want to change the subject for Monday:

   ```html
   <p>&emsp;1. Software Eng.&emsp;&emsp;<u><i>11:00-11:50 AM</i></u></p>
   ```

2. **Change the design colors or layout** in the `style.css` file. Each day’s section is identified by classes (`Mon`, `Tue`, `Wed`, etc.). You can modify the colors by adjusting the `background-color` and `box-shadow` values in the CSS.

### Adding or Removing Days:

- To add a new day, duplicate the relevant `<div>` for any day (e.g., `Mon`, `Tue`), and update the class name and content accordingly.
- To remove a day, delete the corresponding `<div>` block.

---

This is a simple and aesthetic timetable design that can be easily modified for other purposes. Feel free to explore and customize the content and styling according to your needs!

