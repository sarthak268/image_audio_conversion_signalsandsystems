# Image-Audio Encryption-Decryption System

Courses Project for Signals and Systems

Mentor : Dr. Anubha Gupta

A system that converts audio to image and visa versa. Used two algorithms for this : <br>
(1) Version1 - Lossy: Losses data but requires less space. Compressed the data to 18% of original size.<br>
(2) Version2 - Lossless: Retains all original data but requires more space than lossy. Compressed data to 72.2% of original size.

The system can send encrypted audio files ( that are generated by merging the image from original audio along with another image). This is sent along with this other image that holds the key to decryption of this audio file and hence, the original audio can be recovered. 

## Usage
encode.py in version1 and version2 folders encode the audio and image as a new image that cannot be interpreted by other while decode.py is the key to decode the image. We will need the audio as well as the one image to get the image that has been encrypted.
