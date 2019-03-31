## Jupyter Notebook - TensorFlow-GPU - Google Deep Learning VM

1. Go to [Deep Learning VM](https://console.cloud.google.com/marketplace/details/click-to-deploy-images/deeplearning?angularJsUrl=%2Fmarketplace%2Fdetails%2Fclick-to-deploy-images%2Fdeeplearning&authuser=1)
2. Select your project
3. Give it a name
4. Customize the Machine type
5. Enable "Install NVIDIA GPU driver automatically on first startup"
   
6. Install Google Cloud SDK [Windows](https://cloud.google.com/sdk/docs/quickstart-windows) | [ macOS](https://cloud.google.com/sdk/docs/quickstart-macos)
7. [Connecting to Jupyter Lab](https://cloud.google.com/deep-learning-vm/docs/jupyter)
8. Installing python libraies: 
   1.  In a cell.
    ```python
    import sys
    !{sys.executable} -m pip install numpy  
    ```
    2. Reset the machine (didn't find a more convinate way)
9. Deep you mind!
