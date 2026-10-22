ROWDY PROVISIONS CO. SITE - HOW TO USE

1) Set your ordering link + business name
   Open index.html in any text editor, scroll to the "EDIT HERE" block near the bottom:
     const ORDER_URL  = "";   <- paste your link inside the quotes
     const BRAND_NAME = "Rowdy Provisions Co.";
   Every Shop / Order button on the site uses that one link.

2) Add, remove, or swap shirts
   Put the image in the designs/ folder, then add a line to the DESIGNS list:
     { img: "designs/my-shirt.jpg", name: "Shirt Name", color: "Black", desc: "Short description." },
   Delete a line to remove a shirt. List order = carousel order.
   HERO_PICKS chooses which 3 shirts show in the top fan (0 = first shirt).

3) Put it online (free)
   - Netlify Drop: go to app.netlify.com/drop and drag this whole folder in.
   - or GitHub Pages: upload the folder to a repo, Settings > Pages > deploy from main.
   Keep index.html, logo.png, and the designs/ folder together.
