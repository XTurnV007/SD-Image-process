# Lajiaochaorou SD Image Cropper

#### Introduction
Lajiaochaorou Image Cropper is a flexible and easy-to-use batch image adjustment tool. It allows you to resize your images to any specified dimensions and crop them proportionally if necessary. This is an online tool, so you don't need to download or install anything on your computer. Lajiaochaorou Image Cropper is completely free to use.

# -> [Demo Site Vercel](https://lajiaochaorou-nine.vercel.app/) <-
# -> [Demo Site Github](https://xturnv007.github.io/lajiaochaorou/) <-

# Image Cropping Tool for Stable Diffusion
When training Stable Diffusion (or other image generation models), high-quality training images cropped to 512x512 are essential. Lajiaochaorou Image Cropper is the best tool to quickly accomplish this task. With the help of [smartcrop.js](https://github.com/jwagner/smartcrop.js/), it becomes a very powerful batch image cropping tool.

## Local Installation
Clone this repository and open the `index.html` file in your favorite browser. You can even bookmark it for quick access!
```bash
git clone https://github.com/XTurnV007/lajiaochaorou.git
cd lajiaochaorou
python -m webbrowser index.html  # Or simply open the index.html file directly
```

## Run with Docker-Compose
```bash
git clone https://github.com/XTurnV007/lajiaochaorou.git
cd lajiaochaorou
docker-compose up -d
# Open in your browser => http://<HOST_IP>:8080
```

## Authors
- [Original Birme Author, support them](https://www.birme.net/)
- The single image editing feature was developed by me.

## Additional Information
The Hermite quality option uses the [Hermite resize library](https://github.com/viliusle/Hermite-resize), allowing you to experiment with the source image to achieve the best possible image quality.

Disclaimer: This project is based on the open-source project [Birme Variant for Stable Diffusion](https://github.com/livelifebythecode/birme-sd-variant). It has been modified to include the ability to set resolutions for individual images and translate the English text into Chinese, making it more suitable for domestic users.
