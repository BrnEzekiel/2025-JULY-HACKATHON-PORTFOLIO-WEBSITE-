Brian's Portfolio
This repository contains the source code for Brian's personal portfolio website, a responsive and modern web presence built with HTML, Tailwind CSS, and vanilla JavaScript. The portfolio showcases Brian's skills, projects, and provides an easy way to get in touch.

Features
Responsive Design: Optimized for various screen sizes, from mobile devices to desktops.

Dark Mode Toggle: Users can switch between light and dark themes based on their preference, with the setting saved locally.

Clear Navigation: Smooth scrolling to different sections of the page (Home, About Me, Projects, Contact).

Project Showcase: Dedicated section to highlight key projects with descriptions and links.

Skills Section: A comprehensive list of technical skills.

Contact Form: A simple form for visitors to send messages.

Resume Download: Direct link to download Brian's resume.

Social Media Integration: Links to Brian's social media profiles.

Technologies Used
HTML5: Structure and content of the web page.

Tailwind CSS: A utility-first CSS framework for rapid and consistent styling.

JavaScript: For interactive elements, specifically the dark mode toggle functionality.

Font Awesome: Icon library used for social media icons and the theme toggle icon.

Setup and Installation
To get a local copy up and running, follow these simple steps:

Clone the repository:

Bash

git clone https://github.com/brnezekiel/brians-portfolio.git
Navigate to the project directory:

Bash

cd brians-portfolio
Open index.html:
Simply open the index.html file in your preferred web browser. Since this is a static site, no build step or local server is required.

Project Structure
brians-portfolio/
├── index.html          // Main portfolio page
├── pic.png             // Profile picture
└── CV.pdf              // Resume file
Customization
You can easily customize this portfolio to make it your own:

Content:

Open index.html and modify the text in the "Hero", "About Me", "Projects", and "Contact" sections to reflect your own information.

Update the src attribute of the <img> tag in the Hero section to your profile picture (e.g., pic.png).

Change the href attribute of the "Download Resume" link to point to your CV.pdf or equivalent file.

Projects:

In the "Projects" section, duplicate or remove project cards (div with class bg-gray-50 rounded-lg...) as needed.

Update img src, alt text, project titles, descriptions, and the "View Project" links (<a> tags).

Social Media Links:

In the <footer> section, update the href attributes of the social media <a> tags to your respective profiles.

Styling:

Tailwind CSS: Most styling is done directly in the HTML using Tailwind CSS classes. You can modify these classes to change colors, fonts, spacing, and more.

Colors: The primary blue color (blue-600, blue-700, blue-800, etc.) is used throughout. You can search and replace these classes with your preferred color palette from Tailwind CSS.

Fonts: The Inter font is imported. You can change this by modifying the @import url in the <style> block within the <head> section and updating the font-inter class on the <body> tag.

Contributing
While this is a personal portfolio, suggestions for improvements are welcome. Please open an issue if you have any ideas or spot any bugs.

License
This project is open source and available under the MIT License.

Contact
Feel free to reach out to Brian through the contact form on the website or via his social media channels linked in the footer.
