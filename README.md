# unit1finalcode
 final project esstionally first draft of random generation code 

import fileinput "images"
from os import listdir, path
import random
from PIL import Image

files = listdir("images")
files.remove(".DS_Store")

random_file = random.choice(files)

img = Image.open( path.join("images",random_file) )


# let's make a 100x100 white image

width = 100
height = 100

or x in range(width):
    for y in range(height):
        pixel = new_img.getpixel((x,y))
        if pixel[1] > 200

img = Image.new("RGB", 100x100,100x100) )


img.putdata(data)

img.save(sys.argv[1])



