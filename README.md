# WP-Replace-Old-Images
This plug-in will replace old, broken, and unwanted images with a user-adjustable default image, according to date or file location.

The plug-in was written for a large site whose operators, after having been challenged by a copyright lawyer, decided to revise their copyright policy, and no longer use images whose usage rights were not fully cleared. They were left with thousands of images associated with archived posts. They did not want to delete the archives, but attempting a global search and replace for images as well as for image links presented challenges, while simply deleting the images but not the posts from the site would produce numerous load errors, which would be harmful to the site's search engine ranking, and produce a range of unwanted results when displayed on different browser. 

WordPress Replace Old Images will do nothing until the user has set the date and, if necessary, has specified the root folder containing unwanted images or designated by broken image links. Using default settings on most WordPress sites, all post images and image links for posts on or prior to the date will be replaced by links to a simple "image removed" image when the page is rendered, though the *database* will remain unaltered: The change is made when the post is loaded.   
In order to narrow or expand the range of images replaced, or to adjust the plugin, the user can also one or both strings used to identify the image links, but this plug-in is not designed for users attempting fine-grained revisions. It simply replaces images in the most popular file types - jpg, jpeg, png, and gif - in certain directories, as they appear in posts up to a certain date: That's it. 