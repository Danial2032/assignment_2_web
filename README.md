# assignment_2_web

# Alibayev Danial , IT-2504

Task 0: Navigation Bar

HTML Structure: <'header'> container holds a .'logo' div and a .'nav-links' unordered list. Applying display: flex and justify-content: space-between to .'header' pushes the logo to the far left and the navigation links to the far right. Adding align-items: center keeps both elements vertically centered. Applying display: flex and gap: 20px to .nav-links arranges the list items in a horizontal row with clean spacing.

<img width="649" height="592" alt="imm1" src="https://github.com/user-attachments/assets/39ad7aef-ff3d-41b2-9ffb-5469c72dccca" />

Task 1: Card Row 

HTML structure: A .card-row contains three individual .card blocks with <'img'>, <'h3'>, <'p'> and <'button'>. .'card-row' uses display: flex and gap: 15px to place cards side by side with spacing. Setting flex: 1 on .card forces all three cards to set equally. .card img uses width: 100%, a fixed height 160px and objec-fit: cover to crop uneven photos proportionally. .card:hover applies transform: translateY(-5px) to give cards a smooth lift effect on mouse hover.

<img width="537" height="575" alt="imm2" src="https://github.com/user-attachments/assets/fbcf45ac-8537-49ce-a672-3e874c314ff1" />

Task 2: Page Layout with Grid Areas

HTML structure: A .page-container wrapper encloses the four main structural regions: <'header'>, <'aside'> (sidebar), <'main'>, <'footer'>. .page-container sets display:grid defining two columns (200px fixed sidebar and 1fr flexible main area) and three rows (auto header, 1fr main content, auto footer). grid-template-areas maps the spatial arrangement: "header header" spans the top row, "sidebar main" places the sidebar on the left and content on the right, "footer footer" spans the bottom row. Each structural selector uses grid-area (.header { grid-area: header; }) to lock into its designated area.

<img width="373" height="448" alt="imm4" src="https://github.com/user-attachments/assets/a838b40e-dc90-449d-8b64-21adc2bd09d6" />

Task 3: Image Gallery

HTML structure: A .gallery-grid container holds 9 .gallery-item divs, each containing an <img> and an .overlay caption div. .gallery-grid uses display: grid, grid-template-columns: 1fr 1fr 1fr and gap: 10px to form a uniform 3 to 3 grid. Gallery images use object-fit: cover to maintain identical aspect ratios across all grid cells. .gallery-item uses position: relative, while .overlay uses position: absolute with display: none. When hovering over .gallery-item, .overlay switches to display: flex to reveal a dark caption box over the photo.

<img width="389" height="328" alt="imm3" src="https://github.com/user-attachments/assets/671cf87c-0c56-4554-9684-24f77e6e912f" />

Task 4: Portfolio Page Integration

HTML structure: The outer layout relies on CSS Grid Areas (.page-container) to structure the header, sidebar, main section and footer.

<img width="373" height="448" alt="imm4" src="https://github.com/user-attachments/assets/f0f117d8-b473-4c69-a0c7-949e31675eee" />

Summary: 

I used CSS Grid and Flexbox to make the web-site according to the assignment. To make my web-site interactive I used hover pseudocalss in the card with transform translateY(-5) that makes the card go up, while transition: transform 0.2 ease made the animation of the card going up. Moreover, .gallery-item: hover .overlay makes the .overlay appear when hovered. Until hovering .overlay is hidden because it has display: none;.

Web-site link: https://danial2032.github.io/assignment_2_web/
