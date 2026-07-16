
# **Site Philosophy**
This site will be hosted static on Github pages. All content should be easily ediable using Pages CMS with markdown files for content. Also include a global settings md to control the site-wide elements below. 
"Build a headless site architecture that avoids a static site generator. Content is stored as individual Markdown files in a `/content` folder. A GitHub Action should trigger on every push to parse these files and aggregate their front matter and body into a single `articles.json` file in the `/data` directory. The frontend should be a single-page application (SPA) that fetches this JSON and dynamically renders articles based on the URL slug using JavaScript."
# **Site-wide Elements**
# Colors
od-yellow = #ffae00
od-white = #e9e9e9
od-lightGrey = #7b7b7b
od-darkGrey = #2c2c2c

# Cursor
Cursor is an arrow pointer with no tail, that is od-yellow
# Text Fonts
kingthings = in fonts folder stored as “kingthings.woff2”
# Text Styles
header = kingthings, od-yellow
body01 = kingthings, od-white
body02 = comforta, od-white

# Other
textLogo = “One Day”, header styling

# Buttons
**Buton01** 
	deafaultState = fontTK, od-lightGrey, underlined
	onHover = od-yellow highlighting animation, should look like a highliter moving right until there is od-yellow box around text. During animation text outside of highlight should be od-lightGrey, inside highlight text is black.
**Button02** 
	defaultState = fontTK,  od-lightGrey
	onHover = text fades to od-yellow

# Components
tile = a square tile for displaying an item (such as an article). It has a header, description, date, ac. It is portrait oriented with an image in upper 2 thirds and grey text area in lower third. 
tileRow = A scrollable row of tiles 
tileGrid = a grid view of tiles


# **Site-wide Sections**
# Nav Bar
**Desktop**
	textLogo (left aligned)
	nav items centered, od-white, fontTK 
**Mobile**
	textLogo (left aligned)
	Dropdown menu bar on right side
	
The nav bar follows as you scroll…
At start it has no background, with scroll add a dark gradient and gradient blur, no seam

# Footer
textLogo (larger than default) centered with social media buttons in rows on left and right (top and bottom on mobile, plentiful padding above and below

# **Home Page**
# Div01 - Hero
image background (use image placeholder-home image in images folder)
Header = “Honor other’s passions, honor your own.” (Left aligned)
Button01 = “Share your story” (left aligned as well) (linked to “Contact Us” page)


# Div02 - About the Author
Image background (make sure the top of the image always starts at the top of the div)
Left Column
	Header (fontTK, od-yellow) = About the Author
	Paragraph filler text (fontTK, od-white)
	Button02 = Read More (goes to About the Author page)
Right Column
	picture square box (should be slightly tilted) (use profilePic image from images folder)

# Div03 - Our Stories
Header = “Our Stories” (centered)
Body = Placeholder paragraph (centered)
tileRow = recent articles
Button01 = “view all articles” (goes to “our stories” page)

# **About the author** 
See “Article Template” About the author will use the same template. Generate a placeholder article about the author using the profilePic image in images folder

# **Our Stories**
Header = “Our Stories”
listGrid = stories (with search bar and sort by options)


# **Contact Us** 
Contact form

# **Article Template**
Each article is created in pages cms with these fields:
Title:
Main_Image:
Header:
Hook: 
Body
Date: 
Theme: 

Generate somne placeholder articles with these fields filled to populate the website

They will be displayed like this