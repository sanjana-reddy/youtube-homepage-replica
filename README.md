# youtube-homepage-replica
 A fully responsive YouTube inspired homepage built with semantic HTML5 and modular CSS3 ,no frameworks, just clean, scalable front-end engineering.
 The goal of this project is to replicate the core layout, design, and responsiveness of YouTube's home page for learning and practice.

 
---

### 🧾 HTML (`youtube.html`)

- Built using **semantic tags**: `<header>`, `<nav>`, `<main>`, and `<section>`.
- Contains **three core sections**:
  1. **Header**: YouTube logo, search bar, and user action icons.
  2. **Sidebar**: Vertical menu with icons and labels.
  3. **Video Grid**: A flexible grid of video previews including thumbnail, title, channel, and views.

Each video preview is wrapped in a `div.video-preview`, containing:
- A thumbnail image and timestamp (`.thumbnail-row`, `.video-time`)
- Channel picture (`.channel-picture`)
- Video information (`.video-info` with title, author, stats)

---

### 🎨 CSS

#### `general.css`
- Applies default `body` styling and global padding/margins.
- Uses **Roboto / Arial** font family for a clean UI look.
- Sets `background-color`, `padding` for header space, and `padding` for sidebar.

#### `header.css`
- Styles the top **header bar**, including:
  - Flex layout for logo, search, and icons
  - Tooltips on hover using `position: absolute` and `opacity` transitions
  - Custom styled `search-bar`, `voice-search-button`, and notification counter

#### `sidebar.css`
- Styles the **sidebar** using `position: fixed` and vertical flex layout.
- Sidebar icons change background color on hover for interactivity.

#### `video.css`
- Styles the **video grid layout** using **CSS Grid**.
- Adapts responsively using media queries:
  - 2 columns (≤600px)
  - 3 columns (751–999px)
  - 4 columns (≥1000px)
- Each video block contains cleanly styled:
  - Thumbnails (`.thumbnail`)
  - Video metadata (`.video-title`, `.video-author`, `.video-stats`)
  - Channel profile images (`.profile-picture`)

---

### Responsiveness

The layout is made fully responsive using media queries. It adjusts the video grid column count based on screen width:

On mobile devices (≤600px): The grid shows 2 columns for compact view.

On tablets (751px to 999px): The layout expands to 3 columns.

On desktops (≥1000px): A full 4-column grid provides a rich browsing experience.

These breakpoints ensure smooth adaptability across devices, enhancing usability and visual consistency.

 ## What I Learned

Through building this project from scratch, I was able to solidify and master several key front-end development concepts:
- **Semantic HTML Structuring**  
  Gained confidence in organizing complex UIs using semantic tags and clear DOM hierarchies, resulting in accessible and maintainable code.

- **Flexbox & Grid Proficiency**  
  Mastered layout systems by applying Flexbox and CSS Grid to build responsive, multi-section interfaces such as headers, sidebars, and video grids.

- **Responsive Design Principles**  
  Implemented responsive breakpoints with media queries to ensure a seamless layout transition across various screen sizes.

- **Advanced Tooltip Styling**  
  Built dynamic tooltip interactions using only CSS, demonstrating control over hover states, positioning, and smooth transitions.

- **Positioning & Layering Techniques**  
  Learned how to manage element stacking using `position` properties and `z-index` to achieve a clean, layered UI.

- **Reusable, Modular CSS**  
  Applied a modular design pattern to my CSS, creating reusable class-based styles for consistent component behavior across the app.

- **UI Recreation with Pixel Precision**  
  Improved attention to design detail by accurately replicating YouTube’s visual layout and user experience using only HTML and CSS.

- **Asset Management**  
  Structured and optimized image assets like thumbnails and icons in an organized way for efficient rendering and maintainability.

This project deepened my understanding of how professional UIs are built and prepared me to approach front-end challenges with a more structured and scalable mindset.



