# Neural Style Transfer

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PALADUGU VISHNU VARDHAN

*INTERN ID*: CODF32

*DOMAIN*: ARTIFICIAL INTELLIGENCE 

*DURATION*: 4 WEEEKS

*MENTOR*: NEELA SANTOSH KUMAR



This project implements neural style transfer using TensorFlow Hub. It applies the artistic style from one image to the content of another image.

## Setup

1. Install dependencies:
```
pip install tensorflow tensorflow-hub pillow matplotlib numpy
```

2. Make sure you have content and style images in the root directory:
   - `content.jpg` - The image whose content you want to preserve
   - `style.jpg` - The image whose artistic style you want to apply

## Running the Neural Style Transfer

Open and run the Jupyter notebook:
```
jupyter notebook neural_style_transfer.ipynb
```

or

```
jupyter lab
```

The notebook contains a complete implementation of neural style transfer using Google's pre-trained model for fast and high-quality results.

## Output

The final stylized image will be saved as `stylized_tf_hub.jpg` in the root directory.

## Features

- Fast style transfer using pre-trained models
- No lengthy training required
- Handles various image formats and sizes
- Produces high-quality stylized images

The TensorFlow Hub implementation automatically balances content preservation and style transfer, providing excellent results with minimal configuration.

# Output
![Output ](output.png)