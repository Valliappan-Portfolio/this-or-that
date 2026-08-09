THIS OR THAT — Setup Instructions
==================================

FOLDER STRUCTURE (keep exactly like this):
  this-or-that/
  ├── index.html        ← the app
  ├── README.txt        ← this file
  └── images/           ← put ALL your photos here
        Aishwarya Lekshmi.avif
        Aishwarya Rajesh.webp
        Anagha.jfif
        Anupama.jpg
        Anushka Shetty.jpg
        Asin.jpg
        Iswarya Menon.webp
        Kajal Agarwal.png
        Kayadu Lohar.jpg
        Keerthy Suresh.jpg
        Ketika.jfif
        Malavika Mohanan.webp    ← make sure renamed to this
        Mamitha Baiju.jfif
        Meenakshi Chaudry.png
        Mrunal Thakur.jpg
        Nitya Menon.jfif
        Pooja Hegde.jfif
        Preity Mukundhan.png
        Priya Anand.jfif
        Priyamani.png
        Rashmika.jfif
        Saanve.jfif
        Samantha.webp
        Samyuktha.jfif
        Shobitha.webp
        Shriya.jfif
        Sree Leela.jpg
        Trisha.jfif

HOW TO RUN LOCALLY:
  - Open index.html directly in Chrome or Edge
  - OR right-click → Open with → Chrome

NOTE: Do NOT open with Firefox from a local file path — 
images may not load due to CORS. Chrome/Edge work fine locally.

ADDING NEW CATEGORIES:
  - Open index.html in any text editor (Notepad, VS Code)
  - Find the CATEGORIES block in the <script> section
  - Copy the "fincher" block and replace with your new data
  - Add a cat-card button in the home grid (copy an existing one)

ADDING MORE HEROINES:
  - Put the photo in the images/ folder
  - Add a line to the heroines items array:
    { name: 'Name Here', meta: 'Language info', emoji: '⭐', img: 'images/filename.jpg' }

