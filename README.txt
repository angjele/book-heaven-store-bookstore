Book Haven Bookstore - Touchstone 3 Website (Desktop)

Files
- index.html (Home)
- gallery.html (Gallery + Shopping Cart)
- about.html (About Us + Contact/Custom Order form)
- community.html (Custom Page)
- css/styles.css
- js/app.js
- assets/*.svg (placeholder gallery images)

How to run
1) Open index.html in a browser (double click) or use a simple live server.
2) Navigate using header/footer nav.

Key required features
- Header: logo + title + functional nav bar
- Footer: Subscribe feature + social links + nav links
- Gallery: View Cart modal, Add to Cart buttons, Clear Cart + Process Order
- Storage:
  * sessionStorage key: cartItems (array of item names)
  * sessionStorage key: orderProcessed ("true"/"false")
  * localStorage keys: contact:<Name>:<timestamp> (JSON)

Suggested screenshot checklist (matches template)
- Homepage rendered
- Subscribe success alert
- Subscribe input validation (try empty email)
- Gallery rendered
- Add item alert
- View cart after adding one item
- View cart after adding multiple items
- Clear cart alert + empty cart
- Process order alert
- Process order after already processed alert
- sessionStorage before and after processing (DevTools > Application)
- About Us rendered
- Contact form filled + submit alert
- localStorage after form submission (DevTools > Application)
- Contact form input validation (submit empty)
- Custom page rendered
