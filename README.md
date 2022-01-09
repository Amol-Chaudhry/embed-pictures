
# Embed Pictures

This feature gives user the ability to embed images of different formats within the document instead of linking while importing.
The images can be as high as tifs up to 500 MB.

To achieve this, I modified the internal representation, which was earlier used for only low-resolution images, to work with high res images.

I also had to modify and develop algorithms to ensure that Image effects, Advanced Image effects, and colorization is working with the embedded images.

Additionally, I had to ensure that embedded color profiles, source setup, PSD layers, and embedded alpha mask and embedded clipping mask were also working with the resultant images.
