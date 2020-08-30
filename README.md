## Milestone Project Gold

# Motivation
_I created this project to allow users to make purchases through the webiste. For a good user experience I wanted to allow the user to 
create an account, reset password, login, logout, add items to the cart and then checkout. I chose to use a very simplistic approach so 
it was easy to navigate around._     

# Naming And inspiration

I chose this name due to the software name given my many companies to the software update they release, gold meaning the final version as this 
is my final project. To me this was the best name I could of given as this being my last project I went "milestoneprojectgold"_


### Navigation Bar
_For my page I wanted to keep a simple feel to the website so I placed the title to the left, and on the right hand side went with links
as I feel most websites user have been on have links placed on this side. I felt this would users a familarity when navigating through my website.
The colour scheme I chose goes really well as its a bright orange and the black background combines with it quite well._

## Credits
_This is a project which was created only for a project purpose and the images have been used which all credits go microsoft xbox and sony
playstation. I do not take credit for any of the content and the content was just used as I wanted to create console gift card website
where the user can make purchases.

## Backgrounds

_For my final project I trialled a number of backgrounds but I decided to go with a black background as I felt it would work well with
 the orange I chose for the navigation bar. The colours were difficult because I wanted a gaming site feel and at the same time I did not
 want to use a blue or green because those colours are associated with the xbox and playstation. In the end I went with a black background
 as the white boxes which the gift card names and descriptions are included in. The white boxes really stand out with the black colour, giving
 my site a really strong colour scheme for the user to experience as they are navigation around. I did have diffiuclty with this, as normally
 any changes made to my css file would show up. On this occasion when ever I made a change I had to enter the code python3 manage.py collectstatic
into the terminal so it would save the changes made, then python3 manage.py runserver so I can view the changes on the developmental server.


# Technologies

#### HTML

_The html was used to create a general layout for the website and for other features of the site such forms for users to type in usernames 
and passwords to log on, type in formation in the search bar to look for gift card. Also, to fill in details on the payment screen such as,
name, address, contact information, payment details etc._

#### CSS

_The css style sheet I used was for my own personal styling in addition to the bootstrap and font awesome style sheets you will find. This was 
al down to bring the html code to life. Without this, the website would of just looked like page with text and no real style when users are 
navigating around the website._

#### STRIPE

_I installed the stripe platform through my django to allow users to make payments simply safely and securely. This was one the best Technologies
I could of used as I simply use the code such as thier own scripts, which meant all the whole process was easier as stripe would take care of 
most of the hassle, I just had to use the correct scripting and create a form which used "url 'checkout'", within the form and that meant users 
could type in thier details. Also, it would print an error message if users entered incorrect information because of the id I used 
"stripe-error-message"._

#### AWS
_This was the hardest part as I had some issues with my images not showing up due to access denied status, the images would show up on aws but 
not when the user was view the products. For this technology to work I had to create a bucket which is basically an area that included my saved
files for them to be pushed back to the user for them to view. Once I had done since I had to generated code for my bucket policy using the on-site
generator, which gave the code to paste in that section. After this had been done, I also had to enter the CORS configuration which was given
to me in the course section. Finally, I used the sites IAM, which is basically a management console which allowed me to create a group and user
for my policy. I found it hard as I was following one set of instructions but then told to use another which actually caused trouble within my code.
AWS was good though for allowing me to store all my files such media, static, admin etc securely online. It took me a little while to get used to submitting
css changes as in the past I would save changes and it would appear. On this occasion I had to use the "python3 manage.py collectstatic". so the changes would 
be saved for me then to view this on the developmental server._


#### FONT AWESOME
_I used font awesome to help me that styling, this made it whole lot easier I simply placed this along with other scripts in my "base.html" file
which used a block element and I placed this in other files so all the code in "base.html" would move other. In terms of font awesome, using span tags
and i classes I could simply use names of icons from font awesome and as I had the script in "base.html" it would add the icons bringing my forms
to life, just adding to the whole visual experience of the user._

####  BOOTSTRAP
_The bootstrap technology was very smart in allowing my to use the code generated on their site to build a navigation bar easily and quickly. 
It is very effective because it does the hard work for you, as you are simply using a script like font awesome and that will allow the changes
to be pulled through. Bootstrap is really useful as you can simply add text the div for your navigation and it will do the rest for you._

# TESTING

#### NAVIGATION BAR

_I had some issues with changing the colour of my navigation bar as even when I made changes to my css file "custom.css", it would not reflect 
so I had to go into inspect element and simply use the navbar class to add the colour along with the code "!important", this helped me change
the colour apart from the left and right hand side, for that I had adjust the margin left and margin right so it gaved me an orange navbar.
This was difficult as it kept on bringing up the blue colour which was set by default so had difficulty as that was still coming through.
It tooks me hours as using different classes to target the navigation bar until finally I could make the changes_.

#### HTML Validator 

Using the html validator from the site ("https://validator.w3.org/") allowed me to work through my code and remove errors. 
I have found over the time I have done this course difficulty if with certain syntax errors but by using the validator it makes it easier
to spot the error and to resolve the problem. In my experience sometimes I had fixed one part of my code but it would bring up another error.
The validator highlights the line number  which meant I could easily dintinguish a typo or another code which was causing me problems._

#### CSS Validator 

_I used CSS Validator which is simply highlight errors within my css. This helped me a great deal as it reduced the time I would have to spend
looking for the code to correct if I had any issue with the css. There wasn't too much css I used compared to the past but I did find it useful
when positioning my product boxes and also making changes to my navigation. I felt by simply it highlighted any errors allowed me to work quicker._For

#### GITHUB

_I found github to be of great use here as I could roll back data if I needed to. This was good to have this because I could see where I have gone wrong.
Using terminal on gitpod I checked which of my files were commited by using (git status).This allowed me to then add my files using (git add .) and then using 
(git status) again I could see they have been submitted. To complete this I would then use ("git push") which allowed my changes to be submitted so my site can 
be viewed online. I really found this to be much easier with gitpod intergration as I did not need to log on, which before could be difficult as your password your 
typing does not show up on screen. I did not need to manaully create a repository as this was already done as I created the workspace through github then selecting clone
which is plugin linking my github with my gitpod._

# DEPLOYMENT

_Using gitpod I pushed my project online, using the terminal I entered "git status", to see which files I had not commited, this showed me the files that were not pushed
in a red colour, I used "git commit -m "[commit message here]", After this I pushed the project online by using command "git push". This I found very easy to do as my gitpod is    
connected to my github, I had an issue with my workspace dissapearing, so I went online to github and using the gitpod plugin, It allow me to select the button and push
my github repository onto gitpod. After this had been done, now I can run my code " index.html" file, by simply entering into the terminal " python3 -m http.server, then clicking
in the bottom blue toolbar onto the ports section, expose the port 8000, then this will allow it to  be run in a browser to view " index.html"._
#### CONTENT

_The information entered for my product description have been taken from the sources in the links found below, these were simply used for 
project purposes and again no credit taken for these links listed below:
"https://www.argos.co.uk/product/1251731" and "https://www.argos.co.uk/product/4999186", some of the information was used and edited again
for purpose of this project._

# CREDITS

#### MEDIA

_The images used for my website were taken online from "https://i.pinimg.com/originals/a6/74/16/a67416d326106bd2638b9ba14d252cf4.jpg" and 
"https://miro.medium.com/max/1280/1*nnbVjvhYDduj0KKBTvhiDQ.jpeg", these images were found through a search on  "https://www.google.com/". 
I do not take credit for any images used above in them links listed._

#### ACKNOWLEDGEMENTS
_A big thank to all the tutors at code institute support, as I extreme difficulty completing this due to my personal health and situation but am
happy to be able to complete this project. This has been a big journey into the world of coding, I have given everything to this from working in the
mornings on my code, to finishing my job and carry on coding in the evening. I just want to say also big thank you to the mentors I have worked with
and hope I carry my journey in become a succesfull developer in the near future._
# Created and Edited by Michael Singh