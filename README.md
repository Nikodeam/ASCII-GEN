# ASCII-GEN
Simple img2img ascii
Based off [ASCII-Generator by vietnh1009](https://github.com/vietnh1009/ASCII-generator)

## Run example:
python3 img2img.py --input data/ballsackbird.webp --output data/output.jpg --language english --mode standard --background white --num_cols 200

## Path to input
"--input", type=str, default="data/input.jpg"
## Path to output
"--output", type=str, default="data/output.jpg"
## Language (alphabets.py)
"--language", type=str, default="english")
## Mode
"--mode", type=str, default="standard")
## Background Color
"--background", type=str, default="black", choices=["black", "white"]
## Number of characters within width
"--num_cols", type=int, default=300, help="number of character for output's width")

### Requirements
numpy
pillow
opencv-python
