# pytorch-neural-style-transfer

beast neural style transfer using googlenet inception instead of VGG like all other python3+ style transfers.
this way we eliminate the need for 4gb ram, eliminate GPU dependency(although still recomended) & eliminate need for hundreds of iterations. Also includes support for large HD images with no cropping/truncation. thus you retain 100% quality with no distortion loss.
(many others dont support large images / had bad memory leaks when using larger photos)

note: 
------------------------------------
images may require slight modification before they are uploaded, which are listed below, 
Using mspaint the modifications needed take less than 20 seconds total. (for both images)

1) - your initial image must be named the following before you upload: content.jpg

2) - your style image must be named the following before you upload: style.jpg 

3) - initial image and style image must both be the same size! if your content photo is 400x800 in size, 
than you must also resize your desired style image to also be 400x800 in size before they are both uploaded

4) - both images must not have any extra layers, (ie transparency) so this is why I have jpg enforced now, 
png are supported however.
------------------------------------

changes/improvements/features:
-----------------------------------------------
1)- runs online, no installation or even a python enviroment required.

2)- no programming experience or code modification needed

3)- automatic upload photo button and UI. no typing needed. all done with just a couple clicks.

4)- instant preview of your modifications, (get the hang quickly of what each thing does)

5)- no image size limitation/truncation, HD images supported. 

6)- insanely fast results, especially for large images, doesnt require 500+ iterations like others

7)- ability to modify/add/subtract layers to customize style parameters.

8)- added support for 26 other neural-nets/imagenets, and all their layers. (100+ new) this has never been done by any other projects.

9)- fixxed all errors, automatically acquires & sets correct dependencies

10)- enhanced backward compatability, runtime is now also python-3 compatable  

11)- added helpful tips in code to show when to go to next step (etc)

-----------------------------------------------


for more of my projects or to add me on social media:
github:		https://github.com/400lbhacker 
facebook:	https://www.facebook.com/mimmy.tussins.1
gmail:		josepherickson135@gmail.com
---------------------------------------------

this project's base directory is located at: 
https://github.com/400lbhacker/beast-pytorch-tensorflow-neural-style-transfer/
---------------------------------------------



to instantly run online, click here to launch in google colab: 
