# websiteMedia

Content Repository for public media files to be used in websites

## How to use it
1. upload an image to use online  
1. copy its url by opening it on github.com and copying its url. To verify if you have gto the correct url you can compare against the following pattern:  
 ```https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/path/to/the/fileLocation/fileName.extension```
    1. The url should always start with the following pattern pointing at this directory:  
```https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/```  
    1. to reflect its location in this repository the url should continue with a path 
```path/to/the/fileLocation/```   
    1. finally your url has to end with `fileName.extension` where extension must represent a browser-supported file type like `gif`, `jpg`, `jpeg`, `png`, `avi`, `mp3`, `ogg`, and [others](https://www.w3schools.com/html/html_media.asp)  
1. reference your file in markdown following this pattern: !\[briefDescription\]\(url\)

like so:  
```![Logo of the centre for humanities computing aarhus](https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/images/CHCAA/Logo.png)```

![Logo of the centre for humanities computing Aarhus](https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/images/CHCAA/Logo.png)

or as html with css style (removed by github, but working on the websites):
 
 &lt;img alt="Logo of the centre for humanities computing Aarhus" src="https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/images/CHCAA/Logo.png" style="display: block;margin-left: auto;margin-right:auto;"/&gt;  
 
<img alt="Logo of the centre for humanities computing Aarhus" src="https://raw.githubusercontent.com/centre-for-humanities-computing/websiteMedia/main/images/CHCAA/Logo.png" style="width100%!important;display: block!important;margin-left: auto!important;margin-right:auto!important;"/>
 
