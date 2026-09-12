# University Gyaan — Subscribe & Download Gate

## Files
- index.html
- logo.jpg  ← place your University Gyaan logo here

## Change only these links in index.html

### YouTube
Find:
const YOUTUBE_CHANNEL = "https://www.youtube.com/@UniversityGyaan";

Replace with your actual YouTube channel URL.

### PDF
Find:
const PDF_LINK = "https://drive.google.com/";

Replace with the PDF/Google Drive download URL.

## Flow

1. User opens the PDF download page.
2. Instruction tells the user to:
   - Subscribe to the YouTube channel
   - Like any one video
   - Watch a video for at least 10 seconds
   - Return to the page
3. Subscribe button is shown.
4. There is NO "I Have Subscribed" button.
5. A warning remains visible.
6. Download button automatically becomes enabled after 15 seconds.
7. No countdown or seconds are displayed.

## Free hosting

Upload these files to a GitHub repository and enable GitHub Pages.

Important:
This is a free user-confirmation/wait gate. It does not technically verify whether the visitor actually subscribed, liked or watched a YouTube video.
