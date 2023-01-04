# mkslideshow
Make a simple slideshow from a directory of images

## Usage:  
    mkslideshow [OPTIONS]...

    Options:  
    
    -d	Specify a directory of photos to use (defaults to current directory)    
    -h	Print this help and exit  
    -o	Specify output file (defaults to slideshow.mp4)  
    -p	Play the created video after completion.  
    -s	Number of seconds to display each image (default 5)  
    -r	Output framerate (defaults to 29.97 for NTSC)  
    -q	Set desired resoultion as WidthxHeight (default is 1920x1080)  
    -b	Set background color for resized images (default is Black; see https://imagemagick.org/script/color.php for options)  
    -a	Specify audio track to use  
    -l	Loop audio to fit slideshow  
