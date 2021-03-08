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
  
  First, you must download the images to the Image Manager located under the Content navigation. Next, you want to upload your image. Please make sure your image isn't too big or it will increase your website's loading time. The last thing we want our users to do is wait to access our content. LibGuides includes the following information before the upload button "UPLOAD AN IMAGE - Supported formats include JPG, JPEG, GIF, PNG, and ICO up to 5MB in size." Once you've successfully uploaded your picture, you'll find it located within your folder. You can add multiple folders and organize your pictures to suit your needs. 
  
  
  
  ### Use the correct version of Bootstrap and Font Awesome
  
   Because the back-end (creator) side of LibGuides CMS, it's important to make sure you're using the same version of both Bootstrap and Font Awesome (if using). If you use a different or the most current version on the front-end side, certain elements in the back-end will not load correctly. 
   
   For example, there are many versions of Font Awesome. The newest versions are 5.13, 5.14, and 5.15. However, LibGuides CMS uses the old version, 4.7 and in order for the icons in both the front-end and back-end to be present, we must use the old version. If you use one of the newer versions in your website, the icons in the back-end (header icons), will not load and might confuse your LibGuides creators. 
   
   Font Awesome version 4.7 https://fontawesome.com/v4.7.0/
   
   Bootstrap v3 3.7 https://getbootstrap.com/docs/3.3/getting-started/
   
   ### Using the Rich Text/HTML box
   
   When using the Rich Text/HTML box, I've found it easier to go right into the source code and build things with HTML and CSS rather than using the Rich Text box. You have more control over your content and how it looks in the source code. By writing out your content in HTML and CSS via the source code, you're able to have more control over each individual element witin the source code box. This give us the ability to add more style than we'd be able to by using the guide level CSS/JS. Also, the guide level CSS/JS only allows a limited number of characters. This is not the case with the source code box. 
   
   
