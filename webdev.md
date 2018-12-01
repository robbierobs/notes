SGML - Standard Generalized Markup Language (SGML)HTML- Hypertext Markup Language W3C regulates the development of CSS standards

HTML 4.01 flavors

	* HTML 4.01 Transitional
		* allowed developers to insert formatting using either CSS or traditional layout instructions.
		* allowed deprecated tags

	* HTML 4.01 Strict
		* exclusive use of CSS when defining layout instructions
		* deprecated tags were not allowed and generated errors

	* HTML 4.01 Frameset
		* required for pages that used html frames
		* some felt frames provided additional functionality or enhanced a look and feel

XML - Extensible Markup Language
	* used to describe data elements on a Web page
	* enhances the structure and navigate of data to be interchanged with all types of applications
	* often used with intranets and extranets

		* focus mostly on sophisticated personal and business transactions
		* require the elements that XML offers
	* not used to format Web pages, but to describe hte data from which web pages are created
	* W3C governs the development of XML

XHTML- Extensible Hypertext Markup Language
	* combination of XML and HTML
	* two versions were created by the W3C

		* XHTML version 1.0

			* recommended in 2000
			* still used in some production environments
		* XHTML version 1.1

			* recommended in 2001
			* still used in some production environments , provided "modularization"
		* XHTML version 2.0 was abandoned in 2009 in favor of XHTML5

			* did not provide backward compatibility
			* decided to pursue an XHTML version based on HTML5 instead
		* XHTML5

			* working draft
			* under development as part of the HTML5 specification

HTML5
	* modern requirements for the Internet with fewer plug-ins

		* standardize video and audio
		* drag and drop capability for Web pages
	* more native tools such as download progress indicators
	* offline storage
	* allow devs to retrieve the geographical location information for a client-side device

Comparing Markup Languages
	* HTML5- A language that requires few plug-ins and standardizes how video and audio are presented on a web page
	* SGML - A language that is used to create other languages
	* HTML - A language that describes a document's visual layout
	* XML - A language that describes the function and context of the information contained in a document
	* XHTML - a language that organizes data in a document and formats the page's appearance in a Web browser

defining web page authoring terms
	* XML - a newer language used to define context as Tags -  opposed to appearance
	* XHTML - web language standard that separates responsibilities for organizing and formatting data
	* HTML - language used primarily for defining format and appearance of Web documents
	* tags - embedded information that defines the font, color and phrase elements used on an HTML page
	* hyperlink - embedded instructions within a text file that link it to another point in the file or to a separate file
	* markup language - language used primarily for defining format and appearance of Web documents
	* WCAG - a set of guidelines for ensuring Web site accessibility to all users, including those with disabilities
	* SGML - An ISO-standard language used to describe data and context as opposed to its appearance

"HTML Family"
	* HTML5 - markup language used for structuring and presenting Web page content
	* CSS - Cascading Style Sheets, provides the formatting and look of a web page or document written in a markup language
	* JavaScript - scripting language that provides dynamic interactive capabilities to web pages

project management and the web development project cycle
	* create and document an initial web site plan
	* obtain relevant input from stakeholders
	* communicate the web site plan
	* consider technical and non-technical concerns
	* develop the site
	* publish the site
	* manage the site

Americans with Disabilities Act (ADA)
	* enacted in 1990
	* known as U.S. Department of Justice ADA Standards for Accessible Design
	* required if you are "private employers, state and local governments, employment agencies and labor unions"
	* factors to consider

		* ensuring that all images have text-based descriptions so the sight-impaired can access through screen-reader technology
		* providing text-based alternatives to all non-text content
		* providing forms that are easily read by screen-reading technology

Web Content Accessibility Guidelines (WCAG)
	* Web Accessibility Initiative (WAI)

		* developed the Web Content Accessibility Guidelines
		* works with worldwide organizations in five main areas

			* technology
			* guidelines
			* tools
			* education and outreach
			* research and development
		* aims to ensure core tech used on the web are accessible to all users, including disabled

Section 508 of the Rehabilitation Act
	* requires that Federal agencies provide accommodations to users with disabilities for all electronic and information technology developed, procured, maintained, or used by federal agencies
	* priority 1 and 2 checkpoints of W3C's WAI Web Content Accessibility Gudielines 1.0.

Verifying Web page accessibility
	* W3C Page validator http://validator.w3.org
	* HTML validator - firefox addon
	* Cynthia Says - www.cynthiasays.com
	* MAGpie - http://ncam.wgbh.org/invent_build/web_multimedia/tools_guidelines/magpie
	* colorblindness - www.visibone.com/colorblind

addressing challenges wireframing software
	* microsoft sketchflow
	* gliffy
	* web site wireframe tool
	* hotgloo

determining the audience and message
	* customer reps
	* suppliers
	* shareholders

Validating design issues
	* message
	* fonts
	* images
	* color

css terminology
	* body {background-color:lightblue;}

		* body - selector
		* { - opening curly brace
		* background-color: - property
		* lightblue; - value
		* } closed curly brace
	* background-color:lightblue; - declaration
	* body {background-color:lightblue;color:white;} - rule

		* sets the background color to lightblue and the font color to white
	* comment - /* insert message */

adding horizontal rule
	* <hr/>
	* adding style <hr style="width:80%; height:5px"/>

images
	* <img src="image.png" alt="alternative text."/>
	* jpeg - lossy compression
	* gif - supports 256 colors

		* 87a
		* 89a

			* supports transparency
			* supports interlacing
			* supports interlacing
	* png

		* transparency
		* interlacing
		* compression
		* animation
		* adjustable bit depth
		* open standard
	* WebP

		* introduced in 2010
		* developed by Google
		* offers

			* animation
			* image transparency with lossless compression
			* image transparency with lossy compression
	* using alt tag

		* uses text in place of the image while it is loading
		* replaces image with text in non-graphical browsers such as Lynx

			* <img src="image.png" alt="This text should describe the image."/>
	* aligning text to images

		* float

			* in CSS

				* img.floatleft{float: left;margin: 5px;}

					* this code specifies that the image will float to the left of the text
					* the margin specifies the image will include a fix pixel  margin around it
					* use the following example to access the CSS class:

						* <img src="syb/SYBcollage2.png" class="floatleft" />
			* Inline

				* <img src="syb/SYBcollage2.png" style=float:left; margin: 5px; />
	* align images to text

		* height - resizes the image's original height dimension in pixels
		* width - resizes the image's original width dimension in pixels
	* resizing images

		* <img src="imagename.gif" height="HeightInPixels" width="WidthInPixels"/>

special characters
	* special characters such as less than < symbol, copyright symbol can be generated with codes

		* &lt; would generate the less than symbol
		* must end with ;
		* &copy; would generate copyright
		* &nbsp - non-breaking spaces

			* any more than one space is ignored in HTML
			* &nbsp; creates spaces (indented paragraphs)

specifying colors
	* can use hexidecimal to represent a color with RGB codes
	*
	* can also use http://www.visibone.com/colorlab
	* The hexadecimal value #000000 represents the color black.
	* In RGB code, the lower the numeric value representing a color, the darker that color will be.
	* The hexadecimal value F represents 15.
	* The hexadecimal value 10 represents 16.
	* The hexadecimal value #FFFFFF represents the color white.
	* The hexadecimal value A represents 10.
	* In RGB code, the higher the numeric value representing a color, the lighter that color will be.
	* Colors are specified in RGB values ranging from 0 to 255.
	* The hexadecimal value FF represents 255.
	* The browser-safe color palette consists of a standard of 216 colors.

background color
	* background-color: property used to specify the color
	* background-image:url('paper.gif') would designate paper.gif as the background for the page

text color uses the color propertyhyperlink color
	* a:link - determines the color of unvisited links
	* a:visited - determines the color of visited links

font
	* font-family - typeface
	* font-size - size in pixels

		* use headings (h1-h6) whenever possible instead of font-size property
	* color- font color
	* when setting a font, use a back-up as well, in case the browser does not support the selected font

		* font-family:"courier new",arial,sans-serif

review
	* hr: Element that creates a horizontal ruling line
	* align: Property that positions an element to the left, right or center
	* GIF: Image format that is typically used for simpler line drawings, and can support animation and transparency
	* img: Element that displays a graphical image on a Web page
	* background-color: Property that defines a color for a Web page background
	* width: Attribute that determines how far an element extends across the page, specified as a percentage of the window or in pixels
	* background-image: Property that identifies the image used as the background for a Web page
	* alt: Attribute that designates alternative text to appear while an image is loading or in place of an image
	* font-family: Property that identifies the type of font face used, such as Times New Roman or Arial.
	* JPEG: Image format that supports compression, and is typically used for photographs and complex images
	* src: Attribute that specifies the name and, if necessary, location of an image file
	* selector: An element in a style sheet that you want to affect.

web design issues
	* popular color combinations

		* gray green white
		* blue white
		* red white
		* red white and gray
		* red and gray
	* once a color is chosen, most sites use lighter shade of chosen colors for background
	* a lighter background acts as a foil (contrast) to the foreground text and images

		* makes site look more polishes and professional
	* cultural and audience issues

		* from what culture are the people who primarily view this site?
		* is your chosen color combination effective in the cultures this site targets or in most cultures?
		* what is considered "professional" for the audience that will most likely view this site?

page layout<header> - top of webpage, similar to header in a word-processing document<footer> - bottom of the Web page, similar to the footer in a word-processing document<nav> - defines navigation links, such as hypertext menus to access various pages of the web site<article> - web site content,m such as company services, articles, blogs, images and videos<aside> - content that is "aside" from the article content, such as advertisements or news feeds*IE8 and below cannot run HTML5, use RemySharp script. It has been utilized by Google, MIT and nearly all Web developers across the globe.______hyperlinks
	* <a href="URL"> linked text or image (or both) </a>
	* fully qualified URL - hard link, http://www.someserver.com/somepage.html, includes the protocol
	* partial URL - assumes the documents path, references are made from the documents current directory .e.g. symb.html or. ./css/stylesheets.css
	* email - <a href="mailto:info@ciwcertified.com"> info@ciwcertified.com</a>

common errors
	* don't forget to close the tag with </a>
	* place quotation marks around the value "http://www.google.com"
	* include the closing bracket at the end of the opening <a>

protocols
	* ftp: - <a href="ftp://ftp.server.com>Grab These</a>

internal links
	* <a id="targetArea1"> target anchor text or image (or both) </a> - this is the syntax to bookmark/anchor an element
	* <a href="#targetArea1"> text/images linking to targetArea1 </a> this is the syntax to recall a bookmark/anchor

		* the # sumbol is used to tell the browser to look for an anchor by this name in the current document
	* to link to an external file's internal link, use the syntax <a href="URL/filename.ext#AnchorID">link text or image</a>

		* you can start with a full or partial url but you must specify the file name followed by the hash symbol, followed by the id of the internal anchor to which you want to direct the link
		* An internal link requires an internal bookmark, called a(n) anchor, to identify the point that the link will reference within the page.
		* To create an internal link, you must first use the anchor tag with the id attribute to define an area as a target.
		* To create an internal link, you must also create the link that points to the bookmark using the anchor element with the hypertext referenceattribute.
		* The # symbol used with the href value is called a(n) hash.
		* When the href value uses the # symbol, the browser will look for a location within the current document.
		* When the href value omits the # symbol, the browser will look for a location within an external document.

link rot- The phenomenon in which hyperlinks on a Web site gradually become invalid as referenced Web page content, links and page locations change
	* you can use common link-checking software tools to check the integrity of links
	* W3C Link Checker (http://validator.w3.org/checklink)
	* LinkChecker (http://wummel.github.io/linkchecker/)
	* Link Alarm (www.linkalarm.com/)

tables
	* th: Optional element that designates the top row or left column. By default, text will appear bold and centered.
	* table: Required element to create a table, and contains all other table elements.
	* rowspan: Attribute that identifies the number of table rows a single cell can occupy.
	* caption: Optional element often used to add a title above or below a table.
	* tr: Required element that contains all data for a table row.
	* td: Required element that encloses table cell contents; not required when a similar redundant element is present.
	* padding: Property used to manipulate the amount of space between cell content and the cell's inner border.
	* colspan: Attribute that identifies the number of table columns a single cell can occupy.
	* border-spacing: Property used to manipulate the amount of space between borders of adjacent table cells.

css for tables
	* border - determines the style of the boder - border width/border line style/ border color

		* border width
		* border line style
		* border color
	* border-collapse - collapses the borders of adjacent cells into a single border instead of separating them

		* collapse
	* border-spacing - determines the amount of space between the borders of adjacent cells

		* number of pixels
	* padding - determines the amount of space between cell data and the cell border

		* number of pixels
	* width - determines how far the table of cell will extend horizontally across the page

		* number of pixels
		* percentage of the browser windows - number followed by the percent symbol
	* background-color - determines the background color for table elements

		* color name (e.g., green)
		* hexidecimal code (e.g., #00FF00)
	* text-align - aligns text horizontally

		* left
		* center
		* right
	* vertical-align - aligns content vertically

		* top
		* bottom
		* middle

forms
	* CGI script sends form information to server

		* server must be used to interpret the data that is sent by the form
	* -----

		* Enter your name: <input type="text" name="Name" size="40"/>
		* Enter your email: <input type="text" name="Email" size="40"/>
		* Should we add you to our mailing list? <br/>
		* <input type="radio" name="AddToList" value="yes"/> Yes
		* <input type="radio" name="AddToList" value="no"/> No

			* server will send the above data in the form of a raw text string that represents the following

				* Name=Dimitri+Pappas&Email=student50@class.com&AddToList=yes
			* after the server receives this information a CGI script can parse and format the raw text string to a human-readable format similar to the following:
			* Name: Dimitri Pappas
			* Email: student50@class.com
			* Mailing List: Yes
	* Text input - <input type="text" name="Whatever name will be" size="whatever size"/>
	* Radio button - <input type="radio" name="whateverradioname" value="selection (yes/no)"/>
	* FormMail is a Perl script written in 1997 by Matt Wright.

		* designed to

			* receive information from a web form via the perl interpreter
			* send the form information to you via email
		* popular for many reasons

			* free of charge from Matt's Script Archive
			* written in Perl, which allows developers to use a free CGI interpretter

				* most modern OSs allow the Perl interpreter to be installed
				* free and powerful, well written script
			* easy to customize
		* after downloading FormMail

			* install Perl on your Web server
			* define the formmail variables so that the script is capable of receiving information and sending it to you
			* give executable permissions to the FormMail.pl script on your web server
			* Refer to the FormMail.pl script in your web form
			* wait for users to visit your site and then check your email for results
		* Spam concerns

			* use the latest version of FormMail
			* configure the scripts correctly
		* Other versions

			* alternative versions of FormMail are available for PHP and ASP
	* sample syntax

		* <form>method="post"action="http://www.anyserver.com/cgi-bin/scriptfile">             <input .../>               <select>...</select></form>
	* <form> element two different attributes (options)

		* method - tells the browser what method to send form data
		* action - specifies name and location of CGI script used
	* method

		* "get" - Form data is put into the URL of the Web page. Sends info in cleartext, less secure
		* "post" - form data is posted to the URL specified by the action attribute. Post is preferred for sending form data. Can send more characters, but may require more processing by the CGI script
	* action

		* specifies the name and location of the CGI script used to process the form.
		* contents of the form will be processed by the script and acted upon according to the instructions in the script
	* <input><select><textarea> tags

		* use these to create form fields by placing them in the <form></form> tags
	* <input> tag and the type of attribute

		* standalone tag

			* <input type="radio" name="AddToList"/>

				* type can be changed for different htings
				* type="password" name="Password" creates password field
	* <select>

		* used to create a single or multiple-option select list

			* example
			* <select name="frequency"><option>Once a week</option><option>Once or twice a month</option><option>Once a month</option><option value="NotAtAll" >Never</option></select>
		* when using select you may want to allow users to select more than one option from the list

			* use the multiple attribute with "multiple" as the value

				* <select name="Countries" multiple="multiple" size="4"><option></option><option></option>
	* <textarea>

		* larger and allows more input than textbox
		* can enter default text between the opening and closing tags, it'll appear in the text area until the user types in their input
		* <textarea>Type your comments here</textarea>
	* name attribute

		* identifies information your receive from the user and associates it with a value you specify
		* helps organize user input
	* textboxes

		* used to collect a single line of data from the user
		* syntax

			* <input type="text" name="Fieldname"/>
		* for default text, use the value attribute

			* <input type="text" name="Fieldname value="DefaultText"/>
	* file upload

		* <input type="file" name="uploadedfile"/>
	* submit and reset buttons

		* <input type="reset"  ...
		* <input type="submit"....
	* radio buttons

		* Do you know carpentry? <br/>
		* <input type="radio" checked="checked" name="KnowCarp" value="yes"/> Yes
		* <input type="radio" name="KnowCarp" value="no"/> No

			* checked="checked" - means the yes value is checked by default
	* checkbox

		* <input text="checkbox" name="groupName"/>
		* can have multiple choices checked by default

			* What skills do you have that can help us at Habitat for Humanity? (Check all that apply):<br/><input type="checkbox" name="Carpentry"/>Carpentry<br/><input type="checkbox" name="Plumbing"/>Plumbing<br/><input type="checkbox" name="Financing"/>Financing<br/>

				* name could also be "Skills" <input type="checkbox" name="Skills"/>Carpentry<br/>
	* select lists

		* single-option select list

			* <select name="listname"><option>Option 1 </option><option>Option 2</option>...<option>Option n </option></select>
	* scrolling text area box

		* <textarea> is a container tag

			* text between the textarea tags will appear as default text within the box
			* there are several key attributes

				* cols

					* specifies the width in characters of the scrolling text box
					* integer value (e.g., "25", "40")
				* rows

					* specifies the number of rows of text to display in the box
					* integer value (e.g., "2", "5")
		* wrap

			* user-entered text can wrap to new lines when submitted. This advanced attribute is used in conjunction with server-side scripts (such as PHP) that process form data.
			* if "soft" is specified, text in the textarea is not wrapped when submitted. This setting is the default
			* if "hard" is specified, text in the textarea will wrap (adding newline characters) when submitted. The cols attribute must be specified when using wrap="hard".
	* form end questions

		* method: Attribute that specifies how a browser will send form data to a Web server
		* name: Attribute that identifies user input and associates it with a value to help organize user-submitted data
		* select: Element used to create drop-down option lists from which the user can choose single or multiple options
		* form: Required element to create a Web form, and contains all other form elements
		* textarea: Element used to create scrolling box into which text can be entered
		* input: Element used to create text boxes, check boxes, radio buttons, and the Submit and Reset buttons
		* value: Attribute that allows default text to appear inside a text box
		* cols: Attribute that specifies the width of a scrolling text box
		* action: Attribute that specifies the name and location of the script used to process the form

using captcha
	* many services exist

		* captchas.net (http://captchas.net)
		* secureimage CAPTCHA (www.phpcaptcha.org)

SEO - Search Engine Optimization and Web Forms
	* create as simple a form as possible

		* each additional field you use may reduce your score
	* Some search engines score a page lower is a CAPTCHA is used.

		* bots will not read and process all of the page where human input is needed
	* give form field informative descriptive labels
	* provide a clear call to action, do not assume they'll know what to do because of a submit button
	* provide alternative text navigation

form review part 2
	* Text box: A text field into which a user can enter characters.
	* Radio button: Round option buttons in a group of two or more mutually exclusive options.
	* Check box: Square boxes in a group of two or more non-exclusive options.
	* Single-option select list: A drop-down list of two or more options from which a single selection can be made.
	* Multiple-option select list: An exposed list of two or more options, optionally scrollable, from which the user can make multiple selections.
	* Text area: A scrolling text field into which the user can enter multiple lines of text.
	* Password field: A text box that visually masks the entered characters as asterisks.
	* File upload: A button and field that allow users to navigate to and select a local file for uploading.
	* Submit button: A button that, when clicked, causes the form's action statement to process.
	* Reset button: A button that, when clicked, clears all form data and sets all form fields back to the default values for those fields.

Video
	* <video width="36" height="270" controls="controls" poster="image.png"><source src="video.mp4" type="video/mp4" /><source src="video.wbm" type-"video/web" /><source src="video.ogg" type="video/ogg" />Your browser does not support the HTML5 video element.</video>
	* elements/attributes

		* <video> defines the video to embed in the web page
		* width and height - specifies the width and height in pixels, duh
		* controls - adds video controls, native to HTML5
		* poster - image displayed until the play button is clicked
		* <source> - defines the media resource, multiple can be listed to support a variety of devices
		* src - location of the file
		* type - identifies the format of the video, supports MP4,WebM and Ogg
		* text - Text inside the <video> tag will show if the browser/device cannot support the video format

audio
	* <audio controls="controls"><source src="audio.mp3" type="audio/mpeg" /><source src="audio.wav" type="audio/wav" /><source src="audio.ogg" type="audio/ogg" />Your browser does not support the HTML5 audio element.</audio>
	* common attributes

		* loop="loop" - loops music 😐
		* autoplay="autoplay" - music plays immediately upon loading

image maps
	* an image that contains clickable regions, sometimes called hot spots
	* defining a client-side image map coordinates

		* <map name="mapname"><area shape="shape" coords="coordinates" href="url" alt="description"/><area shape="shape" coords="coordinates" href="url" alt="description"/><area shape="shape" coords="coordinates" href="url" alt="description"/></map><img src="imagemap.gif" usemap="#mapname"/>

			* usemap attribute - indicated that the image placed in the web page will use an image map

				* <map name="mapname"> and usemap="#mapname"> are the same value
				* map tags name attribute - reference name for the image map
				* area tag - stand-alone tags that define the hot spot regions of the image map
				* shape attribute -

					* accepted values are

						* rect for rectangle
						* circle for circular area
						* poly for any other shape
						* default to use the entire area
					* shape of the image map
				* coords attribute

					* number and meaning of coordinate you specify will vary based on the shape attribute

						* rectangle areas: x1,y1,x2,y2
						* circle areas: x1,y1,radius
						* polygon areas: x1,y1,x2,y2....xn,yn (up to 100 pairs of coordinates)
				* area's href attribute - value is a URL specifying the linked page that will load when the user clicks the defined hot spot
				* alt attribute - alternative text must be provided using the alt attribute whenever the href attribute is used
				* # symbol in the use map attribute's "mapname" - indicates that the #mapname value represents an image map defined within the same HTML file. If not hash symbol is present here, the browser will look externally for the referenced mapname file
			* rectangle area map example

				*
				* <area shape="rect" coords="x1,y1,x2,y2" href="url" alt="description"/>

					* x1 indicates the leftmost point to the area to be defined
					* y1 indicates the topmost point of the area to be defined
					* x2 indicates the furthest point to the right in the area to be defined
					* y2 indicates the lowest point of the area to be defined
				* ex. <area shape="rect" coords="1,52,33,96" href="hand.htm" alt="hand"/>
				* Home|Search|Help|Other image (figure 7-11)

					* <img src="buttons.gif" usemap="#ButtonMap"/>
					* <map name="ButtonMap"><area shape="rect" coords="0,0,78,75" href="home.htm" alt="home"/><area shape="rect" coords="78,0,156,75" href="search.htm" alt="search"/><area shape="rect" coords="156,0,234,75" href="help.htm" alt="help"/><area shape="rect" coords="234,0,312,75" href="order.htm" alt="order"/></map>
			* defining a circle hot spot

				* <area shape="circle" coords="x1,y1,radius" href-"url" alt="description"/>
			* defining a polygon hot spot

				* the coordinates define the points of the polygon in sequence. You can use up to 100 pairs of coordinates to define a polygon.
				* <area shape="poly" coords="x1,y1,x2,y2.....xn,yn" href="url"/>

image transparency
	* only certain file types can be transparents

		* GIF89a
		* PNG
	* Allows background to blend in, making the image appear to float on the page background.

image interlacing
	* Only GIF 89a and PNG support animation.

		* programs such as Alchemy Mindworks GIF construction Set allow you to incorporate several images into one file
	* flash animation

		* Adobe Flash technology
		* Flash CS4
	* microsoft silverlight

		* silverlight plug-in needs to be launched from an HTML page via javascript
		* designed for online video playback and intense graphical interactivity
	* java applets

		* must have java interpreter installed
		* may not render as quickly as Flash or Silverlight movies due to the nature of the java interpreter
		* java remains a proprietary technology owned by Sun
	* scalable vector graphics (SVG)

		* W3C- recommended language developed by various vendors

			* Adobe
			* Microsoft
			* Sun
		* uses XML to describe graphics and graphical applications
		* allows you to create cross-platform animated movies
		* features

			* compression

				* smaller size than other formats
				* more efficient compression than JPG or GIF images
			* Searchable text

				* text within SVG images can be indexed and searched
			* Zooming

				* you can zoom in or portions of the image without losing image quality
		* supports other technologies

			* including JPG, GIF and Java
	* You can identify animation techniques by saving the image and identifying it's properties or viewing the source code to see how it was inserted into the page
	* mobile device issues with animation and plug-ins

		* animation techniques are often proprietary

			* some visitors may need to download a plug-in, some may choose not to visit your site

				* create another version of your site to accommodate

					* requires more time na dresources on your part but ensure that your site is available to all users
		* plug-ins drain system resources

			* battery life can decrease as much as 40% on a mobile device when running a plug-in.
			* HTML5 solves this issue by providing native support for animation, movies and other multimedia without the use of plug-in. CSS and JavaScript are used instead
		* animation may seem useful and interesting, but it is frequently overused
		* animated images can limit accessibility

creating and managing images
	* when scanning or importing pictures from a digital camera for use on the web, it is generally accepted that you should set the resolution to 72 dpi
	* licensing stock photos

		* royalty-free license

			* initial fee but you do not have to pay a royalty each time the image is used. Buyer does not have the right to resell or transfer the image. typically prices by size of the digital file (600KB might cost $50, while a 10MB version of the same image may cost $200)
		* rights-managed license

			* allows the buyer to "rent" an image through negotiation of price. Some licenses stipulate exclusivity (buy may restrict similar use of the image by others for the duration of the license). Usually more expensive than royalty-free but allow for much larger print runs. Fee charged is based on the scope of the project. Maybe $200 to use an image in a small brochure, or many thousands of dollars to use an image in a national advertising campaign
		* advantages/disadvantages of using stock photos

			* advantages

				* saving time and money
				* quick and easy to search
				* licenses can be purchased online
				* images can be downloaded for use immediately
				* cheaper than hiring a photographer and models, setting up a photo shoot
				* you know exactly what the finished image looks like
			* disadvantages

				* cost associated with the licensing fees
				* reduction in creative control
				* only select image that are available
				* may not find exactly what you want
		* resources

			* getty images (www.gettyimages.com)
			* Shutterstock images (www.shutterstock.com)
			* microstock

				* iStockphoto (www.istockphoto.com)

					* deal almost exclusively over the internet
					* accept photographs from amateur photographers as well as professionals
					* sell images at very low cost (generally 0.20 to $10)
					* image price based on credits

						* image may cost between 1 and 20 credits, depending on size and credits may range from $0.95 to $1.40 each.
			* free images

				* free of charge with certain restrictions

					* domain name of the web site must not be removed from the photo
					* the photos may not be resold
					* the photographer who took the photos retains the original copyright
					* freestockphotos.com (www.freestockphotos.com)
					* freeimages.co.uk (www.freeimages.co.uk)
					* freepixels (www.freepixels.com)
			* photosharing

				* should consider

					* relative ease of use
					* tools for managing photo albums and videos
					* tools for photo editing
					* monthly or annual fees
					* storage space and daily upload limits
					* presences or absence of ads and spam
					* ability to buy and sell prints
					* password-protected access
				* several photo-sharing sites advertise themselves are "family friendly"
				* popular photo-sharing sites

					* DotPhoto (www.dotphoto.com)
					* Webshots (www.webshots.com)
					* Fotki (www.fotki.com/us/en)
					* Flickr (www.flickr.com)
					* SmugMug (www.smugmug.com)
					* Picases (http://picasa.google.com)
					* Snapfish (www.snapfish.com)
					* Shutterfly (www.shutterfly.com)

server-side and client-side languages
	* Variable

		* A place in memory used to store information for later use. Variables are used in simple applications and are essential in complex ones. Variables are usually created by using the equal sign ( = ). For example, to create a variable named James, you would use the following command: James=James. Variables are often referred to as values preceded with a dollar sign ( $ ). For example, the variable named James would be referred to as $James. In many languages, variables are case-specific (e.g., the variable $James is different from the variable $james).
	* Array

		* A collection of variables stored in a series. Arrays are used to hold multiple values; a variable can hold only one value.
	* Function

		* A line of code that allows you to refer to an entire series of steps or commands. Functions are used to organize code into discrete sections.
	* Interpreter

		* Software used to read and process code in standard text files. Interpreters either reside on the server or are downloaded to a client. PHP, Perl and ASP are all languages that use an interpreter. Some CGI applications must explicitly specify the location of the interpreter. For example, Perl requires the first line to include a correct reference, or the script will fail.
	* Compiler

		* An application used to process code in standard text files into executable applications. For example, to compile a C application named james.c, you would use the gcc application: gcc james.c -o james.exe.
	* Include

		* A set of files called a library that you can refer to in your code. Programmers often include libraries in their code to avoid having to re-create code that has already been written.
	* Print

		* A command that prints application output to a destination, often a computer screen. For example, you can create an application that prints information to a window on the screen so you can monitor the application's progress. Print is generally part of a programming language's Input/Output library, which is responsible for allowing users to input information (e.g., through a keyboard) or output information (e.g., to a monitor).
	* Echo

		* A command that repeats the input you type back to a terminal or an application window. Echo can also be used in an application to repeat input so that it can be processed or forwarded.
	* Statement

		* Logical constructs that allow you to control the way that information flows in the application.

programming statements
	* If/then

		* Executes a process only if a particular condition is true. For example, an application may contain a statement that checks whether the \tmp\ folder is present. If it is, then the application will run. Classic if/then statements allow only one condition to occur. Known as a conditional statement.
	* If/then/else

		* Similar to an if/then statement, but executes a group of additional commands if the given condition is false. For example, an if/then/elsestatement can direct the following logic: If the \tmp\ folder is not available, then check to see if the \temp\ directory is available, or else create a directory named \tmp\. Known as a conditional statement.
	* Do while

		* Runs ("do") a specified subprocess while a specified condition is true. For example, an application may continue to present an alternative window while the mouse is being right-clicked. Often used as a part of an if/then or if/then/else statement, the do while statement ensures that an action occurs the entire time a condition is true. Sometimes known as a repeat until statement.
	* Do until

		* Similar to a do while statement, but runs the specified subprocess until a specified number of events have occurred. For example, a calculation process may add the number 1 to the result of the previous statement until the sum reaches 100, then exit.
	* Break

		* When placed inside of a statement, allows an application to break out of an infinite loop in case of a problem.

server-side languages
	* code is executed by the web server
	* code is typically placed into applications
	* code executes because an interpreter has been installed and activated on the Web server
	* server-side scripts are used for:

		* browser detection
		* database connectivity
		* cookie creation and identification
		* logon scripts
		* hit counters
		* file uploading and downloading
	* PHP( PHP hypertext preprocessing)

		* can be placed in the CGI bin directory
		* example code:

			* <?php$ua = $_SERVER['HTTP_USER_AGENT'];
			* {print"
			* <html>
			* <title>PHP Example</title>
			* </head>
			* <body>
			* <h1>Hello, World!</h1>
			* Your user agent is:<strong>{$ua}.</strong>
			* </body>
			* </html>
			* ";}
			* ?>
	* Practical Extraction and Report language (Perl)

		* cross-platform that enables users to write custom CGI programs and system management programs
		* example code:

			* #! /usr/bin/perl
			* use CGI qw/:all/;
			* $cig_object = CGI::new();
			* print "content-type: text/html\n\n";
			* print "<html>\n<head>\n<title>\nPerl CGI
			* Example \n</title>\n<body>\n<h1>Hello,
			* World!</h1>\nYour user agent is: <b>\n";
			* print $cgi_object->user_agent();
			* print "</b>.</html>\n";
		* first line "#!" is called the "shebang" and is used in Perl applications to point to the location of the Perl interpretter
	* Active Server Pages (ASP) using VBScript

		* proprietary to Microsoft
		* PHP alternative to ASP
	* C

		* foundation to many other languages

			* C++ and Java
		* developed in the late 1960s.
		* procedural language

			* subprograms are called functions
		* uses standard libraries that you can include in the program

			* #include <stdio.h>
	* C++

		* object-oriented

			* create an object that can be manipulated throughout the program
			* allows developers to create efficient and powerful code
			* ObjectA discrete portion of an application. Once an object is instantiated (i.e., created), it can then be used. All objects have specific states and behaviors that can be manipulated. An object is also known as an instance, because an object can be duplicated and then manipulated within a program.AbstractionThe determination of all elements that make a particular object unique, separate and distinct from another instance of an object.ClassA group of similar objects.PolymorphismThe ability of the programming language to make an object behave differently or to take on different characteristics, depending upon its place in an application.InheritanceThe ability for one class to share characteristics with another class. Characteristics can include an object's state, structure or behavior.
	* Java

		* object-oriented
		* system interdependent
		* program is not compiled on a specific computer, application is sent and interpreter is installed to each computer
	* JavaServer Pages (JSP) and Java servlets

		* an application that must be installed directly onto the remote server
		* code is not downloaded to the browser
		* when using you must perform the following

			* compile the servlet
			* place the servlet on a server that is capable of handling it
		* one of the most popular web servers that support JSP and servlets is Apache Tomcat
	* visual basic

		* used in .NET CGI
		* considered easier to use than languages such as C++ and Java but as a result, this simplicity sometimes does not allow VB to perform all the tasks that C++ and Java can perform
	* C#

		* proprietary to Microsoft
		* competitor to Java
		* a.k.a Visual C#
	* server-side includes (SSIs)

		* instruction within an HTML page that directs the web server to perform an action
		* considered an alternative to CGI because it does not use languages such as JavaScript
		* written in SGML
		* used to:

			* place the results of a database query into a page
			* execute other programs
			* indicate the last time that the displayed document was modified
			* insert text at the bottom of a page (footer). Can contain any text you want
			* add the current date as a timestamp to a page
		* extensions:

			* .shtml
			* .shtm
		* most Web servers include SSI capability but it may be disabled

			* enable it in httpd.conf file in Apache Server
		* may not be configured to look for the standard .shtml or .shtm file

			* find the supported extension type for SSI
			* define a mime type for the shtml or shtm extension for the web server
	* lesson review

		* PHP: An interpreted server-side scripting language for creating dynamic Web pages
		* Perl: A cross-platform programming language that enables users to write custom CGI programs and system management programs
		* ASP: Microsoft's original server-side scripting solution
		* C: A procedural compiled programming language used to develop stand-alone applications, rather than Web applications
		* C++: An object-oriented compiled programming language whose programs must be compiled to a specific computer type
		* Java: An object-oriented compiled programming language whose applications are platform-independent
		* Visual Basic: A compiled programming language developed by Microsoft and used for stand-alone applications and server-side Web applications
		* C#: A compiled object-oriented programming language that is the proprietary Microsoft competitor to Java

client-side languages
	* issues

		* some clients do not support javascript or other scripting language
		* users can deactivate script execution in browsers that normally support it. Many companies direct their employees to disable scripting
	* javascript

		* object based scripting language
		* must reside inside HTML documents
		* can add

			* pop-up windows
			* automatic date/time changes
			* images and text that change upon mouse rollover
			* cookie creation and identification
		* scripting language is used within a program to extend its capabilities
		* object-based NOT object-oriented
		* objects

			* document - allows you to obtain values from and write values to a document
			* navigator - allows you to determine the type of browser accessing a web page
			* array - allows you to create a series of variable to later manipulate
		* use <script> tags
		* practical uses for scripts of this type include:

			* presenting different versions of a site to different browsers
			* informing users in a corporate intranet to upgrade their browsers to a supported version
			* ensuring the accessibility to disabled users
		* javascript can by used for copyright protection
	* vbscript

		* proprietary implementation of javascript
		* made by microsoft and only works in windows internet explorer

dynamic html (DHTML
	* umbrella term to describe HTML's ability to work with other technologies to provide animation, interactivity and dynamic updating in Web pages.

		* automatic scroll text headlines
		* can animate an image only when a mouse passes over it
		* absolute positioning - create text that moves to certain positions in reaction to user input
		* new document content - context can be exchanged dynamically without having to refresh the browser windows
		* granular control over animation, audio and video - can write code to begin a sequence at a certain time or after a certain event
	* APIs

		* HTML5
		* CSS
		* Javascript to access the DOM (Document object model)

document object model
	* a standard developed by the w3c

		* describes elements/objects within a document rendered by a web browser
	* API - application programming interface

		* specifies how objects in a document can be referred to and manipulated through scripting languages
	* meant to be a vendor-neutral cross-platform standard
	* currently the DOM is not as universal as expected. Most browser vendors either add their own features or do not implement all of the DOM as proposed by the W3C
	* accessing a browser's dom

		* need to use a scripting language such as javascript or vbscript

			* (do not confuse the DOm with the COM (component object model). The DOM describes documents within a browser. COM is a microsoft specification for creating applications. The DCOM (Distributed Component Object Model) describes the ability to create applications that work well over network connections
		* sometimes a browser that is less compliant may be the best choice to use

			* stability and security
			* authentication features
			* availability
		* undefined object error and the DOM

			* may receive an undefined object error if you visit a web page and your browser does not support a specific DOM, may view an unformatted document in plain text.
		* HTML, DOM, browser compatibility

			* most HTML elements/attributes are backward-compatible
			* some are more ambitious at improvements, including frames and ability to respond to users

canvas
	* simple-pixel based drawing API that produces a bitmap image
	* can use canvas instead of using Flash and similar plug-ins.
	* uses fewer resources than a plug-in does
	* only has two attributes

		* height
		* width
		* default is 300x150
	* styles that are applied will have no effect on the drawing capabilities
	* older browsers do not fully support canvas

		* alternative content should be used
	* id attribute is not specific to canvas but a unique id should be used to identify it later
	* getContext

		* only one parameter - the type of context

			* 2d
			* 3d
		* built into HTML5
	* canvas only supports one shape - rectangle

		* all other shapes are created by using a collection of functions and combining one or more paths
		* to draw a rectangle

			* specify the x and y coordinates
			* specify the height and width of the object you want to draw
			* fillRect(x,y,width,height) - draws a filled rectangle
			* strokeRect(x,y,width,height) - draws a rectangular outline
			* clearRect(x,y,width,height) - clears the specified area and makes it fully transparent

offline web application
	* web pages will store data locally within the user's browser, utilizing the application cache
	* especially useful for mobile
	* manifest

		* tells the browser which files to store locally
		* automatically update when the user goes back online
	* allows quicker loading of the application next time it is used
	* reduces the load placed upon the server because the server does not have to provide an application each time it is used
	* how it works

		* need to create a mandatory cache.manifest file

			* manifest lists the files needed for the web application to work offline
			* ex. if a Web site is cached, you would list the main .html file, the .css file and any images or javascript files used.
			* the file name requires a file name extension of .manifest, the file name itself is usually the application name, such as mortgagecalculator.manifest or date.manifest
			* the manifest file always includes the text "CACHE MANIFEST" in the first line.
			* ex:CACHE MANIFEST#The CACHE MANIFEST line is required. This line is a comment.#Blank lines and comments are ignoredCACHE:index.htmlstyles.cssactions.jsbanner.jpgFALLBACK:images/banner.fallback.jpg/offline.html*
			* CACHE sections lists the application files that will be used offline (e.g. cached).
			* FALLBACK defines what the user will see in the event a resource does not load

				* this can be a simple web page that states "We're sorry......."
			* NETWORK defines an online whitelist

				* files that are never stored

					* possibly need a server to process and you would not need them locally
		* include manifest attribute in the <html> tag that identifies the manifest file you are linking to

			* <html manifest="date.manifest">

geolocation
	* used to locate a user's geographical position

		* can use

			* ip address
			* wireless network
			* GPS hardware
	* can compromise a user's privacy

		* need to give permission in a pop-up
	* uses three methods for getting the location from the user

		* getCurrentPosition

			* retrieves the current geographical location of the user
		* watchPosition

			* retrieves periodic updates about the current geographic location of the user
		* clearPosition

			* cancels an ongoing watchPosition() call

drag-and-drop functionality
	* can be used on all links, text and image elements
	* drop zone - a place where items can be dropped
	* two types of drag-and-drop functionality

		* dragging files from the user's computer onto a Web page
		* dragging items to a different location within the same page
	* adding

		* specify the html element you would like to be draggable
		* add an event listener for the dragstart event
		* add an event listener for the dragover and drop events on any element that will accept a dragged item
	* how

		* <img id="drag1" src="logo\CIWLogo.png" draggable="true" ondragstart="drag(event)" width="336" height="69" />
		* must use datatransfer object to define the draggable element's data type and value

			* assigning an id to the item to be dragged will allow that id to be saved in the DataTransfer object to be used again after the element is dropped
		* must define a drop zone

			* dragover - when you want to drag something over it
			* drop - when something is dropped

web application frameworks
	* help manage the creation of maintenance of online databases
	* provide web page security
	* manage data on the servers that host the web pages
	* provide templates that make it possible to change the background of web pages while keeping the graphics, text and other elements of the page intact
	* two applications are gaining favor

		* Django

			* written in Python
			* open source
			* emphasizes Rapid Application Development (RAD)
			* Don't Repeat Yourself (DRY)
			* modifying any single element of a system will not change logically unrelated elements
			* logically related elements will change correspondingly to ensure uniformity and predictability
		* Ruby on Rails

			* open source
			* RAD - Rapid Application Development
			* DRY
			* Works with a wide range of Web Servers

				* apache
				* lighttpd
			* databases

				* MySQL
				* Oracle
				* SQL server
				* DB2
			* OSes

				* Windows
				* Linux
				* Mac OS X
			* emphasizes simplicity and ease of use so that developers can create complex Web sites quickly

connecting to a database
	* in order for a database to work, you must

		* provide a way for the web server and database to recognize each other
		* provide permissions to the database so that it can be read and/or written to
	* cgi and permissions

		* often fail because the web server does not have execute permissions
		* the file or script has incorrect permissions which prohibits the server from executing the file
		* too many permissions can cause serious security problems
	* isps and cgi

		* If working with an ISP you will need to request CGI services

			* enable execute permissions on your scripts
			* create a directory that contains available CGI scripts
			* provide user names and passwords with enough permissions for the system
	* n-tier applications

		* data - the database file or multiple database files
		* business logic - the SQL coding necessary to create relationships with the data stored in the database
		* presentation - the way that data and business logic are presented on the user screen

			* web forms in HTML
			* application-specific interfaces such as MS Access or a web browser
		* single-tier - all three layers are combined into one application/database - local system, opens access, manipulates the database
		* two-tier - client is responsible for presentation and business logic, server houses the data, called client-server relationship - proprietary client connects to a database server to process information - microsoft access to query a remote database
		* n-tier - business logic, data, presentation are completely separated.

			* upgrades does not necessarily mean the others are affects
			* ex. using a web browser to visit a web site that is connected to a remote databasethe web browser downlaods the necessary forms and is responsible for presentationthe web server -> business logic and programmingremove database provides data
			* many times mulitple web servers and databases are used

end of lesson review
Here are the terms related to Web technology:
	* Function: A stand-alone, reusable segment of program code that is not part of an object.
	* DHTML (Dynamic HTML): A general term used to describe the combination of HTML, script, styles and the Document Object Model (DOM) that provides Web page interactivity.
	* Geolocation: An HTML extension used to provide location-based services.
	* Canvas: An HTML extension used to provide on-the-fly graphics or animation to a Web page.
	* Drag-and-drop: An HTML extension that allows Web page elements to be moved inside and outside the Web page.
	* DOM (Document Object Model): A W3C standard that specifies the way objects are manipulated through script.
	* Object-oriented: A style of programming that links data to the processes that manipulate it.
	* Offline Web application: An HTML extension that allows Web programs to function when an Internet connection is not available.
	* Browser detection: The ability to use the DOM and discover particular aspects of a user agent.
	* Compiler: A program that converts text files into executable applications.



# introduction to gui html editors
#### What You See Is What You Get (WYSIWYG) editors.

* Adobe Dreamweaver
* Microsoft Expression Web
* [KompoZer - Open Source](www.kompozer.net)

There are two types of GUI editors:
* page editors
* site management editors

both are WYSIWYG programs.

### Page editors
* allow you to create a web page using a mouse and a toolbar.
* functionality is usually limited to creating individual web pages
* software programs that provide only page editor functionality include:
  - [SiteSpinner Web Page Maker](www.sitespinner.com/web-page-maker.html)
  - [Mozilla SeaMonkey](www.seamonkey-project.org)

### Site management editors
* provide both web page creation and site management functionality
* allow team of designers and developers to work in an integrated environment to design, build and manage web site and internet applications
* can manage the entire web site with this type of application during and after development
* includes task automation and workflow integration with other programs
* software programs that provide these functions includes
  - adobe Dreamweaver
  - microsoft expression web

### GUI HTML Editor Functionality

GUI HTML editors allow you to create web pages, edit/enter text the way you would in a word-processing application. Images, tables, links, bookmarks and so forth can be created easily because the application writes the HTML code automatically

**features of GUI editors**
* Templates and wizards
* text style options - can use different font styles, text size, color, formats (centering, boldface, italics).
* icon bars -easily identifiable graphic icons to provide the same functions found in text-based menus
* image features
* hypertext links features
* import HTML page features
* table creation features
* spelling check
* publish document features

**W3C authoring tool accessibility guidelines**
seven points that help determine the suitability of a GUI editor for developers with disabilities, which include: the ability of the GUI editor to generate proper code and the usability of the GUI editor by a disabled person creating a web page.

* Make the authoring tool user interface accessible
  - must be accessible to people with disabilities, including the editing views and alternative text for toolbar icons
  - authoring tool user interfaces must follow applicable accessibility guidelines such as the ATAG
  - must be perceivable, such as including alternative content and larger fonts
  - editing views must be operable
  - editing view must be understandable


* Support the production of accessible content
  - fully automatic processes must produce accessible content
  - authors must be supported in producing accessible content
  - authors must be supported in improving the accessibility of existing content
  - authoring tools must promote and integrate their accessibility features

End of lesson review
* Templates and Wizards: Allow you to create custom Web pages quickly by selecting from a series of choices
* Text Style options: Allow you to apply different font styles, alter text size and color, and apply text formats
* Icon bars: Offer easily identifiable graphic icons to provide the same functions found in text-based menus
* Images: Allow you to easily insert graphic images into a Web page
* Hypertext Links: Allow you to create hyperlinks to pages and files within your Web site, and to pages and files on the World Wide Web
* Import HTML pages: Allow you to open pages from the World Wide Web and save them to a Web site or local file system
* Table Creation: Allow you to arrange data or organize a page layout
* Publish Documents: Allow you to click a button to post pages to a Web server

### html text editors vs gui editors

**HTML text editors**
* if you are considering learning a scripting language such as JavaScript or VBscript, you _must_ learn to write code manually.
* if you know HTML code you can maximize the benefit of GUI HTML editors by manually modifying code
* you can learn the fundamentals of HTML and update your pages to the latest version(s)

**GUI HTML editors**

**advantages**
* place code into files for you, enables you to create pages quickly by clicking your mouse
* most GUI editors allow you to modify your code manually

**disadvantages**
* some gui editors will alter or ignore any code you enter manually
* many gui editors have not kept pace width the evolution of HTML and do not provide options for using the recently developed tags
* at the time of this writing HTML5 was not supported by an open-source GUI or WYSIWYG HTML editors

### web site publishing

**File Transfer Protocol (FTP)** can be used to publish the website as well as GUI HTML editors.

#### publishing to a test server
why?
* to verify that the web server can process any CGI and database access request
* to locate and repair any dead links
* to allow members of the dev team and stakeholders to preview the site, may need changes

### test server config

* nearly the same as production server
* same operating system version
* same type and version of web server software
* same CGI interpreter software

### publishing with KompoZer

file | publish then enter appropriate info.

## developing web pages for mobile devices

* keep web pages simple and uncluttered, use white space to help give the site an uncluttered look and keep the use of images to a minimum
* prioritize your content
  - only ocntent that is absolutely necessary for the viewer
  - should not contain any banner ads
* optimize your site to a smaller screen
  - most common size is 240x320, 320x480, and 480x800

* use clean valid markup, use css to separate the presentation from the content, most mobile site visitors want access to content and links that may have css disabled
* always use the alt attribute in your <img> tags
* ensure that you label form fields so they're easily identifiable
* use heading tags to build the structure
* reduce margins and padding to give more usable space
* provide easy-to-use navigation options and links
* ensure that your content is easy to read on mobile

## mobile apps vs mobile websites

* advantage of mobile web sites
  - cross-platform
  - can be accessed without waiting for an app to download and install
* advantage of mobile apps
  - designed and built for a specific mobile OS
  - often runs faster
  - no web browser required

**bottom line - mobile web pages and mobile apps will coexist**

## converting a web site for mobile users

list of sites to convert to web pages
* [bMobilized](http://bmobilized.com)
* [Mobify](www.mobify)
* [MobileAppAmerica](www.mobileappamaerca.com)
* [mobiSiteGalore](www.mobisitegalore.com)
* MobStac
* MoFuse
* onbile

## testing a mobile web site

validate as well as test
* W3C mobileOK checker (http://validator.w3.org/mobile)
* dotMobi Emulator (http://mtld.mobi/emulator.php)
* iPhoney (www.marketcircle.com/iphoney)
* iPadPeek.com (http://ipadpeek.com)
* BlackBerry Simulator (http://us.blackberry.com/developers/resources/simulators.jsp)

## working with web 2.0

**web 2.0** is a common term that refers to changing trends in the use of WWW technology and web design since the early days of the web when most web pages were static.

web use before the "bursting of the dot-com bubble" in 2001 is referred to as **web 1.0**

**Ajax (Asynchronous JavaScript and XML)** is a web 2.0 programming methodology that lets web apps interact with usersr the same way they do with desktop apps. It allows you to create interactive web apps using XHTML, CSS, the Document Object Model (DOM), JavaScript and XMLHttpRequest.

## browsers as application delivery platforms
**SaaS software as a service** is another term used to describe cloud computing because:
* software responsible cannot be downlaoded and owned by the end user, only remote
* software available as a service is free or for a fee.
  - free service that is limited or contains ads
  - enhanced or professional service that contains no adds and is often full-featured

[Meebo](www.meebo.com) is an example of a web application delivery platform

Meebo is a free Ajax-based instant messaging program that combines existing IM service onto one web interface.

**advantages**
* flexibility
  - one single person can run a sophisticated busines
  - large enterprise can use a similar product
* scalability
  - as enterprise grows, it can rely on it's cloud computing partner to increase capability
  - won't need to hire additional employees and obtain new hardware
* cost reduction
  - companies can hire fewer employees
  - purchase less hardware
**disadvantages**
* connectivity
  - lose internet or if remote loses internet, you don't have access
  - workers dependent on remote applications
* speed - workers are dependent on internet speed
* lockout - if the cloud-based org decides to limit access to services, you may lose your information that is stored

### personalizing a web page with third-party applications

You can personalize with third party applications but it will slow down the functionality and usability of your Web page.

[iGoogle Portal](www.igoogleportal.com) is an example of a service that offers many third-party applications.

Googgle gadgets are mini-applications created with HTML and JavaScript. Instructions on how to create them can be found at the Gadgets API--Google Developers sit (https://developers.google.com/gadgets/). They are good examples of how apps can be created for mobile phones.

### web feeds

web feed is a data format that delivers and updates content frequently such as blog entries and news headlines

**two popular feeds**
* RSS (Really Simple Syndication, RDF Site Summary or Rich Site Summary)
Currently at version 2.0, RSS is the "original" family of web feeds. RSS 2.0 has the widest acceptance of any feed format.
* Atom
Currently at version 1.0, Atom is a relatively recent development but is much more robust and feature-rich than RSS.

**atom vs rss*
atom provides not only the document's content but also metadata about the document
* what it is called
* who created it
* when it was created
* where it is located

### podcasts
similar to RSS feed in that the use can download the audio or media files to a PC or portable media play.

podcast files can be syndicated, subscribed to and downloaded automatically as you add new content.

## end of lesson review
**Web 2.0**: A concept referring to the changing trends in the use of Web technology and design that have led to the development of information-sharing and collaboration capabilities

**Ajax**: A programming methodology that enables Web applications to interact with users in much the same way they do with desktop applications

**Cloud computing**: A computing paradigm in which users are able to access software and services over the Internet instead of from their desktops

**Application delivery platform**: A Web site that hosts applications and services that enable a user to perform computing tasks without the need to download and install any software

**Web feed**: A data format for delivering Web content that is updated frequently

**Podcast**:The use of audio or video digital-media files that are distributed through Web feeds to subscribed users

# web site development for business lesson 10
## developing a business web site

business that is just starting up, changing or expanding must perform key steps:
* identify a market need/opportunity
* identify a unique product/service to address the need/opportunity
* define the target market
* gather essential user info to help improve the company's product/ability to market/sell
* determine how the business can best communicate with the target market
* establish a brand for the product/service
* determine how to advertise the product/service including developing a web site and a social mead presence

### branding concepts

**brand** is a concept or collection of symbols with a product, service or person

brands should be:
* simple - easy to remember
* different - differentiate a company's product
* safe - doesn't inadvertently offend its target market
* make a promise - clearly express the most important benefits
* reflect the company's attributes - describe what the customer will experience
* reflect the company's personality - reflect the way the customer will feel
* appeal to the intended audience

## development and design

marketing is a key point in web development. It presents the business's product to potential customers in a way that they want to buy it and buy it from that company instead of someone else.

sample resources include:
* design & publishing center (www.graphic-design.com)
* website magazine (www.websitemagazine.com)
* a list apart (www.alistapart.com)
* cmyk magazine (www.cmykmag.com)
* computer graphics world (www.cgw.com)
* web designer magazine (www.webdesignermag.co.uk)
* layers magazine (www.layersmagazine.com)
* webdevforums.com (www.webdevforums.com)
* w3schools (www.w3schools.com)

### keep it simple

> customers do not read web pages, they scan them

structure page text so that it is easy for customers to scan. Highlighted keywords, meaningful subheadings and bulleted lists are way to capture customer's attention and help them find the information they are seeking.

convey business's central message in the first two paragraphs of the page and make sure all subheadings, paragraphs and bullet points start with appropriate keywords that users will notice as they scan the page.

effectively design pages
* crisp concise text
* one idea per paragraph
* search engine keywords in main portions of text
* convey central message using inverted-pyramid writing style, conclusion at top, followed by supporting information

## E-commerce considerations

* business-to-consumer (B2C)
* business-to-business (B2B)
* consumer-to-consumer (C2C)

## internet marketing and search engine optimization (SEO)

* branding - the creation of a distinctive identity and place in the market for a product or organization
* target market - the specific sector in a market that a product or service addresses
* demographics - the study of groups of people. included categorizing populations by interests, ethnicities, cultures and subcultures
* niche - a smaller specialized portion of the market
* mind share - the effect of marketing efforts influencing a particular target market or demographic e.g. commercial phrases, catch words and sound bites that provoke recognition of the product, service, company
* target date - the projected point in time that a product or service will be released
* aggregator - a business that markets and sells goods and services that it does not own or store. allows other vendors to compete using its site and then takes a percentage of the business, acts as a portal for an entire industry niche

**marketing terms**
* search engine optimization (SEO) - the use of specific techniques to increase a page's or site's rank on a search engine (such as Google, Yahoo! or Bing). "organic" because they do not include paid ads of any kind
  - experts must learn about and consider factors that search engines take into account as they rank sites
  - expected to lead users to a specific result or conversion
  - search engine providers collect data on all searches that users conduct on their engine and determine the correlation between keywords and results. sold as seach patterns
* pay per click (PPC) - marketing technique in which you pay for high search engine results by ads on keywords that describe your product or service, you pay you site hosts only when your ads are clicked by the user
  - not considered "organic"
  - good way to reach your target market and generate high-quality sales leads
  - most internet marketing campaigns combine SEO and PPC strategies
* web analytics - the practice of collecting data and studying user behavior in an attempt to increase market share and sales
  - on-site analytics - studying visitor behavior once that visitor has accessed your site, can use software such as WebTrends and Webalizer to review log files.
  - off-site analytics - determining potential audience and how site has addressed and penetrated a specific market
  - includes identifying the size of market, competitors, market penetration, conducting surveys and consulting market research sources

### what to consider when comparing services
* Price per keyword -	Make sure you compare prices carefully. If a particular PPC service is more effective or provides better services, paying extra may be worth it.
* Keyword generation service -	How does the service help you generate keywords? Does the service provide an engine, wizard or other interface for this purpose?
* Bidding options -	Many sites will prompt you to bid for keywords. Other sites will have fixed prices. You must determine which is appropriate for your business.
* Interface quality -	Ease of use is vital, because you may waste time trying to learn a difficult interface. You may also become discouraged if the interface is overly complex.
* Account fee	- Many sites require a fee to open an account.
* Monthly minimum -	Some services will charge you if you do not generate a minimum number of keyword hits per month.
* Software download	- Most sites are Web-based. But some services require you to install a software application.
* Additional features -	Write down additional features that you think will help your particular situation. These particular features might mean the difference between success and failure of your keyword campaign.
* Promotions	- Many PPC services have promotions that might save you money. However, make sure that these promotions do not cost you more money in the long run.

### review
* PPC (Pay per click): A technique that enables you to list your site high in search engine rankings by advertising on keywords that describe your product or service.
* Aggregator: A business (usually Web-based) that markets and sells good and services that it does not own or store.
* On-site Web analytics: The practice of studying visitor behavior once that visitor has accessed your site in an attempt to increase market share and sales.
* Search engine optimization (SEO): The process of improving the volume and quality of traffic to a Web site by structuring content to improve search engine ranking.
* Mind share: The effect of marketing efforts influencing a particular target market or demographic.
* Off-site Web analytics: The practice of determining your potential audience, and how well your site has addressed and penetrated that market.
* Branding: The creation of a distinctive identity and place in the market for a product or organization.

## E-commerce payment technologies

* **electronic funds transfer (EFT)** - generic term for transfer of funds using computers rather than paper
* **payment gateways** - hardware or software based system that mediates between a merchant and acquirer. End users do not configure their systems to become payment gateways.
* **3-d secure** - an XML-based protocol used by credit card companies to add security to online credit and debit card transactions.

### secure sockets layer (SSL)/ transport layer security (TLS)

tools used to secure transactions using encryption

**TLS** is similar to SSL but TLS is an open standard that is updated frequently

SSL and TLS are protocols that are included within transaction methods to secure transactions though encryption which can provide authentication, data confidentiality and data integrity. Many other methods exist but SSL/TLS is arguably the most universally applied.

#### SSL/TLS and public key infrastructure (PKI)

you need a certificate to enable host authentication before you can begin an SSl session and must participate in public key infrastructure (PKI). two parties that have never met can trust each other and encryption can begin. PKI involves two elements

* **digital certificate** - a signed public key that verifies a set of credentials associated with the public key of a certificate authority (CA). All SSL/TLS sessions require a valid certificate, acts as a third party to allow unknown parties to authenticate with each other and begin encryption
* **certificate authority (CA)** - a trusted third party that verifies the identity of the person or company that has submitted a certification request (CR). more than just a computer that issues digital certificates, a CA is an entire organization

### review
* Pay per click: An Internet marketing technique that enables you to list your site high in search engine rankings by advertising on keywords related to your product.
* SSL (Secure Sockets Layer): A protocol that provides authentication and encryption; used by most servers for secure exchanges over the Internet.
* Front-end issues: Factors that affect the accessibility and presentation of a Web page to an audience.
* Relational database: A collection of information that can be sorted, altered and placed into other similar structures for retrieval.
* Character set: The group of symbols used to render text on a page to support various languages (e.g., Chinese, Arabic and Russian).
* 3-D Secure: An XML-based protocol used by credit card companies to add security to online credit and debit card transactions.
* Back-end issues: Factors that affect the operations of a Web site, such as file download times, file names and file locations.
* Branding: The process of establishing name recognition for a company or product.
* TLS (Transport Layer Security): A secure transmission standard based on Secure Sockets Layer (SSL) that uses digital certificates to authenticate systems and to help enable subsequent encryption.
* Push technology: A communications method in which clients automatically receive new information about your product.

## working in a global environment

understand global issues

* currency differences
  - must be able to automatically calculate exchange rates for the day of the transaction (currency conversion)
  - must calculate tax, tariffs and additional costs
* international shipping
  - consider searches by customs
  - cost incurred by customs
  - delays by customs
  - all tariffs
* language concerns
  - target audience and characters necessary may require a different character set
  - specify unicode support for all of your site's web pages
  - www.unicode.org
* relationship management
  - trust-building
    - built through quality customer service
    - frequent contact
  - customer self-service
    - ability to track orders
    - customize orders (modify, cancel, change shipping)
    - choose products without the help of a live person

## databases and web pages

### web pages and CGI

Common Gateway Interface (CGI) are applications that help convey the information provided by the end user to the web server or database They use various computer languages:
* Perl
  - traditional CGI tech
  - due to relative longevity, perl is well known and is supported by many OSes.
  - renowned for stable
* PHP Hypertext Preprocessor
  - newer CGI tech that will run on multiple platforms
  - popular due to relative simplicity and ability to create powerful applications
* Active Server Pages (ASP)
  - older proprietary CGI tech for microsoft-specific systems
  - powerful because it is specially designed to work with the underlying OS
  - requires developers to learn VBScript and/or JavaScript
* .NET
  - microsoft standard dev platform
  - allows use of various languages (C#, JavaScipt, VBScript, Visual Basic).
  - microsofts latest effort to interconnect all internet-based servers.
  - more difficult to learn than VBScript, Perl or PHP
* JavaServer Pages (JSP)
  - universal CGI tech tha tuses the java interpreter
  - can create CGI using java
  - universal tech
  - more difficult than PHP or Perl but more powerfuland can create more stable applications
* ColdFusion
  - proprietary CGI tech
  - designed to be easier to install  and use than other interpreters/languages
  - more work with less code
* Python
  - open source CGI tech
  - emphasizes code readability with minimalistic code syntax and semantics
  - object-oriented
  - easily integrated with other languages
  - runs on windows, linux/unix, mac osx, os/2, amiga, palm handhelds, nokia mobile phones, etc.
  - ported to the java and .NET virtual machines
  - uses white space as block delimiters
* DJjango
  - open-source web framework written to help devs use the python language
  - meant to be a fast-dev platform
  - emphasizes DRY (do not repeat yourself)
* Ajax
  - CGI programming methodology that enables web applications to interact with users like they do desktop applications
  - create dynamic and interactive web pages without the need to refresh or reload
  - uses number of existing technologies together (HTML, CSS, the Document Object Model (DOM), JavaScript and XMLHttpRequest)
* Ruby
  - object-oriented language base on Perl and Smalltalk
  - powerful capabilities but easier to use than many other languages (Java and C#)
  - includes Ruby on Rails framework

### lesson review

* Perl: A traditional CGI technology that is platform-independent.
* PHP: A new CGI technology that will run on multiple platforms.
* Python: An open-source CGI technology that emphasizes code readability by employing minimalistic code syntax and semantics.
* .NET: A proprietary CGI technology that allows you to use various languages, including JavaScript, VBScript, Visual Basic or C#.
* JSP: A universal CGI technology that uses the Java interpreter.
* Django: An open-source Web framework that makes the creation of complex, database-driven Web sites easier by emphasizing the use of components that can be reused.
* ColdFusion: A proprietary CGI technology designed to be easier to install and use than other interpreters and languages.
* Ajax: A CGI programming methodology that enables Web applications to interact with users in much the same way they do with desktop applications.

## optimizing the impact of the web page
search engine companies consider many factors for SEO
* how many hyperlinks
* how informative is the page
* how well a page's code is structured
* how often the content on the page is updated

others:
* using properly validated HTML code
* applying cascading style sheets (CSS)
* structuring pages correctly

## front-end issues

a properly created web page should:
* be accessible by all users
* incorporate attractive images and graphical elements
* contain constantly updated hyperlinks and content
* use tables wisely (tables shouldn't be used to structure)_
* present carefully designed forms
* securely attach pages to databases
* use the most current technology appropriate
* use images sparingly
* be easily navigable without dead ends
* include alternative navigation links
  - if using image maps, provide standard hypertext links as well
  - many developers use image maps to define an entire page
    - although attractive can effectively exclude a page from search engine spiders

### site maps

should show the locations of all site sections

* topical hierarchy
  - clearly outline the site's sections
  - do not provide only a graphic as a site map
* aptly named site sections
  - named accurately
  - makes it easier for users to find what they're looking for
* search capability
  - visitors may not find exact info they're looking for
  - visitors can search for the resource they want

a useful site map is the product of proper site planning

### creative design and branding standards

#### design and branding standards meetings

generally focus on:
* target markets
* market messages
* media choices
* color combinations
* sales strategies
* technologies you want to use

#### audience development techniques

* provide standard web site features, properly placed video, audio and active content
* providing unique web site features such as ideas from you and your web team, input from other areas of the company
* using logos and other images traditionally used by the company
* coordinate efforts with traditional marketing. Ensure web site's look and feel complements the company's slicks and paper items
* tracking user visits, popular parts of site
* analyzing stats to increase web site efficiency e.g. ways to increase visitor time at locations where revenue is generated
* working with sales/marketing teams to obtain input from customers

**push tech** - email list, illegitimate example - spam
**pull tech** - info that is provided on request only (customer downloads a file or collect your email)
**visitor tracking** - any tech that provides number of visitors, length of time remained, frequency etc

### portals (aka *gateway*)

* **veritcal** portal dedicated to one specific interest or field like women's health or network security. Also called *vortal*. Each linked site on a vertical portal maintains a topical focus
  - CNET
  - slashdot
  - realestate.com
* **horizontal** - portal that provides links to various web site with no particular focus
  - google
  - yahoo

#### portal benefits
directs users to the best sites for a particular topic and helps them find info and products faster

benefits business because it can create a stream of customers who generate revenue. It can also help position its brand, recognition and strengthen the brand by comparing it with competitors.

### wiki sites
defined as a web site that allows all visitor to collaborate in its construction.

you can use wikis to create an information repository or portal. It uses specialized web-based software (wiki software) that allows any visitor to update the site using a web browser

most wiki pages are written in simplified markup language called LaTeX that accommodates the fast-paced nature of a wiki site

examples:
* Wikipedia
* LinuxQuestions.org
* BerliOS
* MemoryAlpha
* Wiki Base
* Wiki Choicetree
* JSPWiki

### documenting changes

as you make changes, keep a written record of all changes. practice of documenting changes to a site is called change management. it allows:
* remember which changes have been made to the HTML code and/or pages on the site
* ensure that you publish all security updates to the web server
* provide evidence of good-faith efforts to ensure accessibility
* verify that you have fulfilled requests from departments in your organization

## File Formats and Active Content

common file formats:

HTML	.html or .htm	HTML files.	text/html
XHTML	.html or .htm	XHTML files.	application/xhtml+html
Joint Photographic Experts Group (JPEG)	.jpeg or .jpg	A standard Web page image format. Provides variable image quality and compression algorithms to help reduce file size.	image/jpeg
Graphics Interchange Format (GIF)	.gif	A standard Web page image format. Does not provide native compression.

Two types of GIF exist:
-GIF87a (standard)
-GIF89a (animated GIF)

Animated GIFs show a series of embedded images, simulating motion. GIF files can also be interlaced for gradual display during a slow download.	image/gif
Portable Network Graphics (PNG)	.png	The newest standard Web page image format. Supports compression, and various quality levels and file sizes (the higher the image quality, the larger the file size). PNGs can also be animated.	image/png
Text	.txt	Standard (ASCII) text files.	text/plain
Cascading Style Sheets (CSS)	.css	CSS formatting is defined in text files, which can be attached to HTML documents to apply the defined styles.	text/css
Rich Text Format (RTF)	.rtf	Documents that contain simple formatting (e.g., underlining, bold, and font faces and sizes).	text/rtf
PostScript	.ps	A language designed to describe page formatting for text and graphics. Developed by Adobe, but has become an open standard.	application/postscript
Portable Document Format (PDF)	.pdf	Adobe Acrobat proprietary format, based on PostScript technology. Can retain sophisticated formatting and graphics.	application/pdf
Zip	.zip	Files compressed using the zip/unzip family of file applications.	application/zip
Pretty Good Privacy (PGP) / GNU Privacy Guard (GPG)	.pgp

.gpg	Files encrypted by PGP/GPG.	application/pgp-encrypted
application/gpg-encrypted
Moving Pictures Experts Group (MPEG) - audio	.mpeg	MPEG streaming audio.	audio/mpeg
MPEG - video	.mpeg	MPEG streaming video.	video/mpeg
MPEG Audio Layer 3 (MP3)	.mp3	MP3 audio file format.	audio/mp3
Ogg-Vorbis	.ogg	Ogg-Vorbis audio file format.	application/ogg
WAV	.wav	Native digital audio format of Windows operating systems.	audio/wav
audio/x-wav
RealPlayer	.ram, .ra	Audio and video files in the RealPlayer format (www.real.com).	audio/ram
audio/pn-realaudio ram
audio/x-realaudio ra
Word	.doc	Microsoft Word documents.	application/msword
Excel	.xls	Microsoft Excel documents (spreadsheets).	application/vnd.ms-excel
PowerPoint	.ppt	Microsoft PowerPoint documents (presentation slide shows).	application/vnd.ms-powerpoint
Unrecognized images	N/A	For any images and streaming media not currently standardized by IANA.	application/octet-stream

### proprietary formats and evaluating their use

* difficulty/inconvenience
  - some plug-ins and software may be difficult to obtain, download, install manage
  - may not be completely stable or introduce security vulnerabilities
* cost
  - some proprietary file formats (microsoft word) require software that must be purchased
  - you should consider free or open-source alternative for file formats
* audience limitation
  - some formats limit a disabled person's ability to obtain info
  - provide equivalent information in standard text format elsewhere on the site

## back-end issues

server resources that process and store user input are referred to as the back end of a web site.

### database connectivity

databases provide the ability to:
* present stored information to customers, allow them to search and retrieve
* receive information from customers and save it for later retrieval

many companies use database-enabled sites (Amazon.com, eBay, IBM, etc)

#### types of databses

* flat file - information stored in a single table, simple text file ex. windows registry
* non-relational - information stored statically, can be searched but cannot be reorganized or placed into another database
* relational - information can be sorted, altered and palced into other databses for retrieval
* object-oriented - a newer form with the capabilities of a relational database plus greater storage and search efficiency

#### relational databases

* store information intables
  - contain field that allow data int he tables to be cross-referened and join
  - you or database admin define categories and descriptions
* info can be updated
* when you conduct a search in a site such as eBay, you are using a web-enabled relational database
* can consist of a single file or can be distributed among several database servers

examples of relational database vendors:

* Oracle	You can learn more about the latest Oracle products at www.oracle.com.
* IBM	IBM's database product is called DB2. You can learn more about IBM products at www.ibm.com.
* Microsoft	Microsoft offers a database server product called SQL Server. You can learn more about Microsoft products at www.microsoft.com.
* MySQL	MySQL is an open-source database that will run on Linux, UNIX and Windows systems. You can learn more about MySQL at www.mysql.com.
* PostgreSQL	PostgreSQL is another open-source database product that is often considered to be more powerful and stable. You can learn more about PostgreSQL at www.postgresql.org.

#### structured query language (SQL)

can allow end users to determine the number of projects an employee finished by a certain date, can obtain a record that provides this info along with employee ID number and hire date

can create web page that allows end users to conduct queries through the page

#### database connection methods
* open database connectivity (ODBC)
  - primary purpose is to allow an operating system to register a database.
  - supports SQL and all major database vendors
  - once registered the OS and its components can easily read and udpate the database
  - ODBC was developed by Microsoft and is proprietary to Windows-based OSes
* java database connectivity (JDBC)
  - developed by Sun Microsystems
  - is not limited to Microsoft OSes
  - supports major vendors (e.g., IBM and Oracle)
  - supports SQL
  - can be run on various systems, including Windows and Unix
### indexing and cataloging

web site feature related to databases is the ability to index and catalog a site. more complex sites provide an internal search engine that allows visitors to conduct searches for site elements.

## Bandwidth and Download Time

transferring a 84 KB file

56Kbps speed - 56000 bits

84 KB = 84000 bytes * 8 = 672,000 bits

divide 672,000bits by 56000bits/sec = 12 secs

## naming web page files

may need to restrict the length of file names, should consider naming your HTML pages to correspond to their content. Sale form -> saleform.htm

must identify each file as the appropriate file type

### default files and http server

default page when user give a minimal amount of information. instead of typing www.company.com/index.html they can just type www.company.com

Micrsoft Internet Information Services (IIS) looks for default.htm

Apache HTTP server looks for index.html

every web server is preconfigured to a default document name such as:
* index.htm
* default.htm
* welcome.htm
* home.htm
* index.html
* default.html
* welcome.html
* home.html
* index.asp
* default.asp
* welcome.asp
* home.asp
* index.jsp
* default.jsp
* welcome.jsp
* home.jsp

### HTTP 404 - File Not Found error

shows that server is functioning but the specified file requested cannot be located (renamed or removed). Can also get it if  the request is using the wrong name.
