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
```
<html>
<head>
</head>
<body>
<p style="font-size:30px"><b>Agricultural  Search</b></p>
<a href="https://en.wikipedia.org/wiki/Rice_production_in_India#:~:text=Rice%20is%20the%20basic%20food,a%20kharif%20crop%20in%20India.">
<img style="border:5px solid black;"src="C:\Users\SEC\Pictures\rice crop.jpeg"width="300" height="400"><br>
<br>
<a href="https://farmer.gov.in/m_cropstaticswheat.aspx">
<img style="border:5px solid black;" src="C:\Users\Anu\Pictures/wheat crop.jpg"width="300" height="400"><br>
<br>
<a href="https://www.zzhuayo.com/product/mini-plough/">
    <img style="border:5px solid black;" src="C:\Users\Anu\Pictures/plough machine.png"width="300" height="400"><br>
<br>
  <a href="https://www.zzhuayo.com/product/mini-plough/">
    <img style="border:5px solid black;" src="C:\Users\Anu\Pictures/seeder machine.jpg"width="300" height="400"><br>
<br>
<a href="https://en.wikipedia.org/wiki/Fertilizer">
    <img style="border:5px solid black;" src="C:\Users\Anu\Pictures/fertilizer farm.jpg"width="300" height="400"><br>
</a>       
</body>
</html>
```

## OUTPUT
![1](https://user-images.githubusercontent.com/127816320/235507790-d38720bd-229d-402a-991a-d357f1cf7be8.png)
![2](https://user-images.githubusercontent.com/127816320/235507795-c837b85d-dc87-49a7-9476-c25595592a1a.png)
![3](https://user-images.githubusercontent.com/127816320/235507781-c132aea7-7d65-4148-bc7c-534853bf5ec3.png)
![4](https://user-images.githubusercontent.com/127816320/235507786-982e8017-0041-478d-b75c-49410dda0914.png)

## RESULT
 Images as hyperlinks is implemented successfully.
