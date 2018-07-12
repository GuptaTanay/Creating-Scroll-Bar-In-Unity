# Creating-Scroll-Bar-In-Unity
# Yayyy! You dont need any script to create a scroll bar in unity. Just follow the steps mentioined below:-<br>
1. Create a Panel from UI in GameObject .   => GameObject->UI->Panel (I named it as ScrollArea as it will be named as ScrollArea).<br>
2. Right Click on this ScrollArea and create an empty gameobject named as TextContainer and match the borders with the borders of the Panel.  =>GameObject->Create Empty. <br>
3. Right Click on TextContainer and select Scroll bar from UI and match the boders with the borders of the TextContainer. => UI->Scroll bar <br>
4.Right Click on Scroll bar and select Text from UI.  => UI->Text.<br>
5. Match the border of the Text with the border of the TextContainer except for theright one or the one where you want to place the scroll bar. <br>
6. Extend the size of the text to  greater size so that whole text gets covered in the Text.<br>
7. Now select the Scrollbar and in the inspector search for the direction in Scrollbar script. Select the direction in which your want to scroll.<br>
8. Select TextContainer and from the Inspector drad & drop the Text in the Content and check the direction of scroll(Horizontal or Vertical). <br>
9. Select Panel(ScrollArea in my case) and in the Inspector->Add Component-> Mask(script).<br>
10. Hit Play and test.<br>




<B>PS:</B> Just ask if it doesnot runs or you have a doubt.
