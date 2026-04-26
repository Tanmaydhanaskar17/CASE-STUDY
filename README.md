# CASE-STUDY
CASED STUDY ON AMAZON PRIME INTERFACE

outputs-

<img width="722" height="468" alt="Screenshot 2026-04-25 185902" src="https://github.com/user-attachments/assets/3afe50be-96cf-4a27-9c96-0f64b459e7aa" />

output 2-
<img width="973" height="443" alt="Screenshot 2026-04-26 090444" src="https://github.com/user-attachments/assets/25dbf067-7c56-4d17-b87c-08cadd2b6f50" />


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
