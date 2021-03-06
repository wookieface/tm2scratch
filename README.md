# TM2Scratch

TM2Scratch connects Google Teachable Machine 2 with Scratch 3. You can use image, audio recognition on Scratch project (pose recognition to be released in near future).

## How to use

### Image recognition

1. On [Google Teachable Machine 2](https://teachablemachine.withgoogle.com/) website, create an image classification model and upload it.

2. Copy the sharable link.

  <img src="images/en/sharable_link.png" />

3. Open http://champierre.github.io/tm2scratch on Chrome browser.

4. Open "Choose an Extension" window and select "TM2Scratch".

5. Paste the shareble link into the text field of "image classification model URL" block.

  <img src="images/en/load_image_model_url.png" />

6. You can use the image recognition results with "when received image label" blocks.

  <img src="images/en/when_received.png" />

### Audio recognition

1. On [Google Teachable Machine](https://teachablemachine.withgoogle.com/) website, create a sound classification model and upload it.

2. Copy the sharable link.

3. Open http://champierre.github.io/tm2scratch on Chrome browser.

4. Open "Choose an Extension" window and select "TM2Scratch".

5. Paste the shareble link into the text field of "sound classification model URL" block.

  <img src="images/en/load_sound_model_url.png" />

6. You can use the sound recognition results with "when received sound label" blocks.

  <img src="images/en/when_received_sound_label.png" />

## For Developers - How to add TM2Scratch extension to your (customized) Scratch

1. Prepare LLK/scratch-gui on your local machine.

    ```
    % git clone git@github.com:LLK/scratch-gui.git
    % cd scratch-gui
    % npm install
    ```

2. Run the install script.

    ```
    % curl https://raw.githubusercontent.com/champierre/tm2scratch/master/install.sh | sh
    ```

3. Run Scratch, then go to http://localhost:8601/.

    ```
    % npm start
    ```
