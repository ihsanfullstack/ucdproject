# User Centric Design - Project

This project is designed to showcase and highlight the great music made by the Blasters, one of my favourite bands. 
It's goal is to provide the end user with excitement and inspiration such that they would possibly like to see the band play live, and to allow them to book tickets should they wish. 
The content is design to be just enough to fulfill this aim/goal. It is also my intention to show this to the band too, as I feel their existing site leaves a little to be desired. 
**Please note I'm entirely new to this and I have not had a mentor for this project**

# UX

The UX for this site is to keep things simple and eaay to navigate. The website is intended for, as an example, John Doe - Persona

John is 48 years old and loves music, 
he particularly likes music that brings him back to his younger days when things were fun and life was light. 
John is not a digital native so he likes websites that are easy to use and intuitive. 

The User Stories used are as follows 

 As a User I want to know about the blasters so that I can become excited and get a feel for the band
 
 As a User I want to see some shows to show my friends when we're together to get them interested
 
 As a User I want to be able to know of upcoming gig dates and book them if I like 
 
 As a user I want to be able to easily navigate this site so that I can glide from page to page
 
 As a user I want to be able to get emailed when shows are coming upcoming
 
 As a user I want to be able to use this site on my mobile without needing desktop to get the full experience
 
When designing the wifeframes I worked on paper, since I was not collaborating as I find it easier to think 'out loud'. link here - https://drive.google.com/open?id=17yhxLTSB_SjBYFy8eUZxHcU75gvSQcbZ


# Features


## Existing Features

##### Feature 1 - allows users to sign up to get info about upcoming shows to their email by filling out the form in modal 

##### Feature 2 - allows users to go to the social media pages of the band

##### Feature 3 - navbar - allows users to intuitively navigate to the parts of the site that they want to get to

##### Feature 4 - Allows users to view the gallery and look at nice pics of the band and enlarge through touch/click

##### Feature 5 - allows users to see upcoming shows and book if they wish


### Features Left to Improve

The booking function is left to improve, in that it doesn't work fully, i.e. doesn't re-direct

The pictures in gallery.html - I couldn't figure out how to ge them to change based on hovering although this doesn't affect the mobile experience - I think I needed javascript for this 

The videos embedded via youtube on the tunes page load slowly, I'd like to speed this up - this is something I should perhaps do locally.

All in all the only thing I'd maybe tweak going forward would be the color palette - it seems to work and does look nice, but this would be an improvement, and having done some SCSS I'd use variables to do this so as to quickly change and test new palettes.

I would also like to fully build out the search our site functionality and then include in this a seperate html page which would display content on the site that contained key words that a user searched for - this I think is helpful for the person who goes there with a clear outcome in mind and doesn't want to browse.

### Technologies Used

Bootstrap, used to style everything, minimal CSS used (embedded) - https://getbootstrap.com/
jquery and some javascript plugins, which were provided though I used these as bootstrap told me to in order to run the modals etc. 
Any CSS used was done in embedded form, this really was because bootstrap did so much of the work for me.


# Testing

For my testing this was limited simply because my site is static and doesn't have any functionaltiy, as I understand this is the scope of the assignment. 

The main testing occured simply by using google developer tools, and viewing the site on all different screen sizes for every different page, including testing the modals.

I went through all pages, and tried every piece of them - they we're all fine. This is of course thanks to bootstrap. 

The site responds to re-sizing well I must say, it looks better in fact on mobile that it does on desktop. 

That's the central reason I left the background image of the site to repeat itself, it actually seems more atmospheric - I asked some friends their opinion and they mostly concluded which I thought was good evidence. 

Other things that I tested were the modals and if they worked etc, again I didn't code and functionality into them like returning errors etc I understand that's outside of the scope and would require javascript. 

# Deployment

I have deployed the project using github pages. 
This was done simply by setting up same on the repository on github where I placed the files.
When it comes to version control, since most of the page styling is the same, I added the footers, headers etc as commits and then just committed each page as a new piece of functionality, it seemed to make sense that way. I must also admit that the I initially didn't use github when coding the site, since it took me a bit of trial and error to get things to work and I simply saved them in cloud9, but I did commit the main pieces. 
In order to run the code locally for this project, simply download all html files, ignoring the css style sheet since any css is embedded, and run same. There have been no differences in both versions, except I did find I needed to change the way the pictures were called in terms of file paths once hosted on githubpages, hence the last minute or latest commits. 


# Credits
## Content
The text for section in About was copied from the Wikipedia article found by searching for the Blasters
The content for the quotes from the band were too found on their site
## Media
The photos used in this site were obtained from the Blasters' current live website
## Acknowledgements
I received inspiration for this project from fleetwoodmac.com, pbp.ie
