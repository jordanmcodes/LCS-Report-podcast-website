# LCS Report Podcast website

## What is the purpose for the website?
This website is to provide a central hub for the fans of the LCS Report podcast. A place where they will be able to stay up to date on the latest videos while also providing a place for those who are impaired and may not be able to see the videos, our descriptions next to each video will give them all of the information they need. It's designed to give them a clearer way of accessing all of our content. 

## What value does my website provide?
Users will be able to find the latest episodes with in-depth video descriptions next to each episode. Our website embeds the youtube videos onto the page so once they are done with one episode, they can move onto the next. 

## How you can deploy the website
You can either access the website through this link: https://jordanmcodes.github.io/LCS-Report-podcast-website/index.html

### Or you can deploy the website yourself:

- Download the repository from github here: https://github.com/jordanmcodes/LCS-Report-podcast-website
- Ensure all html, css and asset files are in the same structure that I have in place
- Push the repository that you have just downloaded to github, enabling the pages in the repository settings
- Wait for github to produce a working link

# Code that is from external sources: 

My navigation bar design was guided by W3Schools (https://www.w3schools.com/howto/howto_js_topnav.asp)

My navbar list was inspired by Bro Codez on YouTube (https://www.youtube.com/@BroCodez)

My footer design was inspired by W3Schools (https://www.w3schools.com/howto/howto_css_fixed_footer.asp)

### Code written by me
All other code for the website was created by me and inspired from the countles lectures by NCC London. This includes the html for each page, the css for layout, colors etc, and the embedded youtube videos. 
## Website design using wireframes
This website will be a simple yet effective website for my LCS Report podcast. This will give our audience a place to see all of our content under one roof. 

## Navigation bar + structured layout
The website will follow a simple three button navigation bar. This navigation bar will appear at the top of every page on the website, each button will link to the desired page you want to access. 

Each page will follow a simple layout that the audience can clearly navigate through without any difficulty. Here is how each page is structured. 

**Home page**: The homepage will have the heading at the top of the page underneath the navigation bar, followed by an introduction piece of text, welcoming the viewers to the website. Followed by the featured image below, this will be our most recent episode so you're never out of the loop.

**Podcast page** : This will be where the bulk of the content is displayed. Again below the navigation bar there will be a heading and an introduction block of text that will go over the page and explain about how this page will be updated in a timely fashion to accomodate the new episodes on the page.

Each episode will have an image that is hyperlinked to the podcast episode with a heading of the episode and a description next to it. 

**Contact us page**: This page is where the fans will get to contact the podcast to ask any burning questions, podcast feedback, and more. Below the navigation bar will be the heading asking them to please get in touch, with more information on when we can answer questions, what is allowed to be asked, and more. This is followed by a form with a simple email, twitter handle, and comment form.
Here is how each page will playout:

**Home**: 
- h1: LCS Report Podcast
- p: introduction text
- video:featured video block


**Podcast**
- h1: Our Latest Episodes!
- p : introduction text
- img:three image blocks that are hyperlinked to external pages.

Having the navigation bar in the same position helps the design remain consistent, making the website accessible for its users as the position of the navigation bar and its buttons will be in the same place. 

## Wireframe for the home page
![Home page](Assets/Images/home-wireframe.png)

## Wireframe for the podcast page
![Podcast](Assets/Images/podcast-wireframe.png)

## Wireframe for the contact us page 
![Contact us](Assets/Images/contact-wireframe.png)

## How I will make my website accessible 
My website will be easy to read due to the stark contrast differences between the colors I will be using on the website. In the podcasts graphics on youtube, we use a darker blue background combined with golden borders, graphics etc. This will be the same for the website. I will use the same background image for the website, with the navigation bar being the same golden color used in the podcast itself.

All of my headings will be clear and easy to read. This is so that people that need to use screen readers will be able to quickly identify what is on the page. 

Every image where applicable will have accurate alternative text that informs the reader of what the image is about. When there is hyperlinks, the alternative text will describe the page they are going to rather as that is the reason they are hovering over the hyperlink in the first place.

The readers will have an easy time navigating my website because the navigation bar will remain the same position throughout, the buttons will not animate, and the colors will remain the same so the users have the same experience regardless of what page they are on. 

Going back to the background, it will be clear and not distract the users away from the website. 

Autoplaying videos are annoying, which is why every video on the website will have to be played manually. 

Font size and font used will be consistent throughout, making them both easy to read. 

For youtube videos opening in a new tab. YouTube has a built in feature for websites that allows you to open a new tab simply through clicking the title of the video. 

## Organization
The information on every page will be displayed in a clear and precise manner. Underneath the navigation bar on each page of my website there will be a large h1/h2 clearly explaining what page you are on.

Because this is a podcast, these videos are prioritised to be placed higher on the pages where applicable. For example, the home page. The featured video will be displayed underneath the introduction paragraph, allowing for the audience to dive right into the content. 

To understand what page you are on even clearer, the button on the navigation bar will have a slight color change, indicating that this is the page you are on. Each hyperlink will go from one page to the next, meaning there is no broken navigation chain, you can go from page to page as many times as you want. 

All videos on the podcast page will open a popup video, these videos will not automatically play as this can become irritating to the spectating audience. 

When the user opens up the home page. They will know what the content is about immediately. Our opening paragraph and featured video will be the hook. So when they open the site, they will see the large navigation bar, then the introduction paragraph, followed by a large featured video.

Each page will follow a header, paragraph, and content formula. 


## CSS Validate
![CSS Validate](Assets/Images/css-validate.png)

## index page validate
![index validate](Assets/Images/index-validate.png)

## podcast page validate
![podcast validate](Assets/Images/podcast-validate.png)

## contact page validate
![contact validate](Assets/Images/contact-validate.png)

# Finished home page
![home page](Assets/Images/home-page.png)

As a user, the main thing that I want to see from this home page is an idea of what the podcast is about. I want to see a description and featured video from the jump

# Finished podcast page
![podcast page](Assets/Images/podcast-page.png)

As a user, the main thing I want from a podcast page is to see the full list of episodes available. Having more than one is important to me, so I want to make sure that I am seeing a full variety of episodes.

# Finished Contact page
![contact page](Assets/Images/contact-page.png)
As a user, I want an easy way to contact the podcast I am a fan of. This should allow me to send a message, as long as I want, to the podcast and know they are going to be recieving it. 

# Finished navigation
![navigation](Assets/Images/navigation.png)
As a user, I want the navigation bar to be clear and precise. I want when I hover over a button to know what I am hovering over. 

# All code from outside sources

/* Styling of the footer courtesy of W3 schools */
.footer{
    position: fixed;
    bottom: 0;
    width: 1000px;
    background-color:#ebca99;
    color: black;
    text-align: center;
}

/*nav bar design courtesy of Bro Code on YouTube */
.navbar ul  {
    list-style-type: none;
    background-color:#ffbd59;
    padding: 0;
    overflow: hidden;
    margin:0;
    overflow: hidden;
    display: flex;
    justify-content: center;
     font-size: 30px;
}

/* Navigation bar design from W3 schools */
.navbar {
    width: 1000px;
    margin: 0 auto;
    text-align: center;
}

# Code separation
All website code - html and css was written by me. Any code that is commented was inspired by outside sources clearly identified in the css code. 

# Testing

### Navigation Bar

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
| Home Button | Click home button | The page will reset | Page resets |
| Podcast Button | Clock podcast button | The website will navigate to podcast page | Website navigates to podcast page | 
| Contact Us Button | Click Contact Us Button | Website will navigate to Contact Us Page | Website navigates to Contact Us page | 

### Home Page Content 

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
|Featured Video | Click play on the video | Video will play | Video plays sucessfully on the page | 
|Intro text | Read text on page | Text is readable | Text is displayed clearly | 
| Video layout | Resize window | Video and content stays centered | Layout remains consistent 

### Podcast page content 

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
| Ep 1 | Click play on video | Video will play | Video plays |
| Ep 2 | Click play on video | Video will play | Video plays |
| Ep 3 | Click play on video | Video will play | Video plays |
| Episode text | Read text on screen | Text is readable | Text displayed is readable | 
| Video layout | Resize window | videos remain centered | Layout is consistent |

### Content Page 

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
| Email | Type an email | Text appears | Text works correctly | 
| X handle input | Type X handle | Text appears | Text works correctly | 
| Comment area | Type comment | Text Appears | Text works correctly |
| Submit button | Click submit | Form submits | Button works correctly | 

### Responsiveness 

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
| Navigation bar | Resize window | Buttons stack | Buttons remain useable | 
| Page content | Resize window | Videos stay centered | layout remains same 
| Footer | Resize window | Footer remains at bottom | Footer behaves correctly | 

### Accessibility 

| Website feature | Action | Expected Result | Actual Result |
|-----------------|--------|-----------------|---------------|
|Videos | Check alt text | Each video has an alt text for users | Alt text is correct | 
| Colours | Check colours | All colours work well and don't clash | Colours mesh well | 
| Aria labels | Inspect | Each video has descriptive aria label | labels are present 
