# ModernEditor, Kevin Bryan, July 2025, MIT License
A modern text editor that includes custom stylistic suggestions. Runs in a web browser.  

(By the way, for more from me, see @Afinetheorem on Twitter, or <a href="http://www.kevinbryanecon.com">kevinbryanecon.com</a>.  If you find this useful, you'll love <a href="http://www.alldayta.com">All Day TA</a>, the best AI for university classrooms (used in over 25 countries!), and <a href="http://www.kevinbryanecon.com/ModernSlides">ModernSlides</a>, my free in-browser slideshow software)

You can run this locally or at kevinbryanecon.com/ModernEditor. The idea is to do basic Grammarly/Word-type spell and grammar checks, but also to do "style" checks according to a custom rule. I have preset three rules - Literary Nonfiction is my favorite - and the model will make up to hundreds of suggestions which you can go through with Backspace and Enter to reject/accept. There is now an undo feature. Suggestions are editable in line before accepting. If you highlight text, the code will pop up a "simplify" box to make simplification suggestions, and if you do this to a theorem and proof, it will try to check your proof using Gemini 2.5 Pro.

All you need is a Gemini API key, either entered by you or else in keys.js as "Gemini,....." in your base directory if running locally.  You can add your own style guide following the model and comment in styles.js.
