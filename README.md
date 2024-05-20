# Compresos AG Welcome Screen

This repository contains the code for a static website designed to run on an Tablet located at the entrance of our agency. The website displays a video in an endless loop, creating a welcoming experience for visitors.

## Features

- **Endless Loop Video**: The website plays a specified video in an infinite loop.
- **Static Website**: Simple and lightweight, designed to run smoothly on an iPad.
- **Responsive Design**: Ensures the video displays correctly on the iPad screen.

## Setup

To set up and run the website on an iPad, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/agency-welcome-screen.git
    cd agency-welcome-screen
    ```

2. **Prepare the Video**:
    - Place your video file in the `assets` directory.
    - Update the `version1.html` file to reference your video file. Replace `video.mp4` with the name of your video file.
    ```html
    <video autoplay="true" loop="true" autoplay="true" muted="true">
      <source src="./assets/video.mp4" type="video/mp4">
    </video>
    ```

3. **Deploy the Website**:
    - You can use any web browser to open the static HTML File.
  

## Customization

- **Video Settings**: You can adjust the video settings (autoplay, loop, mute) directly in the `version1.html` file.
- **Styling**: Modify the CSS in the head part in `version1.html` file to change the appearance of the website.

## Troubleshooting

- If the video does not play, ensure the video file format is supported by the Tablet (Mostly you need a mp4 File with a h264 Codec).
- Check the video file path in the `version1.html` file to make sure it is correct.

---

For any questions or issues, please contact samuel.ruegger@compresso.ch.

