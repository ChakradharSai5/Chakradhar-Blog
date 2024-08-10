About Github:
- well, it is owned by Microsoft and allows a maximum of 100GB storage for codes, related documents, images and facilities
- but recommends about 1GB usage
- as we have few pdfs and many images and that too small size, so I don't think it would cross more than 1GB

 So think my Approach would be 
        - to write and embed all pdfs and images completely offline, and simply sync them to repository for web access and sync them with syncthing for phone and tablet access
        - what this does is 
            1. this will have all pdfs and images to repository and can be accessed with no issue, except for some minor css issue that can be taken care of with time
            2. as this shall create exact vault inside phone and tablet, it shall take a good amount of space in phone & tablet, which if less than 1 GB, I guess, is absolutely fine.
            3. Point to note that, sometimes if a note requires a drawing to be shown in middle, what we will do is we create a excalidraw file along with all pdfs and images folder and SVG file of that particular file shall be embeeded in this note file, (SVG file gets created automatically with )
    NOTE: it may be noted that, the pdfs and images MIGHT or MIGHT NOT be from google drive/one drive/or any other local/cloud storages I have and google photos or some other, this vault shall have duplicated copy of that - that is this vault shall NOT be accesing the file from that cloud through iframe link, this shall ensure simplicity in and removes clumsiness.
-
### For excalidraw drawing
- The problem:
    The excalidraw drawings that are easy to draw and view in Obsidian, cannot be accesed to github Blog, as github blog don't have way to render the code of Excalidraw,
My approach would be
    1.the only way that can be seen in blog is if it is an image, and we have an option in excalidraw plugin to make this whatever drawing we create shall be made to SVG or PNG file and auto updates when we change drawing
    2. Now what we do is we create an excalidaw file, that auto creates an SVG file(we chose for only SVG File,'cause SVG file has more clarity) beside the drawing file
    3. Now we create another note with same name adding "SVG File", and embed the SVG file of the drawing
     this is good because if we want to make any changes in drawing, we can make in drawing file and auto updates in SVG file, and the same can be viewed in blog.
    4. this excalidraw we are not keeping with "z-All pdfs & images" because those are the drawings that are created to be kept as small part of a larger text heavy file, these are the drawings are that are "drawing heavy less text" type
    5. So this comes to us, in making choice of whenever you are need to create an excalidraw, think do you need it as part of another text file, or this itself gonna have requried text, based on that you have to place it
