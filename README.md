# LibGuides CMS Tips & Tricks

  These are some tips and tricks I use when building and updating the Gregg-Graniteville Library website (https://library.usca.edu/home). 
 
## Understanding LibGuides CMS

  ### Using Admin Groups
  
  As an admin in LibGuides, you can add groups to the CMS. Each group will correspond with a specific template or layout. You can use a group for the home page, another for your research guides, one for your website content pages, and so on. 
   
   For example, our website uses four different groups: home, subject homepage (research guides), content (side navigation), and ask a librarian (box format). The content and ask a librarian pages have very different layouts, which is why they're in different groups. If I needed to add another content page with side navigation, I would make sure to select the content group when creating a new guide. That way any of the overall code (header, footer, css/js) of that group is automatically added to the new guide.
   
   Creating and using groups makes it easier to organize your pages, ensuring they all have the same design, and utilize the same code. 
   
   #### Using the CSS/JS box within Groups
  
  ### Templates
  
  The templates available for use and adaption in LibGuides CMS correspond to the framework LibGuides has created and built their website (back-end). We can go into the templates and adapt them for our own means. The existing template for a side navigation gives us one big area for content but if you find you want to have 2 areas of content instead of one, you can add another column via adapting and saving a new template. We discovered this through a LibGuides CMS training video. These training videos are very helpful when you're starting out and aren't entirely sure how the CMS works or how to make it work for you.  
  
  ### Adding Images
  
  ### Use the correct version of Bootstrap and Font Awesome
  
   Because the back-end (creator) side of LibGuides CMS, it's important to make sure you're using the same version of both Bootstrap and Font Awesome (if using). If you use a different or the most current version on the front-end side, certain elements in the back-end will not load correctly. 
   
   For example, there are many versions of Font Awesome. The newest versions are 5.13, 5.14, and 5.15. However, LibGuides CMS uses the old version, 4.7 and in order for the icons in both the front-end and back-end to be present, we must use the old version. If you use one of the newer versions in your website, the icons in the back-end (header icons), will not load and might confuse your LibGuides creators. 
   
   Font Awesome version 4.7 https://fontawesome.com/v4.7.0/
   
   Bootstrap v3 3.7 https://getbootstrap.com/docs/3.3/getting-started/
   
   ### Using the Rich Text/HTML box
   
   When using the Rich Text/HTML box, I've found it easier to go right into the source code and build things with HTML and CSS rather than using the Rich Text box. You have more control over your content and how it looks in the source code. 
   
   
