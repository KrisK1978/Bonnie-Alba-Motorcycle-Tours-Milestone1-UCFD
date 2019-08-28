
# BONNIE ALBA MOTORCYCLE TOURS


**Bonnie Alba Motorcycle Tours** is my very first website created as a part of **User Centric Front-End Development**. 
It is my Milestone 1 project and confirmation of my coding skills I had gained since started the Full-Stack Web 
Developer course provided by [Code Institute](https://codeinstitute.net/). 



## Demo
***


The website live demo can be found <a href="https://krisk1978.github.io/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/">***here***</a>



***UX***


1.	My goal:


The main purpose for creating Bonnie Alba Motorcycle Tours was to provide helpful information to 
a specific user/audience, in this case motorcycle enthusiasts who would like to tour Scotland on a motorcycle, 
but also to any website visitor who wants to learn more about interesting places in Scotland. 
This website is designed to be easy to navigate and will frequently updated in order to keep users coming back for more information. 


2.	Website additional information:


•	if a website user would like to have access to a newsletter there will be requirement to complete a sign-in form;

•	the website is available in both English and Polish language;

•	an access to Shop section with a possibility to purchase motorcycle-related products e.g. helmets or gloves;




***Client stories***

1.	Client’s (website visitor) expectations:


-	As a new visitor, I am expecting to find the website user-friendly and easy to navigate;

-	As a new visitor, I am looking to find the information efficiently;

-	As a new visitor, I want to learn more about the country I am planning to visit and get some specific details about interesting places to visit;

-	As a new visitor and potential client, I want to have an easy access to the products offered in the Shop and fully understand the purchasing process;

-	As a new visitor, I am expecting a straightforward contact form, so getting in touch with the website host would not be complicated;

-	As a new visitor, I am hoping to stay connected with the website host using the available social media, so I can be up to date with the news, planned venues, etc. 




***Wireframes***


I have used Balsamiq to create wireframe mockups to represent the project’s structure and the way the website would look like.


• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/Home%20Page.pdf">Home Page</a>

• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/About%20Us%20Page.pdf">About Us...</a>

• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/Tours%20Guide%20Page.pdf">Tours Guide</a>

• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/Gallery%20Page.pdf">Gallery</a>

• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/Shop%20Page.pdf">Shop</a>

• <a href="https://github.com/KrisK1978/Bonnie-Alba-Motorcycle-Tours-Milestone1-UCFD/blob/master/wireframes/Get%20in%20Touch.pdf">Get in touch...</a>


***Features***


All pages consist a responsive navigation bar with a logo (motorcycle related icon) located in right-top corner.
When users click on the logo it will return them to the home page (applied in both English and Polish version).
Each page has a different background-image and an active language-button located in navbar which once tapped will 
transfer the user to Polish version of the website. This will give the non-English speaker users an opportunity to 
access information in their native language. The footer has a copyright information and social media icons which will 
link the user to the website owner social media pages (the size and colour of social media icons will change when using 
a hover function).


**Home Page**


The Home Page features a motorcycle-related image (background) which was converted to grayscale to grab attention and to 
build a nice connection with the website users. There is also an active 'Sign Up!' button applied on the Home Page. 
It is a modal's element and when clicked it will provide the user with additional information e.g. a chance to receive 10% 
voucher to be used in the Shop section.



**About Us... Page**


The About Us... Page has paragraphs added which contain a brief description of Scotland and interesting places to visit.



**Tours Guide Page**


The Tours Guide gives the user an opportunity to access the following information:

•   tour destination and duration;

•   tour description;

•   places worth to visit;

•   tour map (the map extends when clicked, it opens in a new window and has interesting places marked on the map);



**Gallery Page**


The Gallery Page consists several images laid out in columns. The number of columns depend on the type of the device. 
Each photo has a caption and can be clicked to open in a modal window. The user can view the content in a bigger size and the image can be closed by using 'X' sign. The image has a grayscale filter applied and the image scale changes when using a hover function.



**Shop Page**


The Shop Page gives the user an opportunity to purchase a range of motorcycle products. I used a 'card' component to create the Shop section.
Each card has the following elements: 

•   product image (each image will extend its size when clicked, modal function applied);

•   product title;

•   product price;

•   product description;

•	'Add to Cart' & 'Remove from Cart' buttons (the button's background changes when using a hover function);

•   Subtotal, Tax, Shipping Cost & Total amount;



**Get in touch… Page**


The Get in touch page features a simple contact from which consists the following elements:

•	Full name;

•   Telephone number;

•	Email address;

•	Reason for Contact;

•	Message box;

•	‘Send’ button;

The form cannot be submitted without completing all fields. If a field is left blank a warning note will
pop-out with the following message **‘! Please fill in this field’**. There is also an address label located 
below the contact form with the Bonnie Alba Motorcycle Tours contact details. 



***Features to Implement in future***


In the future, I would like to improve the following sections of the website to make it more attractive and user-friendly: 

•	upgrading the content of About Us section by adding more information;

•	updating the Tours Guide section by adding more tours e.g. enhanced description & detailed maps;

•	upgrading the Gallery section by adding video clips related to Scotland’s best motorcycle routes;

•	adding more products to the Shop section and apply a specific JavaScript function which will automatically calculate the total amount of the purchased items;

•	adding GDPR complaint pop-up screen to Get in touch section



***Technologies Used***


The following technologies have been used in the project completion process:

•   HTML which defines the properties and behaviours of web page content  

•   CSS which describes how HTML elements should be displayed on the screen 


•   <a href="https://getbootstrap.com/docs/4.3/getting-started/introduction/">Bootstrap v4.3.1</a> to make the website responsive and user-friendly

•   <a href="https://cdnjs.com/libraries/font-awesome/5.8.2">Font Awesome v5.8.2</a> to control the way the icon looks  

•   <a href="https://fonts.google.com/">Google Fonts</a> responsible for styling the website fonts 

•   <a href="https://autoprefixer.github.io/">Autoprefixer</a> to add vendor prefixes to CSS and make sure the CSS code is valid for all browsers

•   <a href="https://fancyapps.com/fancybox/3/">Fancybox</a> used for a gallery modal popup to view gallery images.

•   <a href="https://jquery.com/download/">jQuery v3.4.1</a> to standardize and simplify interactions between HTML elements and JavaScript code

•   <a href="https://cdnjs.com/libraries/popper.js/1.14.7">Popper.js</a> to calculate the position of an element and required for the responsive navbar

•   <a href="https://www.favicon-generator.org/">Favicon</a> to represent the website


***Project Testing***


More information about the project testing can be found in 



***Deployment***


The website is hosted using GitHub pages and can be deployed directly from the 
<a href=”https://github.com/KrisK1978/milestone-project1-bamt-ucfd”>master branch</a>
Initially the project was developed using the <a href=”https://c9.io/login”>Cloud9</a> 
IDE but due to a long-planned platform upgrade it had been migrated to a new Amazon Website Services account.


***Credits***


**Content**


The content in the **Home, About Us…, Tours Guide, Gallery, Shop & Get in touch** pages was written by me. 



**Media**


The photos used in the project, including background and gallery images, were taken from:


•	https://www.motorcyclescotland.com


•	https://www.guidedmotorbiketours.co.uk


•	https://dailyrecord.co.uk 


•	https://mallelondon.com 


•	https://www.mslmagazine.co.uk 



***Acknowledgements***


I received a motivation and inspiration for this project from my own and my friend's riding experience. I am a motorcycle enthusiast and 
I had a chance to visit most beautiful places in Scotland. I thought it would be good to share my experience with others who 
are planning to visit Scotland on the motorbike but would need some practical advice. 

I also received a useful advice and support from my mentor Simen Daehlin who guided me through the project phases.  



**Disclaimer**

Please note the website was created for educational purposes only.
