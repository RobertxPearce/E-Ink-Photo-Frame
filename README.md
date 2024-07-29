# E-Ink-Photo-Frame
Photo frame using Pimoroni's Inky Impression 7.3 e-ink display.

## How to Use
1. **SSH into Pi**
2. **Move to Directory**
   ```bash
   cd /Desktop/E-Ink-Photo-Frame/Code
   ```
4. **Run the Program**
   ```bash
   python3 image_static.py
   ```
   ```bash
   python3 image_loop.py
   ```
5. **Run Loop in Background**
   ```bash
   nohup python3 image_loop.py &
   ```
6. **Kill Program**
  * Find Programs PID
    ```bash
    ps aus | grep image_loop.py
    ```
    ```bash
    kill <PID>
    ```

## Files
### Code
* Directory for custom code to operate display.
### Photos
* Photo albums I made for display.
### Resources
* Resources from Pimoroni and Thingiverse.
