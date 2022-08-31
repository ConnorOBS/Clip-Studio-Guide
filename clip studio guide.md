# Connor's Clip Studio Guide
**August 11th, 2022 problem:** The image I want to use for my Github profile picture is too large, got an error message "needs to be smaller than 1mb". My photo is 1.15mb. Ughhh, so I need to shrink the size. Probably should crop out my bathroom from the background as much as possible too. 
  
    
      
      How do I resize an image in clip studio?

1. *What size canvas do I need?*  `Answer: 589 by 720 pixels, 72 DPI`

>Go to "Edit"->"Change Canvas Size" and
Go to "Edit ->"Change Image Resolution"  

Make the canvas just slightly larger than the image resolution you need, leaves room to manipulate the image. My default canvas size is a piece of standard printer paper, which is 8.5inch (width) by 11inch (height). This can be converted to pixels to get an idea of size, which in this case would be 5100 pixels by 6600 pixels. 

 >600 pixels per inch x 8.5inch= 5100 pixels  
 >600 pixels per inch x 11inch= 6600 pixels

Ok, at this point I need to know how many pixels are in a megabyte, which depends on the color mode of the picture. Oof, ok once more into the rabbit hole! 

>Got to "View"->"Color Profile"->"Preview Settings"  

Ok! My image has a RGB color mode meaning, it is a 24-bit RGB(16.7 million colors) picture, one megabyte has 468 by 720 pixels. I looked this up in a [BoldBrush](https://support.boldbrush.com/faso-images-other/difference-between-image-size-and-resolution#:~:text=How%20many%20pixels%20are%20in,1024%20pixels%20in%20one%20megabyte.) article online. Though clip studio rounded it to 520 by 720, so I'll stick with that. 


 DPI of 72 is web friendly, but I found an article that referenced 300 as a standard for print media. Since I only need to resize a photo that will appear in my online profile, I think 72 DPI is adequate.   

 Wow! All that to get set up, I had no idea picking the right canvas would be this involved when I started playing around with photos, but I got a lot of guidance from this [piplinecomics](https://www.pipelinecomics.com/learncsp/new-canvas-size/) article.  


 2. *How do I crop an image in clip studio?*  `rectangle selection area tool`  
 The official clip studio help library is extensive and very helpful, I quickly found an article on [cropping an image](https://support.clip-studio.com/en-us/faq/articles/20200023) that had simple instructions and images of the process. This makes the cropped area of the photo the canvas, so it turns out I didn't need extra space in my canvas to play with the picture.

3. *How do I save and export the image?*  `file types CLIP STUDIO FORMAT and PNG`  
All that's left to do now is save the work. I like to keep a clip studio file of everything I work on, so it is easy to come back later instead of starting from scratch. Not as essential in this case since the project is simple and small, but still a nice to have as a reference in the future. 
>Go to "File"->"Save as"-> file type "ClIP STUDIO FORMAT" and file name "cropped and resized pirate pic"  

Last step, save the resized and cropped image.
>Go to "File"->"Export(Single Layer)"-> file type "PNG" or "JPG" and file name ""cropped and resized pirate pic"  

Whether to go with JPG or PNG depends on the need, I usually go with a PNG file because the resolution will still look good if expanded. The PNG file is only slightly larger(478kb) than  the JPG file(281kb).    

In retrospect I'm not sure why the final file size is 478kb instead of 1mb. At least I made it smaller and github accepted the picture for my profile avatar. Unfortunately because of the round shape of the profile, I either cut off my hat or show my bathroom toiletries in the background, so it wasn't the best picture to choose in the end. At least I learned more about the process of resizing an image and got some basic pratice playing with an image in clip studio.  

---
## EDITS and FEEDBACK
Some of my conclusions were a little off base, after I consulted someone who knows more about design and photoshop. They pointed out that in photoshop it would tell you the size of an image and what the file size would be. Clip Studio doesn't seem to list those together, so I have to check the file size after I've exported. An extra step and the reason I got confused on the definitions of resolution and image size. 

Resolution would be 72 dpi or ppi and 600 dpi or ppi. 
To convert between pixels and inches for how we want to think about resolution, must first decide which standard to use for dots per inch or pixels per inch, which are interchangable terms. 

72 dpi is a low resolution, appropriate for small web images.
300 dpi is the standard resolution for printing.

The size of the image, in terms of height and width, is independent of the dpi. So when I am trying to make a decision about how big an image should be, it is helpful to think in terms of inches in real life. For example, if I wanted a little profile picture, maybe 3in by 4in portrait would be appropriate.

Then depending on what dpi I choose, the resolution of that 3 by 4 inch image will be lower (72dpi) or higher (300dpi).

Clip Studio does not display the original image's dpi for some reason....either that or I don't know where to find it. 

On the original file
>go to "properties" -> "Details"

This provides the dimensions (1980 width x 2640 height in pixels) and the resolution (72 dpi), bit depth (24), and color representation (sRGB).

I can convert the width and height to inches, to get a better sense of how big the image actually is, by using the 72 dpi as my conversion unit. DPI stands for "Dot Per Inch" so the math is as follows.

> 1980 pixels/ 72 dots per inch= 27.5 inches  
> 2640 pixels/ 72 dots per inch= 36.67 inches  
> so the image is 27.5 by 36.67 inches. 

That's really big! Especially since the resolution was set to 72 dpi, which is very low. So the image was taking up 1.15mb of file space because it was giant, yet low resolution. I should probably change the resolution on my camera phone to slightly higher, maybe I've been short changing my photos by working in low resolution for everything. 
---  
### August 27th, 2022

Started on a new drawing, actually an old drawing that is getting an upgrade.
A line drawing that I did one fall while I was stressed out from evolution class. 
I had just watched "The Book of Kells" animated movie, so the patterns are inspired from
linework and shapes in the animation.

My origianl drawing is the first layer, to help with tracing. I reduced opaqueness to 51%.   
Found a clip studio paint tips page that clearly explained the [difference between raster and vector layers.](https://tips.clip-studio.com/en-us/articles/532)   

 ***Not sure why this relative file path isn't working. Doesn't work with primary source path, and changing the backslash to forward slashes doesn't change anything. Can I save it to a repository on VSC itself to access locally? Do I need an extension? What preview extension am I using? How do I look that up on VSC?***

![drawing](.../markdown vsc files/jake_forest_original.jpg)


Anyway, will use a vector layer to do the linework using the figure tool and subtools.
Go to window->tool or subtool or tool property. Use brush size 10 for now, can change later since it is a vector layer. Use tools->operations->subtools for operations->object subtool to select the points and move to somewhere else.   
 Found another article that specifically talks about how to use all the cool features for [vector
line drawings in clip studio paint.](https://blog.yarsalabs.com/vector-drawing-in-clip-studio-paint/) There are features unique to Clip Studio Paint that Photoshop doesn't have, like drawing with brush tools in vector layers.   

I'm beginning to see how Clip Studio Paint is built for illustration, not for photo editing.  


Next I want to create two symmetric circles overlaping like a venn diagram. So I made a circle, lasso tool around it, then copy and pasted it, which made a new layer, then choose the scale/transform button on bar that pops up, moved it over then went to lasso properties and flipped it horizontally. Or skip moving and just flip horizontally.
I learned this manipulation from a short video on youtube, that explains how to [copy, paste, and flip vector lines or objects.](https://www.youtube.com/watch?v=VDSoP65pgtM)

Continue using this method with different layers, so I can start isolating the main line structures and shapes. Mostly using the figure curve subtool. Pulled down a ruler grid line to check my symmetry. Can already see how my original sturcture was not symmetrical at the bottom right side. 


![first screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  

![second screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  

![third screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  

![fourth screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  

![fifth screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  

![sixth screenshot](E:/coding/markdown vsc files/clip_studio_guide images)  


August 28th, 2022

Jake the Face in the Forest continues. Went back into individual layer sets to erase vector lines that overlapped too much. Took a few more screenshots to show the basic structure is now done. I don't want to permanently collapse all the layers, instead I'll figure out if I can temporarly collapse the vector layers, or just export this as one layer to start playing with. 
