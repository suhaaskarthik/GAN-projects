# landscape-colouriser

Repository consists of two separate projects that work with the pix2pix gan architecture. First one I have manually web-scraped over 10k images from the internet, converted them into grayscale. Built and trained a pix2pix architecture from the ground-up for it to learn how to revert to its colourised form. 

Similarly i worked with another anime coloruiser dataset where the anime outline is provided by the user and, the AI learns how to colourise the outline. I used a higher-end NVIDIA A100 GPU for this, due to the various requirements.
Another project is a lunar rock segmentation, that uses the same architecture to identify small, medium and large size rocks, by giving them various colours, aswell as the empty space background and lunar rock surface
