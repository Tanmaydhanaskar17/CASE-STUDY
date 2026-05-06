# CASE-STUDY
CASED STUDY ON AMAZON PRIME INTERFACE

outputs-

<img width="1829" height="774" alt="Screenshot 2026-05-06 203157" src="https://github.com/user-attachments/assets/fb738a0a-aca3-44eb-a1af-ea1b9144da37" />


<img width="1826" height="544" alt="Screenshot 2026-05-06 214846" src="https://github.com/user-attachments/assets/3ebde4f8-8594-447c-a7d4-9b28b67b1c26" />



<img width="1488" height="521" alt="Screenshot 2026-05-06 214856" src="https://github.com/user-attachments/assets/e6a69c22-ff3a-447d-b801-fe02c81a5395" />



output 2-


<img width="1829" height="774" alt="Screenshot 2026-05-06 203157" src="https://github.com/user-attachments/assets/74cdec09-6c17-4fb2-9264-02d9b6926fc2" />





1. Page Loads (HTML Initialization)

When the page opens in the browser:

The HTML structure is loaded first.
It creates placeholders for:
Navbar
Hero section
Movie rows (empty containers)

At this stage, you only see the layout — no movies yet.

 2. JavaScript Executes (Dynamic Content)

After the page loads:

The JavaScript file runs automatically.
It contains arrays of movie data (name + image).

Example:


<img width="771" height="126" alt="Screenshot 2026-04-26 091534" src="https://github.com/user-attachments/assets/dfce7a7f-80d1-49a1-a412-e3f1993ad94a" />

 3. Movie Cards Are Created

For each movie:

JavaScript creates a new <div> (movie card)
Inserts:
Movie poster (image)
Movie name (text)
Then adds it into the correct section (Recommended / Continue Watching)

This makes the interface:

Easy to update
Scalable (you can add 100+ movies easily)
 4. CSS Makes It Look Like a Streaming App

Once elements are added:

CSS styles them:
Dark theme background
Horizontal scrolling rows
Card spacing and alignment
Hover effect:
When you move the mouse over a movie → it zooms slightly
 5. User Interaction

Here’s how users interact with the interface:

Scroll horizontally → Browse movies
Hover on a movie → Visual highlight (zoom effect)
Click Play button → (Currently static, but can be connected to video)
 6. Reusability of Code

A key working concept:


<img width="653" height="145" alt="Screenshot 2026-04-26 091543" src="https://github.com/user-attachments/assets/c2f3f60b-ce62-45a0-8d48-ed6acae3bb67" />



 This avoids repeating code and improves efficiency.

7. Behind-the-Scenes Flow

Simple flow of how it works:

Page Load → HTML Structure Ready  
        ↓
JavaScript Runs  
        ↓
Movie Data Processed  
        ↓
Cards Created Dynamically  
        ↓
CSS Styles Applied  
        ↓
User Interacts with UI
