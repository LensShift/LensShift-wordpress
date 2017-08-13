# LensShift-wordpress
notes for the "development" wordpress page created during the RHoK Hackathon
Plug-ins installed
  Post Content Shortcodes: to allow shortcodes to aggregate multipl mini-courses (to render a post in another post)
  Post Grid: no changes made to settings. Only edits made were optical changes like background choices
  Master Slider: basic testing. Needs adjustments to make it look like how we want the guides to look
Site Structure
  Three categories for posts: Library item, Mini Course, Guide
    Library item is a post with media type (images, videos, etc.)
      Missing fields need to be added
      Missing: Embedded/iFrame window
    Mini Course is a post that aggregate posts using post ID shortcodes
    Guide is a post that has the master slider shortcode
Post Grid Customizing
  Use 'Query Post' to filter which categories and posts will be rendered in a grid
Menu created with various Pages to appear in the header/navbar
