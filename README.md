# Horiseon-Search-Engine-Optimizations-Webpage--Edits-Updates

# 0. Project Overview: #

This was our first challenge through The Adelaide of Universits Coding bootcamp. our challenge was a mock up of an" on the the- Job Ticket&mdash" which meant we were given a starter code that we need to refactor and Modifiy. The starter code was missing key elements that were needed in order for the webpage to meet Accessibility standards and it was not optimzed for search engies. our job was to Refactor the code, make the webapge more Accessiible to the end user, espically those with health barries and by following the "Scout Rule" we nedded to leave the code cleaner then we have found it. through implmeting all we have learnt from our Teaching Staff, the website now meets Accesanbtly criteria, the code has been debugged and cleaned up with the website now being optimsezed for serach engies & with all CSS codes being corrently layed out and all links are now working as it should.  


# Table of Contents: #
                  0. my project overview
                  1. usefull information: HTML & CSS structure i have learnt 
                  2. three CODE REFACTOR TIME: how our starter code looked, what has changed and how it looks now
                  3. Installation: This sectition will tell you  clear and concise instructions on how to install and run my project.
                  4. Usage: This section will explain how to use my  project, including any relevant commands, functions , features.
                  5. Credits:This section will acknowledge any external resources, libraries, or tools that i have used for this project.
                  6. My contact information :if you have any Questions or conrners feel free to rach out.

# 1. Useful Information i learnt about HTML & CSS structure #
the below infromation has been submitted as a comment in my HTML code for the user to cleary see the reflelence and structure

<!DOCTYPE html> 

<!--the above states that our document type is HTML-->
<!--the html element repersents the root of an html document. ( root element)                                                                                          all other elemenets will be decendants of this element-->

<html lang="en-us"> 

<!--this tell us that inside the tag is an attribute of language and that
   the document is HTML- and the language is US English-->

<head> 

    <!--the head element contains information or metadata that helps the browser
    render the page correctly. most heads wont be seen by the End User.-->
    
 <meta charset="UTF-8" /> 
 
    <!--the head elelement contains the metadata. metadata is data about our
    webpage that the browser uses to deliver our webage to the end users
    it contains important information about accessibilty, search engines
    and performance-->
    
</head>

the character " <>" are used when opening, when closing as seen above we used </title> 
which is used when closing

<body> 

<!--the body element contains the context that is shown to the end user.
all the details we want the end user to see and
interact with are compiled in this element-->

<P> 

This tag allows the coder to define a block of text as a paragraph.

<u> 

this tag is called the underline tag which when used, underlines all text in the open and closed tags.

<h1> ..<h6>

headings that serve as titles for lines of text to help orgainse the information

<br>
forces a line in the text


# 2. Code Refactor: #
What our starter code looked like:

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>

<body>
    <div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
    <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    <div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>
</body>

</html>

# The Code now after it has been refactoerd & Debugged in HTML: # 

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8">
    <meta name="description" content="Horiseon offers digital marketing services including SEO, online reputation management, and social media marketing. Contact us to learn more."/>
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>;Horiseon - Digital Marketing Services</title>
</head>

<body>
    <header>
        <h1>Hori<span class="seo">seo</span></h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization"><Search Engine Optimization&lt />
                    </li>
                <li>
                    <a href="#online-reputation-management"><Online Reputation Management&lt;/>
                    </li>
                <li>
                    <a href="#social-media-marketing"><Social Media Marketing&lt />
                    </li>
                </ul>
            </nav>
        </header>

    <main>
        <section id="search-engine-optimization" />
            <h2>Search Engine Optimization></h2>
            <img src="./assets/images/search-engine-optimization.jpg" alt="Search Engine Optimization" />
            <p>Search engine optimization (SEO) is the practice of increasing the quantity and quality of traffic to your website through organic search engine results. </p>
    </section>

        <section id="online-reputation-management">
            <h2>Online Reputation Management</h2>
            <img src="./assets/images/online-reputation-management.jpg" alt="Online Reputation Management" />
            <p>;Online reputation management (ORM) involves monitoring, influencing, and protecting the online reputation of a brand or individual. </p>
        </section>

        <section id="social-media-marketing">
            <h2>;Social Media Marketing </h2>
            <img src="./assets/images/social-media-marketing.jpg" alt="Social Media Marketing" />
            <p>Social media marketing (SMM) is the use of social media platforms to connect with your audience to build your brand, increase sales, and drive website traffic. </p>
        <p></section>
        </main>

    <footer>
        <div class="footer">
            <h3>Contact Us</h3>
            <ul>
                <li>
                    <a href="tel:123-456-7890">123-456-7890</a>
                </li>
                <li>
                    <a href="mailto:horiseon@horiseon.com">;horiseon@horiseon.com</a>
                </li>
                <li>
                    <a href="./contact-us.html">Contact Form</a>
                </li>
            </ul>
        </div>
    </footer>

</body>

</html>






3. installation 

4 .Usage 

5.Credits: 

6.Contact:
