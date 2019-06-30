# Responsive-Portfolio
Updated version of my Basic-Portfolio using media responsiveness .




Mostly got old code to scale. I ran into 2 issues, both of which I believe requires me to adjust HTML architecture.

1st and biggest issue. when scaling tothe  640 screensize. I couldn't get the nav link text themselves to rise up to the white banner space. I tried messing with margins, and adjusting z-indexes, however due to layer spacing (maybe need to experiment more with the " its inherited "float right" attribute), If that's not the issue, I think I need to adjust the div container sections.

second issue is again on the 640 screensize, the white banner gets cut off on the top left side of the screen. I have the width set to 640 px (and inspector is showing it IS indeed taking up 640 px) however it's offset a little to the right. Might again be due to div container differences