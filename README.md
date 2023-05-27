# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```<html>
<body>
<h1>Horticulture</h1>
<a href="https://www.google.com/search?q=horticulture&rlz=1C1CHBD_enIN1033IN1033&oq=hort&aqs=chrome.0.69i59j69i57j35i39j0i20i263i512j0i433i512j0i131i433i457i512j0i402i650l2j46i199i465i512j0i20i263i512.2359j0j15&sourceid=chrome&ie=UTF-8&bshm=lcbsc/1#imgrc=0TZj9Hwe3IATXM">
<img src="11.webp" height="300" width="300">
<br>
<br>
<h1>Irrigation</h1>
<a href="https://www.google.com/search?q=Irrigation&rlz=1C1CHBD_enIN1033IN1033&sxsrf=APwXEdfNFTBBkNpNV4RW6zsFFbhEG2Druw%3A1685214047835&ei=X1NyZKrSMvHiseMP24KJoAY&ved=0ahUKEwjq_cPFl5b_AhVxcWwGHVtBAmQQ4dUDCA8&uact=5&oq=Irrigation&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIHCCMQigUQJzIKCAAQgAQQFBCHAjIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOg8IABCKBRDqAhC0AhBDGAE6CwguEIAEELEDEIMBOgsIABCABBCxAxCDAToRCC4QgAQQsQMQgwEQxwEQ0QM6EAgAEIAEEBQQhwIQsQMQgwFKBAhBGABQjSRY4zZg7zxoAXABeACAAbYCiAHPDpIBBzAuNi4zLjGYAQCgAQGwARTAAQHaAQYIARABGAE&sclient=gws-wiz-serp">
<img src="12.jpg" height="300" width="300">
<br>
<br>
<h1>Apiculture</h1>
<a href="https://www.google.com/search?q=apiculture&rlz=1C1CHBD_enIN1033IN1033&sxsrf=APwXEde1u_MBJ99T0JhobIh8N4CuOOUfCA%3A1685214223308&ei=D1RyZKq9EtmeseMPhJu48A4&ved=0ahUKEwjqgJqZmJb_AhVZT2wGHYQNDu4Q4dUDCA8&uact=5&oq=apiculture&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIHCCMQigUQJzIKCAAQgAQQFBCHAjIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOg8IABCKBRDqAhC0AhBDGAE6BAgjECc6BwgAEIoFEEM6EQguEIAEELEDEIMBEMcBENEDOgsIABCABBCxAxCDAToICAAQgAQQsQM6CwgAEIoFELEDEIMBOgsILhCABBDHARDRAzoOCC4QgAQQsQMQxwEQ0QNKBAhBGABQ5whYqB5gzCZoAXABeACAAZoCiAHkDZIBBTAuNy4zmAEAoAEBsAEUwAEB2gEGCAEQARgB&sclient=gws-wiz-serp">
<img src="13.jpg" width="300" height="300">
<br>
<br>
<h1>Organic Farming</h1>
<a href="https://www.google.com/search?q=organic+farming&rlz=1C1CHBD_enIN1033IN1033&sxsrf=APwXEdePo09VBYUC17vtisbR69vf_FlPdw%3A1685214444787&ei=7FRyZLHRL_602roPq-CzyAg&ved=0ahUKEwix9-eCmZb_AhV-mlYBHSvwDIkQ4dUDCA8&uact=5&oq=organic+farming&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIPCAAQgAQQFBCHAhBGEP8BMggIABCABBCxAzIFCAAQgAQyBQgAEIAEMgsIABCABBCxAxCDATIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOg8IABCKBRDqAhC0AhBDGAE6BwgjEIoFECc6BwgAEIoFEEM6DgguEIAEELEDEMcBENEDOhEILhCABBCxAxCDARDHARDRAzoKCAAQigUQsQMQQzoRCC4QgAQQsQMQxwEQ0QMQ1AI6BQguEIAEOgoIABCABBAUEIcCOggIABCKBRCxAzoKCAAQgAQQsQMQCjoHCAAQgAQQCjoHCCMQsQIQJzoLCAAQigUQsQMQgwE6DQgAEIAEELEDEIMBEAo6CwguEIAEEMcBEK8BOg0ILhCABBDHARCvARAKSgQIQRgAUPsJWLajAmCiuQJoBXABeACAAaYEiAHwNJIBCzAuMy40LjUuNC4zmAEAoAEBsAEUwAEB2gEGCAEQARgB&sclient=gws-wiz-serp">
<img src="14.jpg" width="300" height="300">
<br>
<br>
<h1>Harvest</h1>
<a href="https://www.google.com/search?q=organic+farming&rlz=1C1CHBD_enIN1033IN1033&sxsrf=APwXEdePo09VBYUC17vtisbR69vf_FlPdw%3A1685214444787&ei=7FRyZLHRL_602roPq-CzyAg&ved=0ahUKEwix9-eCmZb_AhV-mlYBHSvwDIkQ4dUDCA8&uact=5&oq=organic+farming&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIPCAAQgAQQFBCHAhBGEP8BMggIABCABBCxAzIFCAAQgAQyBQgAEIAEMgsIABCABBCxAxCDATIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOg8IABCKBRDqAhC0AhBDGAE6BwgjEIoFECc6BwgAEIoFEEM6DgguEIAEELEDEMcBENEDOhEILhCABBCxAxCDARDHARDRAzoKCAAQigUQsQMQQzoRCC4QgAQQsQMQxwEQ0QMQ1AI6BQguEIAEOgoIABCABBAUEIcCOggIABCKBRCxAzoKCAAQgAQQsQMQCjoHCAAQgAQQCjoHCCMQsQIQJzoLCAAQigUQsQMQgwE6DQgAEIAEELEDEIMBEAo6CwguEIAEEMcBEK8BOg0ILhCABBDHARCvARAKSgQIQRgAUPsJWLajAmCiuQJoBXABeACAAaYEiAHwNJIBCzAuMy40LjUuNC4zmAEAoAEBsAEUwAEB2gEGCAEQARgB&sclient=gws-wiz-serp">
<img src="15.jpg" width="300" height="300">
</body>
</html>
```


## OUTPUT
![Ex51](https://github.com/Thennunagaraj/Ex04_Web-Design/assets/128386061/645f0a5e-ec33-47bb-bf1a-042c9b22b8b0)
![EX52](https://github.com/Thennunagaraj/Ex04_Web-Design/assets/128386061/50077e8c-e4bb-471e-be15-9c8cf444ab99)


## RESULT
 Images as hyperlinks is implemented successfully.
