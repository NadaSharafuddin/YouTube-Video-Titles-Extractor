# UiPath-YouTube-Video-Titles-Extractor
 
This UiPath automation extracts **all video titles** from **any given YouTube channel** using **any web browser**, and exports the results into a **clean Excel spreadsheet** saved directly on your desktop.

##  What It Does

- Prompts the user to enter the full URL of a YouTube channel.
- Opens the specified channel in a browser (Chrome/Edge/Firefox).
- Scrolls through the page to load all videos.
- Extracts only the **titles** of all available videos (no dates, no links).
- Generates an Excel file named `YouTubeVideoTitles.xlsx` on your desktop.

##  Project Files

- `Main.xaml` – The main workflow that orchestrates the automation.
- `Process User Input.xaml` – A sub-workflow that handles user interaction and input validation.
- `Extract Data.xaml` – A sub-workflow that handles data scraping, formatting, and Excel output.
- `project.json` – Configuration file for the UiPath project.

## 🛠 Requirements

- UiPath Studio or UiPath Assistant (Community or Enterprise Edition)
- Excel installed (or Excel Activities configured in UiPath)
- Internet connection
- A modern browser (Chrome, Edge, or Firefox)

##  How to Use

1. **Download this repository**  
   Click the green `Code` button > `Download ZIP`, then extract it on your desktop.

2. **Open in UiPath Studio**  
   Launch UiPath Studio and open the extracted project folder.

3. **Run the Automation**  
   - Run the project.
   - When prompted, enter a YouTube channel URL (e.g., `https://www.youtube.com/c/NASA`).
   - Let the robot do the rest!

4. **View Your File**  
   Check your desktop for a file called `YouTubeVideoTitles.xlsx`.

##  Example Output

| Title |
|-------|
| Journey to Mars – NASA's Latest Mission |
| Behind the Scenes at the ISS |
| How Solar Storms Affect Earth |

## 🤖 Bonus: Custom Code

This project uses **Invoke Code** (VB.NET) to:
- Dynamically get the current user's desktop path.
- Ensure that the Excel file is saved in a platform-independent way, no matter whose PC it runs on.

##  Use Case

This project was designed for **content analysts, educators, or marketers** who need to quickly audit or track content published by any YouTube creator — without copying titles manually.

---

##  FAQ

**Q: Can I run this without installing UiPath?**  
A: No, you need UiPath Assistant or Studio installed. See details in the main [documentation here](https://docs.uipath.com).

**Q: Does it download video links, thumbnails, or dates?**  
A: No, this version focuses only on extracting titles for simplicity and speed.

---

##  Contact

Have feedback or need support?  
You can contact the developer or open an issue here on GitHub.

---

© 2025 – UiPath YouTube Video Titles Extractor · Licensed for educational/demo use.
