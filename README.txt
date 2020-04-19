1c. Accessibility Guidelines Applied:
Four Core Principles: Perceivable, Operable, Understandable, Robust.
‘Perceivable’ concerns the user’s ability to see or hear the content.
‘Operable’ concerns the user’s ability to operate the interface. 
‘Understandable’ concerns the user’s ability to understand the information conveyed in the web application.
‘Robust’ concerns the user’s ability to access the information and the interface through a variety of technologies, and evolving assistive technologies. 

These principles have been covered by using the design techniques as follows:
Use of consistent top menu Nav across all pages with the inclusion of the logo and a banner immage.
Content can be accessed with the keyboard alone in a logical way by using the tab button and shift tab to move forwards and backwards through the website page navigation links.
Use of clear easy to read font. Font applied = Arial
Use of headings to organise content using the appropriate tags <h1> or <h2> etc.
Colour is used with care. Providing a consistent colour palette across all pages and a clear uncluttered background using the colour white. 
CSS styling is used where appropriate to design the layout of the pages and add various useabiltiy functions 
- Even though red is used which may cause concern for colourblind users, it is not used to differentiate important functions or information. It is used as stand-alone heading colours which could just as easily be read as a grey scale colour if the red could not be differentiated.
Home page includes the use of tag <em> for the Welcome message in Maori. Foreign language should be in italics.
And providing the tag <em> will allow a screen reader to portray a different tone of voice to emphasise the welcome that it needs to exude.
Home page tag <strong> at the name of the restaurant while displays in bold like a bold tag would, being <strong> again allows a screen reader to provide an important voice tone for the restaurant name - which is very important to remember!
All images contain alt tags. E.g. Home page fish dish image has the tag alt="Fish of the day served with side salad". This will allow a screen reader to describe that image on the page.
In conjunction with the image alt tags, they also all contain a tag title, e.g. title="Fish" so that anyone not sure what the image is, can hover over it to see the short title of the image.
The form on the Rervations page allows tabbing between fields in addition to using the mouse for point and click navigation.
All interfaces are simple and meet common norms. E.g:
- navigation is simple to follow, the page title clearly shows what page you are on.
- the top nav shows an underline when you hover over a navigation link
- the navigation links within a page such as the Beverages link on the Meun page, are underlined to indicate a link and also show in bold upon hover over of the link
- feedback is provided when the Reservations form is submitted by way of a popup window to proceed to another reservation of you can click back to a web page.
ARIA roles are used to identify landmarks on each webpage. E.g. Home page role="navigation" attribute is used to define the navigation landmark. Similar roles used to identify 'main' and 'header'.
-Landmarks provide a way to identify the organisation and structure of a web page. Use of landmarks roles support keyboard navigation and the structure of a page for screen reader users.

1e. Security Issues:
Role of HTTP caching:
HTTP cache is a web cache to store information received in response to requests for use in responding to future requests. Hence, webpages, images, multimedia are temporarily stored for easier recall upon conditions being met, to reduce server lag.

Role of Content Delivery Networks:
CDN is a geographically distributed network of proxy servers and their data centres with the goal to provide high availability and performance by distributing the service spatially relative to end users.

Security Issues to be aware of:
Web developers should work with a security model such as the Parkerian hexad security model.
It describes six information security attributes with the aim of creating a complete security model covering the following attributes:
-confidentiality and availability
-authenticity
-possession or control
-utility
In consideration of The Haukai Restaurant website, security attributes might include:
- confidentiality - booking details which contain name and phone numbers, and future development pages to buy vouchers which include the submission of bank details. These need to be kept secure from potential hackers gaining access to the website.
- integrity - as with confidentiality except a hacker might use their access to modify a user name, phone number or other booking details.
- authenticity - to assure the information exchnage is from the claimed souce, so need to ensure a hacker can't create a copy of the website and direct users to the fake site to collect user information.
- possession - the actual physical possession of the media. This may not be an issue in this website unless the reservation bookings or voucher purchases were to be downloaded onto a USB or printed for reference.
- utility - a hacker might insert random data into the database with fake bookings or voucher purchases which will create irrelevant data.