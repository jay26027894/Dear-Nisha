# Birthday Website

This is a simple static website created to celebrate a birthday. It includes a photo gallery, a timeline, and a letter.

## Project Structure

- `index.html`: The main landing page.
- `gallery.html`: A photo gallery with a lightbox.
- `timeline.html`: A page that displays a timeline of events.
- `letter.html`: A page that displays a letter.
- `why.html`: A page that explains the reason for the website.
- `input.css`: The source CSS file for Tailwind CSS.
- `output.css`: The compiled CSS file.
- `images/`: A directory containing all the images used in the website.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
## Building the CSS

To build the CSS file, run the following command:
```bash
npx tailwindcss -i ./input.css -o ./output.css --watch
```
This command will watch the `input.css` file and automatically rebuild the `output.css` file whenever you make changes.
