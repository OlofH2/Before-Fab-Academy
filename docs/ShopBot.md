
#Using the ShopBot

##?

CNC stands for Computer Numerical Control

Router bits and end-mills

Raster/bitmap vs. vector

"Allow precise and repetitive control"

Speed: ips (inches per second)
Can cut 2D (x and y) and we create 2D toolpath

2.5D is usually used when making signs, so I would compare it to making a relief. Router travels by x and y axis and only uses the z-axis to go in and out of toolpaths. To do a 3D work you would have to design a 3D model. 

Ath PartWorks og Aspire

I used the program [VCarve pro](https://www.markdownguide.org/basic-syntax/) to design my sign. 

I began by filling in the size of the material I wanted to use. I wrote 382mm x 200mm. It is very important to always measure the thickness of the material because it can vary. I set the thickness to 17.5mm.

I tested how to draw a perfect rectangle by choosing the rectangle and holding the **Control** button when clicking and drawing with the mouse. I deleted it and drew an ellipse. Then I wrote a text by clicking on the big T. When the text was on the plate I resized it by using the resizing arrow, clicked on the text and dragged one corner to make it smaller. By holding the **Shift** key whilst doing that it centered and rezised it all.

To use a ruler as a measurement guide I chose the normal arrow (for the mouse), left-clicked on the ruler and held it down as I dragged it to where I wanted to have a guide line. 

By pressing fn and F12 the toolpath settings open up and by pressing fn and F11 these settings are closed and the drawing tab appears again. In 

I double clicked on the icon near **material setup** and adjusted the following:
I **set the xy origin position to bottom left** and made sure that **Use origin offset was NOT chosen**. I **set the z origin to the top of the material.**

Under **Rapid Z gaps above material** I clicked **Above material** and set **Clearance Z1** and  **Plunge Z2** to 5mm. In the video this was set to 0.5 inhces, which equals 12.7mm, but a co-teacher of mine said that it would be okay to set it to 5mm since the material I was using was even. 

Home/start position was set to: x=0, y=0 and z=20 (mm). **The z should never be set to 0.**
Then I clicked on **ok**.

The next step was to click on the outline and then select **Profile toolpath**. The **start depth** should always (usually) be set to 0. I wanted to cut the material in two passes, so the cutting depth should be around just over half of the thickness of the material in each pass. So I set the cutting depth to 9mm.





