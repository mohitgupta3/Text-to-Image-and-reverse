# Text-to-Image-and-reverse
A handy tool to convert large text files to a grey scale image and convert that image to the original text.

## Usage
To convert a text file to an image
```
python TextToImage.py -f <name-of-text-file> -l <Decimal-value-limit-for-pixel-value (1 to max)> <path-to-image>.png
```
or

```
python TextToImage.py -t <your-text> -l <Decimal-value-limit-for-pixel-value (1 to max)> <path-to-image>.png
```

To convert the image back to the original text

```
python ImageToText.py -f <path-to-image-file> <path-to-image>.png
```
