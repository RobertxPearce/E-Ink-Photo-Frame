# E-Ink-Photo-Frame
Photo frame using Pimoroni's Inky Impression 7.3 e-ink display.

## How to Use
1. **SSH into Pi**
    * Username and password on back of frame.
2. **Move to Directory**
    * Use command `cd /Desktop/E-Ink-Photo-Frame/Code`
3. **Run the Program**
    * Use command `python loop_photos.py <album name>`
    * Use command `python static_photo.py <photo location>`

## Files
### `Code`
* Directory for custom code to operate display.
### `Photos`
* Photo albums I made for display.
### `Resources`
* Resources from Pimoroni and Thingiverse.
  * `Inky Impression 7.3`: Directory for Inky Impression display resources.
      * `inky-main`: Pimoroni libraires, tools, and example code.
      * `Schematics`: Schematics for the display
      * `Drawing`: Drawing of the display for dimensions.
  * `Cases`: 3D print files for display case.

## Build Process

### Tech Assembly 🔧
* Components
  * Inky Impression 7.3" (7 colour ePaper/E Ink HAT) by Pimoroni
  * Raspberry Pi Zero 2 W WH
  * 32gb Micro SD Card (Headless Pi OS)

### Code 💻

* `loop_photos.py`: Program to loop through a collection of photos.


* `static_photo.py`: Program to display a static photo.


### Frame Assembly 🖼️
