+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Aggie NOW Tries - Nerf Club"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-06-04T01:43:12-07:00 #the date the file was created

    
    shortDescription = "A student organization based on the UC Davis campus."
    projectVideo = "Wk1LAv0pM_Q"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "youtube"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "davis_nerf.jpg"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++
<div class="container">
        <div class= "title-display-video">
            <h1 class= "image-title">Aggie NOW Tries - Nerf Club</h1>
        </div>
</div>

<div class= "display-text-video">
    <h1 class= "girl-text">
        This video was made for the YouTube series Aggie NOW Tries. Aggie NOW Tries seeks events and clubs in and around Davis that involves UCD students. For this particular episode, I edited all footage taken of the Davis Nerf Club. Meant to inform and interest students, this video was shared all over Aggie Studio’s social platforms and the Davis Nerf Club’s Facebook page.
    </h1>
</div>

