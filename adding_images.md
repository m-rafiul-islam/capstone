# How to Add an Image in Markdown in Jupyter/GitHub
You can display images in GitHub markdown files in two primary ways:
 - Using Markdown syntax (simple and clean)
 - Using HTML tags (more flexible and customizable)

## Markdown Syntax
```markdown
![alt text](https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg) 
```
Note: Markdown syntax is clean and easy, but you can't customize the size or style of the image directly.
![alt text](https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg) 



<h2>html syntax</h2> 
The following is the basic html system for attaching an image. 
```markdown 
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg"> 
```
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg"> 

You can specify the width and height of an image in pixels. This gives you precise control over the image's dimensions. Also, Alt text is a crucial element for making web content more accessible and understandable. 
```markdown 
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg" alt="This isn an image for samusa" width="300" height="200"> 
```
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg" alt="This isn an image for samusa" width="300" height="200"> 


You can also use percentage values to make the image's size relative to its parent container. It's helpful for mobile-friendly or responsive designs. 
```markdown
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg" alt="Samusa image" width="50%" height="Auto">   
```
<img src="https://github.com/m-rafiul-islam/capstone/blob/main/images/samusasingara.jpeg" alt="Samusa image" width="50%" height="Auto">   


## Take a screenshoot and paste directy 
You can take a screenshoot and paste into a markdown file directly. It will automatically generate necesary code. 
```markdown
<img width="362" alt="image" src="https://github.com/user-attachments/assets/ff296e98-3afb-489d-b205-4610120a84ae" />
```
<img width="362" alt="image" src="https://github.com/user-attachments/assets/ff296e98-3afb-489d-b205-4610120a84ae" />


## Markdown vs. Html 
<img width="467" alt="image" src="https://github.com/user-attachments/assets/2cd219e2-10ec-4cc7-b46d-b236a0f754bb" />




