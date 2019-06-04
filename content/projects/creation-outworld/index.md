+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Creation in Outworld"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-06-04T01:42:48-07:00 #the date the file was created

    
    shortDescription = "A play on Michelangelo’s Creation of Adam."
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "LuceroCortesSpace.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++

<div class= "container">
    <div class= "girl-image">
        <img src= "LuceroCortesSpace.jpg">
    </div>
</div>

<div class="container">
        <div class= "title-display">
            <h1 class= "image-title">Creation in Outworld</h1>
        </div>
</div>

<div class= "display-text">
    <h1 class= "girl-text">
        A play on Michelangelo’s Creation of Adam, this graphic is a twist on the famous painting - but this time in space. With a “glitch” over the imminent touch, a disturbance is felt in the near-unity.
    </h1>
</div>
