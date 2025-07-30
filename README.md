# Static-Website-Project    
                                                     Wildlife Photography Website – UI Documentation

Project Overview
•	Project Title: Wildlife Photography
•	Template Used: TemplateMo #502 – Short Template
•	Website Structure: Single-page application with vertical tab navigation
•	Design Goal: To promote wildlife photography and showcase a gallery of wildlife images, while inviting users to engage via a contact form.

Main Navigation Structure
The site is structured using vertical tabs powered by the Easy Responsive Tabs jQuery plugin. Each section is accessible via a unique URL fragment identifier (anchor hash).
Section	Fragment ID	Description
Welcome Intro	#profile	Hero section introducing the theme and message of the site.
About Us	#resume	Background information on wildlife photography.
Our Projects	#portfolio	A gallery-style carousel of wildlife photography projects.
Contact Us	#contact	Contact form and personal note encouraging course participation.

Section Breakdown
1. Welcome Intro (#profile)
Content:
•	Main heading: Wildlife Photography – A Journey Into the Heart of the Wild
•	Inspirational Quote:
“It’s not about hunting with a gun, it’s about shooting with a lens — capturing, not killing.”
•	Call to Action: "Discover More" button (currently a placeholder).
•	Image: Right-aligned image representing wildlife (image path is local and must be replaced).
Layout: Two columns – text left, image right (Bootstrap col-md-6 layout).

<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/fc69ce4e-8921-49f1-9950-b543a79d0b98" />

 


2. About Us (#resume)
Content:
•	Title: More Info About Photography
•	Paragraph:
Wildlife photography is a specialized genre that involves capturing animals in their natural surroundings without disturbing them. It demands not just a good eye for composition but also an understanding of animal behavior and movement. This field blends art, patience, and adventure, often taking photographers into remote or challenging environments.
•	Supporting image displayed below the paragraph (path is currently local).
Styling:
•	Center-aligned with a decorative underline (.under-line class).
•	Text uses soft typography and light spacing.
 
<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/cc62be51-dcf9-46a1-b9f7-e64741230549" />


3. Our Projects (#portfolio)
Component: Owl Carousel (horizontal slider)
Functionality:
•	Each item includes:
o	Wildlife Image
o	Title (e.g., Tiger, Owl, Peacock)
o	Hover overlay with title and a zoom icon (opens in lightbox)
Examples of Project Items:
•	Hawk Eagle
•	Lemur Catta
•	Parrot
•	Peacock
•	Giraffe
•	Owl
•	Lion
•	Leopard
•	Tiger


Notes:
•	All image sources are currently absolute local paths (e.g., C:\Users\...) and must be updated to hosted URLs for deployment.
•	Project icons used for the zoom effect are standard (project-icon.png).
<img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/e12b4aff-5935-4982-848e-32a6fc1c77ec" />

<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/f384881a-8902-43f5-8dc0-9442fdd6c97c" />

 
 

4. Contact Us (#contact)
Left Column:
•	Form with inputs:
o	Name (text)
o	Email (email)
o	Message (textarea)
o	Submit Button
Right Column:
•	Motivational Message:
If my wildlife photography has caught your eye and sparked your curiosity, why not take the next step? You’re just one step away! Join my wildlife photography course and learn how to turn your passion into powerful pictures.
Form Validation:
•	Basic HTML5 required attributes are used.
•	The form action is currently empty – server-side integration needed.

 <img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/886ddf48-c862-4a80-b21c-e6e546655334" />


Visual and Styling:
General
•	Fonts: Open Sans (loaded from Google Fonts)
•	Animations: Animate.css for effects like fadeIn, bounce, etc.
•	Tabs: Styled with custom CSS (tabs.css) and jQuery plugin
•	Preloader: Loading animation displayed before the content is fully loaded
CSS Files Included:
•	bootstrap.min.css
•	bootstrap-theme.min.css
•	animate.min.css
•	easy-responsive-tabs.min.css
•	tabs.css
•	templatemo-style.css

 
<img width="940" height="516" alt="image" src="https://github.com/user-attachments/assets/8a2c5aaa-1803-4c1c-ad90-56dafe9f3d5c" />
<img width="940" height="521" alt="image" src="https://github.com/user-attachments/assets/355e2d34-2f23-4982-a8ba-8a3538337466" />
<img width="940" height="583" alt="image" src="https://github.com/user-attachments/assets/c8ad00eb-5d5c-4cc0-bf24-3883ae86b641" />
<img width="940" height="591" alt="image" src="https://github.com/user-attachments/assets/758e22d0-17dd-4bd9-aa69-ae03fa4eef37" />
<img width="940" height="539" alt="image" src="https://github.com/user-attachments/assets/f5d70f4b-2d02-4ef3-8f41-0b67a1a38418" />

 
 
 
 

JavaScript Functionality
Main Libraries and Plugins:
1.	jQuery
2.	Bootstrap 3.3.1 – handles UI components like modals, transitions, alerts, dropdowns
3.	Easy Responsive Tabs – manages vertical tab layout with dynamic hash navigation
4.	Owl Carousel – used in the “Our Projects” section
5.	NiceScroll – optional for styled scrollbars
Scripts Included:
•	modernizr-2.8.3-respond-1.4.2.min.js
•	bootstrap.min.js
•	easyResponsiveTabs.js
•	jquery.nicescroll.min.js
•	plugins.js
•	main.js
Responsive Tabs:
•	Allows switching via hash (#profile, #resume, etc.)
•	Active tab highlights with color changes
•	Automatically adjusts for vertical or accordion mode on small screens

Technical Notes
File Paths
•	Most images are referenced with local absolute paths, e.g.:
•	C:\Users\psrir\OneDrive\Desktop\wild life web img\tiger.jpg
These must be replaced with relative paths or uploaded URLs for website deployment.
HTML & SEO
•	Semantic HTML5 structure is followed.
•	Meta tags included for responsiveness and compatibility.
•	No meta description content is filled — recommended for SEO.
Accessibility
•	ARIA attributes are added for tab roles (via JavaScript plugin).
•	No alt attributes for images — should be added for screen readers.

Deployment Checklist
Task	Status
Replace all C:\Users\... image paths with relative or hosted URLs	🔲 Pending
Connect contact form to a server-side script (PHP, Node.js, etc.)	🔲 Pending
Ensure all CSS/JS/images are uploaded to server	🔲 Pending
Add meta description for better SEO	🔲 Pending
Add alt text to images for accessibility	🔲 Pending

Credits:
•	Design Template: TemplateMo
•	Developer/Photographer Credit (on page):
Sri Ram, Wildlife Photographer


