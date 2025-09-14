# coursework
These codes described here can be used to design someone's profile. It contained a responsive design that someone can use to create the homepage HTML, sass/CSS. Index.html described the code to set up the homepage for HTML. Contact.html described the code to set up the contact information with flexbox design for HTML. Also, the skill.html code explained the code used to set up the skill or any publication. The main.scss used to design the whole background of the web, while \_mobile.scc code used for modern technology layouts such as laptops, smartphones, small laptops, and tablets.


## Personal Portfolio Website - Femi Adesola Oyinloye

### Overview

This is a personal portfolio website for **Femi Adesola Oyinloye**, showcasing professional experience, education, skills, projects, and contact information. The website is fully responsive and built using **HTML, CSS (Sass), and JavaScript**.

###  Features

- **Responsive Navigation Menu**  
  A collapsible menu for mobile and desktop screens with smooth toggle animation.

- **About Me Section**  
  Includes a detailed professional profile, work experience summary, and educational background.

- **Contact Section**  
  Contact information including email, phone, and address.

- **Home Page**  
  Welcome section with a marquee animation, large headings, and links to LinkedIn and GitHub profiles.

- **Projects and Skills Links**  
  Quick navigation to sections like Work Experience, Education, Skills, Publications, Cover Letter, Testimonials, and Software Projects.

- **Interactive Buttons and Hover Effects**  
  Smooth transitions using Sass mixins for hover effects and responsiveness.

###  Technologies Used

- **HTML5** – Structured semantic content for web pages.
- **CSS3 / Sass (SCSS)** – Styling with variables, mixins, and media queries.
- **JavaScript** – Toggleable navigation menu functionality.
- **Font Awesome** – Social media icons (LinkedIn, GitHub, Facebook).

###  File Structure

```
project/
│
├─ index.html          # Home page
├─ about.html          # About Me section
├─ contact.html        # Contact information
├─ school.html         # Education details
├─ work.html           # Work Experience
├─ skill.html          # Skills and Publications
├─ project.html        # Software projects
├─ testimonial.html    # Testimonials
│
├─ css/
│   └─ main.css        # Compiled CSS from SCSS
│
├─ scss/
│   ├─ _config.scss    # Variables, mixins, and media queries
│   ├─ _menu.scss      # Menu styles
│   ├─ _mobile.scss    # Mobile-specific styles
│   └─ main.scss       # Main SCSS entry file
│
├─ img/                # Images (profile, background, etc.)
├─ js/
│   └─ main.js         # Menu toggle functionality
└─ README.md
```

### Setup Instructions

1. **Clone the repository**
```bash
git clone <repository-url>
```

2. **Navigate to project directory**
```bash
cd project
```

3. **Install dependencies (if using Sass compilation with Node.js)**
```bash
npm install
```

4. **Compile SCSS to CSS**
```bash
npm run sass
```
or use Dart Sass directly:
```bash
sass --watch scss:css
```

5. **Open in Browser**
- Open `index.html` in your preferred browser to view the website.

###  Usage

- Navigate through pages using the top menu.  
- Click on social media icons to visit LinkedIn or GitHub profiles.  
- Hover effects and transitions are applied on buttons and interactive elements.

###  Contact

- **Email:** femioyin2003@yahoo.com, moysem11@gmail.com  
- **Phone:** +358442040418  
- **Address:** Kiltavelejenpolku 3 C23, 02770, Espoo, Finland  

### License

This project is for personal portfolio purposes. You can use it as a reference for front-end development projects.



npm uninstall node-sass
npm install sass --save-dev
"sass": "sass --watch scss:soft/css"