+++
#The site banner has two buttons. The first one directs to the contact page. Do not alter the url or text fields of this one. If you are not using the second button for an announcement, you might want to remove the hashmark from the type line in the first button and add one to the type line of the second. This will make the first button the primary one. (A hashmark at the beginning of a line in this file will tell the browser to ignore that line. This lets you deactivate a line without actually deleting it, which is helpful if you want to be able to toggle a thing off and on.)
#
#The second button can be changed as needed, particularly for special annoucements (like a gospel meeting or an emergency). Change the URL to the name of the page (e.g. /covid, /meeting) so the button will link to the page. If the first button is designated as the primary button, add a hashmark to the beginning of the type line for the first button and remove it from the type line for the second button.
[banner]
  [[banner.button]]
      url = "/contact"
      text = "Get in touch"
      #type = "primary"

  [[banner.button]]
      url = "/covid"
      text = "COVID-19 update"
      type = "primary"

#Details for the box below the banner
#In the event of an emergency or special announcement, place a hashmark at the beginning of the "Join us for worship" title line and remove the hashmark from the other, editing the text there as needed. You cannot use line breaks in a title.
[services]
  title = "As of July 5, our meeting and class times are changing. Please click the COVID-19 update button above for information on streaming services and limited in-person gathering."
#title = "Join us for worship."
  #text = "<p>Sunday morning: Bible study @ 9am, worship @ 9:50am</p> <br> <p>Sunday evening: worship @ 6pm</p> <br> <p>Wednesday evening: Bible study @ 7:30pm</p>"
  map_location = "Downers Grove church of Christ"

[feature_icons]
  #These feature icons look best if there's an even number of them.
  enable = true

  #Accent is a colour defined in the CSS file. Choose between 1 and 5
  [[feature_icons.tile]]
    icon = "fa-hands-helping"
    icon_pack = "fas"
    accent = "1"
    title = "Who we are"
    text = "Our mission here is to acquaint our community with the New Testament church as described in the Bible. We want to lead others to become Christians and only Christians. The Bible reveals that you can belong to Christ without belonging to a human institution."
    
  [[feature_icons.tile]]
    icon = "fa-comments"
    icon_pack = "fas"
    accent = "5"
    title = "Looking for something real?"
    text = "We are a non-denominational, New Testament church that is dedicated in preserving pure Christianity as the Bible authorizes. Our worship is Simple, Educational, Spiritual, and Biblical. Please feel free to come and worship with us."

  [[feature_icons.tile]]
    icon = "fa-book-open"
    icon_pack = "fas"
    accent = "2"
    title = "Classes"
    text = "We have Bible classes for adults and for children (starting at 6 months)."

  [[feature_icons.tile]]
    icon = "fa-heartbeat"
    icon_pack = "fas"
    accent = "3"
    title = "Worship with us"
    text = "Sunday morning: Bible study @ 9am, worship @ 9:50am<br>Sunday evening: worship @ 6pm<br>Wednesday evening: Bible study @ 7:30pm"

[feature_images]
#These feature images look best if there's an even number of them.
  enable = true

  [[feature_images.tile]]
    image = "img/principles.jpg"
    title = "First Principles"
    text = "The basics of God's Word are simple yet deep. Find lessons on faith, repentance, and other elementary principles in this playlist."
    url = "https://www.youtube.com/playlist?list=PLgqm3d_wB-8qMoDhwYdePNDYODVW889GD"
    button_text = "First Principles Playlist on YouTube"

  [[feature_images.tile]]
    image = "img/living.jpg"
    title = "Christian Living"
    text = "Living by faith has its challenges, but we have a Savior who led His life as an example for us and left His Word to guide us. Find lessons on prayer, loving our neighbors, coping with struggles, and more in this playlist."
    url = "https://www.youtube.com/playlist?list=PLgqm3d_wB-8qVm4LcHcn7GY4bthd8OC3D"
    button_text = "Christian Living Playlist on YouTube"

[CTA]
  heading = "Get in touch!"
  message = "We'd love to hear from you."
+++
