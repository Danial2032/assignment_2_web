# assignment_2_web

# Alibayev Danial , IT-2504

Task 0: Navigation Bar

HTML Structure: '<header>' container holds a .logo div and a .nav-links unordered list. Applying display: flex and justify-content: space-between to .header pushes the logo to the far left and the navigation links to the far right. Adding align-items: center keeps both elements vertically centered. Applying display: flex and gap: 20px to .nav-links arranges the list items in a horizontal row with clean spacing.



Task 1: Card Row 

HTML structure: A .card-row contains three individual .card blocks with "<img>", <h3>, <p> and <button>. .card-row uses display: flex and gap: 15px to place cards side by side with spacing. Setting flex: 1 on .card forces all three cards to set equally. .card img uses width: 100%, a fixed height 160px and objec-fit: cover to crop uneven photos proportionally. .card:hover applies transform: translateY(-5px) to give cards a smooth lift effect on mouse hover.

Task 2: Page Layout with Grid Areas

HTML structure: A .page-container wrapper encloses the four main structural regions: <header>, <aside> (sidebar), <main>, <footer>. .page-container sets display:grid defining two columns (200px fixed sidebar and 1fr flexible main area) and three rows (auto header, 1fr main content, auto footer). grid-template-areas maps the spatial arrangement: "header header" spans the top row, "sidebar main" places the sidebar on the left and content on the right, "footer footer" spans the bottom row. Each structural selector uses grid-area (.header { grid-area: header; }) to lock into its designated area.

Task 3: Image Gallery

HTML structure: A .gallery-grid container holds 9 .gallery-item divs, each containing an <img> and an .overlay caption div. .gallery-grid uses display: grid, grid-template-columns: 1fr 1fr 1fr and gap: 10px to form a uniform 3 to 3 grid. Gallery images use object-fit: cover to maintain identical aspect ratios across all grid cells. .gallery-item uses position: relative, while .overlay uses position: absolute with display: none. When hovering over .gallery-item, .overlay switches to display: flex to reveal a dark caption box over the photo.

Task 4: Portfolio Pae Integration

HTML structure: The outer layout relies on CSS Grid Areas (.page-container) to structure the header, sidebar, main section and footer. The internal components rely on Flexbox (navigation b)
