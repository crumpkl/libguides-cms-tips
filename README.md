# LibGuides CMS Tips & Tricks

  These are some tips and tricks I found useful when building and updating the Gregg-Graniteville Library website (https://library.usca.edu/home). 
 
## Understanding LibGuides CMS

  ### Using Admin Groups
  
  As an admin in LibGuides, you can add groups to the CMS. Each group will correspond with a specific template or layout. You can use a group for the home page, another for your research guides, one for your website content pages, and so on. 
   
   For example, our website uses four different groups: home, subject homepage (research guides), content (side navigation), and ask a librarian (box format). The content and ask a librarian pages have very different layouts, which is why they're in different groups. If I needed to add another content page with side navigation, I would make sure to select the content group when creating a new guide. That way any of the overall code (header, footer, css/js) of that group is automatically added to the new guide.
   
   Creating and using groups makes it easier to organize your pages, ensuring they all have the same design and utilize the same code. The groups also help with making sure specific templates are for particular groups. LibGuides CMS doesn't make a lot of things easy but the organization of the different pages with different templates within groups helps to streamline editing and updating your code when it comes to the header, footer, and overall CSS/JS for all the pages within the specific group. 
   
   #### Using the Header/Footer/Tab/Boxes within Groups
   
   The Header/Footer/Tab/Boxes area within the Groups gives us the ability to write or copy/paste the HTML code necessary to build the header and footer for the particular pages housed within the specific group and streamline the appropriate styles for the tab/box options for the group. The header and footer boxes are nice because we know exactly where the header and footer code is located for each individual group. There is no searching around for the code when making changes for each group because all of the code is in the same area. This also rings true when applying CSS/JS to the site at a specific group level. 
   
   #### Using the CSS/JS box within Groups
   
   When using the CSS/JS box within the admin groups allows you to change the CSS/JS across all the pages within the Groups. This is helpful when building and making changes to the header and footer across the entire website (different groups included). By using the group wide CSS/JS box instead of the guide level CSS/JS box ensures consistency within the design and makes it easier in the long run when applying changes to the code when it comes to updating the look of the website. Being able to locate the code and make group wide changes will save time when completing minor changes and updates that come with maintaining a website. 
  
  ### Templates
  
  The templates available for use and adaption in LibGuides CMS correspond to the framework LibGuides has created and built their website (back-end). We can go into the templates and adapt them for our own means. The existing template for a side navigation gives us one big area for content but if you find you want to have two areas of content instead of one, you can add another column via adapting and saving a new template. We discovered this through a LibGuides CMS training video. These training videos are very helpful when you're starting out and aren't entirely sure how the CMS works or how to make it work for you.  
  
  ### Adding Images
  
  Adding images within LibGuides CMS requires a few steps and depending on how, what, and where you plan to use the images can be even more tricky. 
  
  First, you must download the images to the Image Manager located under the Content navigation. Next, you want to upload your image. Please make sure your image isn't too big or it will increase your website's loading time. The last thing we want our users to do is wait to access our content. LibGuides includes the following information before the upload button "UPLOAD AN IMAGE - Supported formats include JPG, JPEG, GIF, PNG, and ICO up to 5MB in size." Once you've successfully uploaded your image, you'll find it located within your folder. You can add multiple folders and organize your images to suit your needs. 
  
  After you've successfully downloaded your image, you'll notice there are two icons under the image. One is a chain (click to view the image URL - this will come in handy when adding the image to HTML code) and an X (to delete the image). The chain icon is the most important, especially if you plan to add your images via HTML box and not the widget box. However, if you plan to use the Gallery box (more on that later) on any of your pages, you will notice a different icon to add images. 
  
  #### Gallery Box
  
  Adding images to the Gallery box is simple and straightfoward. After you'd added the gallery box to your guide, click on the cog in the uppper right and side to add panels to your new box. 
  
  When adding an image, you will be pulling images from the Image manager, so make sure the image you want is already uploaded to the Image manager. Next, click on the Open Image Manager to find and add your desired image. It's important to note that when adding an image, you have two options, you can click on the picture icon to reuse the image or you can click on the chain icon to copy/paste the image URL into the slide image URL box on the gallery prompted box to add an image. Both will add the selected image so it's your choice. 
  
  Below the area where you can add your image is where you can add the link URL, image alt text, slide title, and slide details. 
  
  ### Use the correct version of Bootstrap and Font Awesome
  
   Because the back-end (creator) side of LibGuides CMS, it's important to make sure you're using the same version of both Bootstrap and Font Awesome (if using). If you use a different or the most current version on the front-end side, certain elements in the back-end will not load correctly. 
   
   For example, there are many versions of Font Awesome. The newest versions are 5.13, 5.14, and 5.15. However, LibGuides CMS uses the old version, 4.7 and in order for the icons in both the front-end and back-end to be present, we must use the old version. If you use one of the newer versions in your website, the icons in the back-end (header icons), will not load and might confuse your LibGuides creators. 
   
   Font Awesome version 4.7 https://fontawesome.com/v4.7.0/
   
   Bootstrap v3 3.7 https://getbootstrap.com/docs/3.3/getting-started/
   
   ### Using the Rich Text/HTML box
   
   When using the Rich Text/HTML box, I've found it easier to go right into the source code and build things with HTML and CSS rather than using the Rich Text box. When writing your content in HTML and CSS via the source code, you're able to have more control over each individual element within the source code box. This give us the ability to add more style than we'd be able to by using the guide level CSS/JS. Also, the guide level CSS/JS only allows a limited number of characters (2000 characters). However, this is not the case with the source code box. 
   
   The source code (HTML section) allows you to add CSS with the style tags. This is an easy and great to add individual style to tabbed and standard boxes. You can adjust any spacing concerns you might run across when adding content via the rich text/widget box. For example, when our content creators finished adding their content via the rich text component, I went into the source code (HTML) and rewrote the content using the appropriate HTML/CSS code. This allowed our content to render correctly and consistently on all of our pages. 
   
   
   ##Designing for LibGuides CMS
   
   
