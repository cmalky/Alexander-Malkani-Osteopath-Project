# Alexander Malkani Osteopath

This project is built for an Osteopath looking to advertise his services through his website. 
This website is designed for clients to visit and gain more information about the treatments offered
before booking an appointment with the Osteopath. It is built more with providing information
in mind rather than selling services.
 
## UX
 
I built this project with new and returning clients in mind as a way for them to easily get in contact
with the Osteopath that would be working with them and to give them more insight on the treatments that
are offered.


The project is built to serve a few main functions:

- Provide an easy to use site that will be discoverable through the Osteopaths Google business search that can
help bring more traffic and clients by providing essential information and reassurance.
- Allow new and returning clients to learn more about the Osteopath that would be treating them should they
decide to make an appointment.
- Provide a site for new and returning clients to gain information on Osteopathic procedure and determine if 
Osteopathic treatment is the right course of action for them.

These are some user stories:

- As a client that requires treatment I need to know how I can contact the Osteopath, find opening and closing times,
and see where the Osteopath is situated so I can book an appointment or get a quote from the Osteopath.
- As a client that has a specific injury or ache I need to be able to have a look at some common treatments on the Osteopaths
website so that I can see if the Osteopath is suitable to treat my specific injury or ache.
- As a returning client I need an easy and accessible way to contact the Osteopath multiple times so I can continue to make
appointments should the injury or ache reoccur.
- As a client that may not be tech-savvy I need a website that is easy to navigate with clear directions so that I am not needlessly
confused when browsing the website.

I heavily utilized Bootstrap when creating this site as I believe it provides an amazing framework for
attractive and responsive websites. 

I tried to keep the website and colour pallette as minimalistic as possible to fit a doctors theme 
opting for white + black with an orange highlight to make certain items stand out. I designed the website this
way due to the varying ages of users that may visit the website. My goal was to keep the website concise,
making sure to include a call-to-action button on the index page that would lead the user to the treatments 
immediately so they can quickly make an informed decision if Osteopathy is right for them.

I built wireframes in Photoshop before I began the website to get a rough idea of what kind of design
I was going to be creating. You can view them below:

https://imgur.com/a/gVznwc3


## Features

 
### Existing Features

- The navbar collapses into a burger menu when the screen size gets smaller.

- The footer includes social media links which can be added to or changed should the Osteopath require.

Index 

- I included a bootstrap jumbotron with a call to action button on my front page to allow users to easily get to
the treatments page and make an informed decision by clicking the call to action button. The HTML for this 
can be viewed at the top of index.html and the styles are under the "CALLOUT" section of styles.css.

About Me 

- I included some testimonials on this page that I took from the Osteopaths Yell page, using FontAwesome
to provide Star icons for the ratings. These testimonials are on the Bootstrap grid system and so they are
fully responsive to screen size. I used Bootstraps blockquote styles for this. This allows users to see how the
Osteopath is rated in his field.

Treatments 

- I made use of the Bootstrap card accordion code and styles to make it easy for users to read summary of some 
common issues that the Osteopath can treat by clicking on the desired heading. The HTML for this can be viewed 
on treatment.html and the styles are under the "CARDS" section of styles.css.

Contact 

- I made sure to include a contact form alongside the workplace of the Osteopath. This allows users to enter 
their Name and E-mail and send a question directly to the Osteopath. This will allow users to get an evaluation
should they describe their symptoms and allow the user to engage with the Osteopath directly before treatment.

### Features Left to Implement

I have a few features that I would love to implement including:

- Google Maps iframe embed that would point the user to the location of the clinic where the Osteopath
works.

- A system to add a more comprehensive list of treatments that would allow more entries than the bootstrap 
accordion system.

## Technologies Used

- HTML & CSS
    - These languages are the core of the website.
- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap was used to provide attractive styling universally across all pages.
- [FontAwesome](https://fontawesome.com/)
    - FontAwesome was used to provide icons for the rating on the testimonials.


## Testing

Page(s) | Browser(s) | Resolution | Intended Result | Result | Notes
------------ | ------------ | ------------- | ------------ | ------------- | -------------
Home, About, Treatment, Contact | Google Chrome, Microsoft Edge, Firefox | Responsive, 27 inch screen | Testing screen resolution: Screen should adjust accordingly to the different screen and mobile sizes and be easily readable, maintaining ease of use. | Result as intended | Keeping the website fluent throughout multiple screen sizes will help users that aren't tech savvy.
Home | Google Chrome, Microsoft Edge, Firefox | Responsive, 27 inch screen | Testing hyperlink on jumbotron: hyperlink should take user straight to the Treatment page. | Result as intended | The call to action button will help streamline the experience for users immediately looking for treatment options.
Home, About, Treatment, Contact | Google Chrome, Microsoft Edge, Firefox | 1920x1080, 17.3 inch screen | Testing pages on smaller screen: Screen should adjust accordingly and be easily readable, mainting ease of use. | Result as intended | Making sure that there are no bugs or unintended changes on a smaller screen for users that have smaller laptops.
Treatment | Google Chrome, Microsoft Edge, Firefox | Responsive | Testing dropdowns: Dropdowns should stay well sized across screen sizes and work well. | Result as intended | The dropdowns were designed so to not overload the user with potentially unneccesary information.
About | Google Chrome, Microsoft Edge, Firefox | Responsive | Testing screen ordering: Testimonials should span vertically instead of horizontally on the screen when the screen size gets smaller. | Result as intended | Making sure the elements are spaced adequately and not cluttering the page.
Contact | Google Chrome, Microsoft Edge, Firefox | Responsive | Testing screen ordering: Contact page should move below the address information when the screen size gets smaller. | Result as intended | Making sure the elements are spaced adequately and not cluttering the page.
Home, About, Treatment, Contact | Google Chrome | Samsung S10, 2280x1080 | Phone testing: Website should work flawlessly and be easily readable on phone. | Result as intended | Testing to make sure the website works well on a real mobile device.

## Deployment

I deployed this website by taking the following steps:

1. Going to github.com and logging in to my account.
2. Choosing the project repository.
3. Opening the settings and scrolling down to "GitHub Pages"
4. Enabling GitHub Pages by selecting the master branch and the root folder.
5. Pressing save.
6. After a short wait the website should be deployed at https://cmalky.github.io/Alexander-Malkani-Osteopath-Project/

## Credits

### Content

Most of the text was copied from the Osteopaths previous website (https://www.alexandermalkaniosteopath.com/)

### Media

The photo's used on this site were obtained from the Osteopath. Icons were obtained from FontAwesome.

### Acknowledgements

I was inspired to make this project when I seen my Dad's current website and thought it would be a good
starting point for my project.