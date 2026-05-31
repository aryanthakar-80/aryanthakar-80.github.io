# Aryan Thakar Portfolio

Static portfolio site for GitHub Pages.

## Files

- `index.html` - main portfolio page
- `resume.pdf` - optional resume file; add this if you want the resume download button to work
- `assets/projects/` - project photos and videos used by the project detail links

## Publish on GitHub Pages

1. Create a GitHub repository named `aryanthakar-80.github.io`.
2. Upload `index.html`, `resume.pdf`, and the `assets` folder to the root of that repository.
4. Go to repository `Settings` > `Pages`.
5. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save, then open `https://aryanthakar-80.github.io` after GitHub finishes deploying.

## Project Detail Links

Each project card uses a shareable hash link, similar to `#/projects/motor-performance-variable-loads`:

- `#/projects/ai-vision-expansion-board-k210`
- `#/projects/underwater-robot-controller`
- `#/projects/sensor-fusion-localisation`
- `#/projects/autonomous-hexapod-robot`
- `#/projects/pd-control-pic-microcontroller`
- `#/projects/next-embedded-project`

## Adding Photos and Videos

Place your media files in the matching folder:

- `assets/projects/k210/`
- `assets/projects/underwater-robot/`
- `assets/projects/localisation/`
- `assets/projects/hexapod/`
- `assets/projects/pic-control/`
- `assets/projects/next/`

The current `index.html` expects these example filenames:

- photos: `board-photo.jpg`, `firmware-test.jpg`, `controller.jpg`, `gui.jpg`, `robot.jpg`, `visualisation.jpg`, `lidar.jpg`, `circuit.jpg`, `scope.jpg`
- videos: `demo.mp4`, `test-run.mp4`, `walking-demo.mp4`

You can either rename your files to match those paths, or edit the `media` arrays near the bottom of `index.html`.

## Customization

- Replace the sixth placeholder project with a real project when ready.
- Add `resume.pdf` beside `index.html`, or change the resume link in the HTML.
- For a custom domain, add a `CNAME` file with only the domain name in it, then configure DNS in your domain provider.
