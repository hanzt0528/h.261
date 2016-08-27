# h.261

H.261 is an ITU-T video compression standard, first ratified in November 1988.[1][2] It is the first member of the H.26x family of video coding standards in the domain of the ITU-T Video Coding Experts Group (VCEG), and was the first video codec that was useful in practical terms.

H.261 was originally designed for transmission over ISDN lines on which data rates are multiples of 64 kbit/s. The coding algorithm was designed to be able to operate at video bit rates between 40 kbit/s and 2 Mbit/s. The standard supports two video frame sizes: CIF (352x288 luma with 176x144 chroma) and QCIF (176x144 with 88x72 chroma) using a 4:2:0 sampling scheme. It also has a backward-compatible trick for sending still images with 704x576 luma resolution and 352x288 chroma resolution (which was added in a later revision in 1993).

 Each macroblock consists of a 16×16 array of luma samples and two corresponding 8×8 arrays of chroma samples, using 4:2:0 sampling and a YCbCr color space.
 
 
 CIF (Common Intermediate Format or Common Interchange Format), also known as FCIF (Full Common Intermediate Format), is a format used to standardize the horizontal and vertical resolutions in pixels of YCbCr sequences in video signals, commonly used in video teleconferencing systems. It was first proposed in the H.261 standard.

CIF was designed to be easy to convert to PAL or NTSC standards. CIF defines a video sequence with a resolution of 352 × 288 like PAL Source Input Format, a framerate of 30000/1001 (roughly 29.97) frames like NTSC, with colour encoded using YCbCr 4:2:0.
The CIF "image sizes" were specifically chosen to be multiples of macroblocks (i.e. 16 × 16 pixels) because of the way that discrete cosine transform based video compression/decompression is handled. So, by example, a CIF-size image (352 × 288) corresponds to 22 × 18 macroblocks.
