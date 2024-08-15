# Spotify Clone Web Player

This project is a simple Spotify Web Player clone, designed to mimic the look and feel of Spotify's interface. It is built using **HTML**, **CSS**, and **JavaScript**. The clone features a sidebar navigation menu, a main content area displaying music cards, and a fixed music player at the bottom.

---

### Features
1. **Responsive Layout**:
    - The layout adjusts to different screen sizes. For smaller screens, certain elements are hidden.
2. **Sidebar Navigation**:
    - A left sidebar includes navigation options such as Home, Search, and Your Library.
3. **Music Cards**:
    - The main content area displays multiple sections of music cards, such as "Recently Played", "Trending Now", and "Featured Charts".
4. **Fixed Music Player**:
    - A bottom-fixed music player displays song information, playback controls, and volume controls.
5. **Hover Effects**:
    - Interactive buttons and icons with hover effects that change their opacity.
6. **Playback Bar and Volume Slider**:
    - Custom sliders for both the playback progress and the volume level.

---

### Project Structure

```
spotify-clone/
├── Assets/               # Folder containing images and icons used in the project.
├── HW_Assets/            # Folder containing additional images and icons for the music player.
├── index.html            # Main HTML file.
├── style.css             # CSS file for styling the Spotify Web Player.
└── README.md             # Project documentation.
```

---

### File Breakdown

1. **HTML** (`index.html`):
    - Defines the structure of the web page.
    - Includes a sidebar navigation, main content area, and fixed music player.
    - Contains references to assets and stylesheets.
    - Utilizes FontAwesome icons for visual elements like the Spotify logo, home, and search icons.

2. **CSS** (`style.css`):
    - **Global Styles**:
        - Sets default styling for the body with a dark background and white text.
    - **Layout**:
        - Utilizes Flexbox for both the sidebar and main content layout, ensuring responsive design.
    - **Sidebar**:
        - Styles for the sidebar, including navigation links and library sections.
    - **Main Content**:
        - Defines styles for music cards, including image cards with titles and descriptions.
    - **Music Player**:
        - Customizes the appearance and functionality of the fixed music player, including playback buttons and sliders for progress and volume.
    - **Hover Effects**:
        - Adds hover effects to buttons, icons, and music cards for an interactive experience.

---

### How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/spotify-clone.git
   ```

2. **Open `index.html`**:
   - Navigate to the project directory and open the `index.html` file in your preferred web browser.
   
3. **Assets**:
   - Ensure all image files are in the correct `Assets/` and `HW_Assets/` folders.

---

### Customization

- You can easily customize this project by replacing the images in the `Assets/` and `HW_Assets/` folders with your own.
- Modify the text, titles, and descriptions in the HTML to reflect different music content.

---

### Technologies Used

- **HTML**: Structure of the page.
- **CSS**: Styling for the user interface, including layout and responsiveness.
- **FontAwesome**: Used for icons in the navigation and music player.
- **Google Fonts (Montserrat)**: Applied for the primary font in the project.

---

### Screenshots

**1. Main Layout:**
![Screenshot of main layout](./Assets/screenshot_main.png)

**2. Music Player:**
![Screenshot of music player](./Assets/screenshot_player.png)

---

### License

This project is licensed under the MIT License - feel free to use and modify it for your own projects.

---

### Credits

- **Icons**: FontAwesome
- **Font**: Google Fonts (`Montserrat`)
- **Inspiration**: Spotify Web Player
