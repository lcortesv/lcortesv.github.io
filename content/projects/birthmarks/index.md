+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Birthmarks"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-21T10:46:56-07:00 #the date the file was created

    
    shortDescription = "Thoughts on a birthmark myth."
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html
    projectImage = "thegirlwf_2.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 
    #<div class="container">
        #<div class= "title-display">
            #<h1 class= "image-title">Birthmarks</h1>
        #</div>
    #</div>

+++

<div class= "container">
    <div class= "girl-image">
        <img src= "thegirlwf_2.jpg">
    </div>
</div>

<div class="container">
        <div class= "title-display">
            <h1 class= "image-title">Birthmarks</h1>
        </div>
</div>

<div class= "display-text">
    <h1 class= "girl-text">
        A birthmark indicates how you died in your previous life. Or so, that is how my mother told me the myth goes. In Spanish, a birthmark is called a lunar or a mancha (a stain). Like the impact marks on the moon or a stain on a white shirt, this piece wonders about the past behind each mark.
    </h1>
</div>
