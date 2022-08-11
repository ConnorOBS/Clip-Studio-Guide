# Connor's Clip Studio Guide
**August 11th, 2022 problem:** The image I want to use for my Github profile picture is too large, got an error message "needs to be smaller than 1mb". My photo is 1.15mb. Ughhh, so I need to shrink the size. Probably should crop out my bathroom from the background as much as possible too. 
  
    
      
      How do I resize an image in clip studio?

1. *What size canvas do I need?*  `Answer: 520 by 720 pixels, 72 DPI`

>Go to "Edit"->"Change Canvas Size" and
Go to "Edit ->"Change Image Resolution"  

Make the canvas just slightly larger than the image resolution you need, leaves room to manipulate the image. My default canvas size is a piece of standard printer paper, which is 8.5inch (width) by 11inch (height). This can be converted to pixels to get an idea of size, which in this case would be 5100 pixels by 6600 pixels. 

 >600 pixels per inch x 8.5inch= 5100 pixels  
 >600 pixels per inch x 11inch= 6600 pixels

Ok, at this point I need to know how many pixels are in a megabyte, which depends on the color mode of the picture. Oof, ok once more into the rabbit hole! 

>Got to "View"->"Color Profile"->"Preview Settings"  

Ok! My image has a RBG color mode meaning, it is a 24-bit RGB(16.7 million colors) picture, one megabyte has 468 by 720 pixels. I looked this up in a [BoldBrush](https://support.boldbrush.com/faso-images-other/difference-between-image-size-and-resolution#:~:text=How%20many%20pixels%20are%20in,1024%20pixels%20in%20one%20megabyte.) article online. Though clip studio rounded it to 520 by 720, so I'll still with that. 


 DPI of 72 is web friendly, but I found an article that referenced 300 as a standard for drawing. Since I only need to resize a photo that will appear in my online profile, I think 72 DPI is adequate.   

 Wow! All that to get set up, I had no idea picking the right canvas would be this involved when I started playing around with photos, but I got a lot of guidance from this [piplinecomics](https://www.pipelinecomics.com/learncsp/new-canvas-size/) article.  


 2. *How do I crop an image in clip studio?*  `rectangle selection area tool`  
 The official clip studio help library is extensive and very helpful, I quickly found an article on [cropping an image](https://support.clip-studio.com/en-us/faq/articles/20200023) that had simple instructions and images of the process. This makes the cropped area of the photo the canvas, so it turns out I didn't need extra space in my canvas to play with the picture.

3. *How do I save and export the image?*  `file types CLIP STUDIO FORMAT and PNG`  
All that's left to do now is save the work. I like to keep a clip studio file of everything I work on, so it is easy to come back later instead of starting from scratch. Not as essential in this case since the project is simple and small, but still a nice to have as a reference in the future. 
>Go to "File"->"Save as"-> file type "ClIP STUDIO FORMAT" and file name "cropped and resized pirate pic"  

Last step, save the resized and cropped image.
>Go to "File"->"Export(Single Layer)"-> file type "PNG" or "JPG" and file name ""cropped and resized pirate pic"  

Whether to go with JPG or PNG depends on the need, I usually go with a PNG file because the resolution will still look good if expanded. The PNG file is only slightly larger(478kb) than  the JPG file(281kb).

