# How to update the website

**If you are updating a page on the website,** go to dgcoc.org/admin. You will be prompted to log in. Click on the Google button and log in using the dgcocit address. (If you don't have those login credentials, talk to Dave Malcomson, Peter Jetton, or Anna Jetton.) From there you can edit all blog posts and all pages EXCEPT the front page of the website. You can also add blog posts and pages. All fields are required except for tags, but you are strongly encouraged to tag blog posts to make it easier to sort and find posts.

This admin page can use Rich Text or Markdown code. For Rich Text, use the buttons to format your text. (You do not need to do anything to create the popup links for Bible references. Those are generated automatically when you reference a verse as Book Ch:Vs. The book names can be abbreviated. If the verse reference is not underlined on the published page, check your spelling and chapter/verse numbers. You might also try a different abbreviation for the book name.)

Markdown code is an easy and versatile option for formatting text. You can read more about it at https://daringfireball.net/projects/markdown/syntax.

**If you are updating the responsibilities page,** go to https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/. You should have the responsibilities charts in a spreadsheet file. Copy the fields one section (Sunday mornings, Wednesday evenings, etc) and paste it into the text field on that site. It will generate the Markdown code you need for the website.

You can update the responsibilities page in the admin section described at the top. In the Body section on the left side of the page, toggle the switch from Rich Text to Markdown. Paste the Markdown code you generated with the link above in the Body field. Repeat this with the other sections of the page. Change the page title to the correct month.

**If you are updating the main page,** you must do this in Github. In the "sitedeploy" repository, open the content folder and select the file index.md. (This is preceded by an underscore that doesn't render correctly in this file.) In the bar above the large text field, click the pencil icon on the far right side. This opens the editor.

There are not many things you will want to change in this file, mostly the text field under the banner and the buttons on the banner. The index file has instructions for updating these. If you want to remove something, I STRONGLY RECOMMEND placing a hashmark at the beginning of the line rather than deleting it outright. This tells the browser to ignore the line. Using the hashmark to deactivate a line of code makes it much easier to revert to the previous version.

(Also, please note that lines are numbered, and a single line can appear to be more than one. All the paragraphs in this document have a single line number and are considered a single line in the document. So to hide a paragraph in this document, you would only need one hashmark at the beginning of the paragraph.)

**If you are updating the menu,** please be sure you really want to do this. You must do this in Github. In the "sitedeploy" repository, select the file config.toml. In the bar above the large text field, click the pencil icon on the far right side. This opens the editor. Most of this file is settings for the menu. A menu item looks like this:

    [[menu.main]]
      name = "Leaders"
      parent = "About"
      url = "/leaders"
      weight = 2
    
Copy one of these blocks and paste a new copy where you want the new item to appear. The name field is what will appear in the menu. The parent field is which submenu the item appears in. (If your new item is a submenu or a top-level item, delete the parent line or add a hashmark to the beginning of the line.) The url field is the link for the page. (Remove or hashmark this field if this is a submenu heading and does not need to link to a page.) The weight field determines the order of items in the menu. If you are adding this to the middle of a menu, be sure you add one to each of the other menu items that will now follow it.
 
I STRONGLY RECOMMEND not deleting these. Add hashmarks before each line of a menu item if you want to disable it. One menu item block has the note SPECIAL EVENT after the menu.main line. If you want to add a link to a page for a special announcement, remove the hashmarks at the beginning of lines for that code block (leave the hashmark with the SPECIAL EVENT note) to reactivate it and change the name and URL as needed. Add the hashmarks back to the beginning of each line of the code block to deactivate it when you no longer need the special announcement.
