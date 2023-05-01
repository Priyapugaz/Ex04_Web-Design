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
<html>
<head>
</head>

<body>

    <p style="font-size:30px"><b>Agricultural  Search</b></p>
    
    <a href="https://www.google.com/search?q=rice+crop&rlz=1C1RXQR_enIN1029IN1029&oq=rice+crop&aqs=chrome.0.69i59j0i512j0i67i650j0i512l5j0i67i650j0i512.2931j0j15&sourceid=chrome&ie=UTF-8">
        
<img style="border:5px solid black;"src="C:\Users\User\Pictures\rice crop.jpg"width="300" height="400"><br>
<br>


    <a href="https://www.google.com/search?q=wheat+crop+&bih=526&biw=1093&rlz=1C1RXQR_enIN1029IN1029&hl=en&sxsrf=APwXEdffn7ccIgWcE2Lesx6_CBA0YtO86w%3A1682952442356&ei=-tBPZJOuFdjh4-EPsdmW-A0&ved=0ahUKEwiTk4C0rtT-AhXY8DgGHbGsBd8Q4dUDCA8&uact=5&oq=wheat+crop+&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIICAAQigUQkQIyCAgAEIoFEJECMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6BwgjEOoCECc6DwgAEIoFEOoCELQCEEMYAToSCC4QigUQyAMQ6gIQtAIQQxgCOgQIIxAnOgcIIxCKBRAnOgcIABCKBRBDOgoILhCKBRDUAhBDOgsIABCABBCxAxCDAToICAAQgAQQsQM6DQgAEIAEELEDEIMBEAo6CggAEIoFELEDEEM6CggAEIAEEBQQhwJKBAhBGABQrgNYgBNgtxdoAXABeACAAY8BiAG8CZIBAzMuOJgBAKABAbABE8ABAdoBBggBEAEYAdoBBggCEAEYCA&sclient=gws-wiz-serp">
<img style="border:5px solid black;" src="C:\Users\User\Pictures\wheat crop.jpg"width="300" height="400"><br>
<br>
<a href="https://www.google.com/search?q=plough+machine&rlz=1C1RXQR_enIN1029IN1029&sxsrf=APwXEddZyAZzM5zILryIQAE08jfsOkGdzg%3A1682961070621&ei=rvJPZNrCJZmu2roP57ijgAQ&ved=0ahUKEwja0aPGztT-AhUZl1YBHWfcCEAQ4dUDCA8&uact=5&oq=plough+machine&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIHCCMQigUQJzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgYIABAWEB46CggAEEcQ1gQQsAM6BwgjEOoCECc6EQgAEIoFEOoCELQCEAoQQxgBOg8IABCKBRDqAhC0AhBDGAE6CAgAEIoFEJECOgsILhCDARCxAxCKBToLCAAQgAQQsQMQgwE6CwguEIAEELEDEIMBOgUILhCABDoHCAAQigUQQzoICAAQgAQQsQM6CggAEIoFELEDEEM6CggAEIAEEBQQhwJKBAhBGABQhqMsWOC3LGC6vixoA3ABeACAAXmIAckLkgEDNS45mAEAoAEBsAEUyAEIwAEB2gEGCAEQARgB&sclient=gws-wiz-serp">
    <img style="border:5px solid black;" src="C:\Users\User\Pictures\plough machine.jpg"width="300" height="400"><br>
<br>
 <a href="https://www.google.com/search?q=seeder+machine&rlz=1C1RXQR_enIN1029IN1029&sxsrf=APwXEddNLgKMpJI3i9J-zQadL3u3WwOf1Q%3A1682961931269&ei=C_ZPZOv8D9zN2roPibmKoAU&ved=0ahUKEwirrtXg0dT-AhXcplYBHYmcAlQQ4dUDCA8&uact=5&oq=seeder+machine&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIHCCMQigUQJzIICAAQigUQkQIyCggAEIAEEBQQhwIyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEOgcIIxDqAhAnOg8IABCKBRDqAhC0AhBDGAE6BAgjECc6BwgAEIoFEEM6CggAEIoFELEDEEM6CgguEIoFELEDEEM6CQgAEIoFEAoQQzoHCAAQgAQQCjoNCAAQgAQQsQMQgwEQCkoECEEYAFDmBljgHGDmH2gBcAF4AIABngGIAfsLkgEENC4xMJgBAKABAbABE8ABAdoBBggBEAEYAQ&sclient=gws-wiz-serp">
    <img style="border:5px solid black;" src="C:\Users\User\Pictures\seeder machine.jpg"width="300" height="400"><br>
<br>
<a href="https://www.google.com/search?q=fertilizer+farm&rlz=1C1RXQR_enIN1029IN1029&sxsrf=APwXEdfc4m3shHYhb7onga3MWyVegLuzbQ%3A1682962102264&ei=tvZPZPnQD9ux2roP-M6FgA4&oq=fer&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQARgAMgcIIxCKBRAnMgQIIxAnMggIABCKBRCRAjIHCAAQigUQQzIICAAQigUQkQIyBwgAEIoFEEMyCggAEIoFELEDEEMyBwgAEIoFEEMyCggAEIAEEBQQhwIyCAgAEIAEELEDOgcIIxDqAhAnOhEIABCKBRDqAhC0AhAKEEMYAToPCAAQigUQ6gIQtAIQQxgBOhEILhCABBCxAxCDARDHARDRAzoRCC4QgwEQxwEQsQMQ0QMQgAQ6BQguEIAEOhAILhCKBRCxAxDHARDRAxBDOgUIABCABDoOCC4QgAQQsQMQxwEQ0QNKBAhBGABQyQFY4gNgrBFoAXABeACAAY4BiAHlApIBAzAuM5gBAKABAbABFMABAdoBBggBEAEYAQ&sclient=gws-wiz-serp">
    <img style="border:5px solid black;" src="C:\Users\User\Pictures/fertilizer farm.jpg"width="300" height="400"><br>


</a>  



    
</a>       
</body>
</html>

## OUTPUT


## RESULT
 Images as hyperlinks is implemented successfully.
