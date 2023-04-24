# sign-language-detector-python

Sign language detector with Python, OpenCV and Mediapipe.

## Prepare

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Instructions

    1. Collect the images using the collect_imgs.py. Maybe youll have to change line 14 with VideoCapture. Depending on your camera the number will be different.

    ```bash
    python collect_imgs.py
    ```

    Use one or two hands to create different signs with you hands. Press "Q" each time to change the sign and save the images.

    2. Create dataset, using the images from previous step.

    ```bash
    python create_dataset.py
    ```

    3. Train the model

    ```bash
    python train_classifier.py
    ```

    4. Test the model

    ```bash
    python inference_classifier.py
    ```
    
## Video

Original video

[![Watch the video](https://img.youtube.com/vi/MJCSjXepaAM/0.jpg)](https://www.youtube.com/watch?v=MJCSjXepaAM)

