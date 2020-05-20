# Scouse Daxie - README

A social space targeting Dachshund owners in Liverpool. The site aims to provide community through existing social media and free organsied social events. The site offers advice and tips on dog friendly bars, pubs, restaurants and other venues/establishments along with training tips and 3rd party training in the area.

The site could eventually generate revenue through attracting local businesses and suppliers to advertise or promote their relevant offerings. One future option is to create an online store platform selling relevant products either directly or in acting as an intermediary.

Whist the site currently heavily relies upon existing social media platforms for inter-user interaction, user to business interaction and events sign-up and bookings the intention is to build thie functionality locally into the site with time.

The site can expand to include additional content for other dog breeds in the geographic area and also expand to other locations in the future. By narrowing the target audience initially it allows bespoke, attractive content and a managable scope. Choosing a popular breed increases the interest in the content and initial user pick-up.

## UX Design
The Scouse Daxie site was designed following a User Experience Design process which established a set of goals for the core user groups, the minimum viable product to achieve these goals and future development potential. 
The scope set out the required pages and content based on several developed user stories.
An initial site structure was outlined and with a proposed future expansion as content and coverage increased. 
Wireframes provided a means of limiting mission creep and making key decisions prior to the commencement of coding.
Colour schemes, font types and icons were all researched and in advance and a colour palette and template font-family code added to the initial styles.css file for ease of use and consitency. 

A review meeting refined the initial plan, scaling back the number of pages by combining several in singular pages, and the colour palette and fonts were revised to ensure visual contrast and readibility. The use of free logo making utilies was also advised to reduce the number of utilised fonts.
### Strategy
The following Users were identified and their goals established:

#### The Business

* Establish a go-to brand for the Dachshund Owners in Liverpool (UK).
    * First port of call for owners looking for advice on caring for their dogs, training, behaviour, most appropriate items for the breed i.e. harnesses, collars, jackets etc.
* Build a network of users who “crowd-source” potential future site content i.e. new advice or tips.
* Highlight the popularity of dog-friendly venues in Liverpool to encourage more venues to become dog friendly.
* Work with venues to advise on top tips for becoming dog friendly.
* Encourage venues to advertise on the site (potential revenue).
* Encourage manufacturers/suppliers to advertise products on site (potential revenue).
* Launch regular free events such as group walks, playdates and meetups.
    * This could eventually lead to paid/ticketed events (potential revenue).

#### General Consumers

* Receive sound advice and provide best possible care for their dog(s).
* Recommendations on products. 
* Confidence in attending venues with the knowledge it caters for dogs well. 
* Socialisation of both the owners and their dogs. 
    * Remotely (via social media)
    * Physically (walks, events)
* Show off their pride and joy
    * Image/video sharing
* Show of their knowledge
    * User to user interaction. 

#### Other 3rd Party businesses

* Increase revenue
* Create repeat custom
* Reach specific target market
* Diversify
* Potentially enter e-commerce via a 3rd party (i.e. the site). 

#### Minimum Viable Product
The mimimum product required to achieve the majority of the above goals was defined as requiring:

* A regular events calendar
* Non-interactive "dog-friendly" venue guidance.
* Non-interactive training and training provider advice.
* Links to established social media pages to provide interactivity.

An Opportunity Importance vs Feasibility assessment was carried out: [Opportunity Assessment PDF](assets/docs/opportunity_assessment.pdf)

### Scope

The scope of the project was to initially create a fun, catchy, visually appealling site and establish brand recognition. Written content was to be kept minimal and of value to the user. 
At this stage user interactivty must be provided by external social media. 
The aim was to build a site which focuses on satifying the **General Consumers** and **The Businesses** goals on the premise that establishing these will contribute towards brand appeal with the **3rd Party Business** user group and assist in achieving this groups goals.

The scope identified the following as required content:
* Homepage.
    * Introduction to brand and purpose.
    * Highlight key content.
* Dog-Friendly venues page.
    * Immediate content with value to **General Consumers**.
    * Links to **3rd Party Businesses** eventually attracting collaboration.
    * Provide advice to **3rd Party Businesses** on how to qualify for inclusion.
* Training Tips Page.
    * Training advice is always sought by **General Consumers**. The inclusion of this content will increase traffic on the site. 
    * Providing professional training reccomendations again provides buy-in for **3rd Party Businesses**.
* Events page. 
    * Builds community.
    * Encourages interaction and repeat engagement. 
    * Promotion through word-of-mouth. 

User stories were created for representatives of each core user group. 

User | Story
-----|-------
The Business | [The Businesses User Story](assets/docs/the_business_user_story.pdf)
General Consumer | [The General Consumer User Story](assets/docs/general_consumer_user_story.pdf)
3rd Party Businesses | [3rd Party Businesses User Story](assets/docs/3rd_party_business_user_story.pdf)

### Structure
As an unestablished brand it is critical that the structure provide an intuitive, rewarding and positive user experience. 
All users will be unfamiliar with the site and if navigating it proves difficult the user is unlikely to return. 

The header and footer will be common across all pages to improve familiarity across the site. 

The inital navigation structure was planned in a simple tree, minimising the number of clicks for the user. All pages are accessible from all other pages thanks to the common header and footer. 

![Planned Site Structure](assets/images/planned_structure.PNG)

This was revised following the initial planning meeting to further reduce the site complexity by merging the sub-pages into their parent pages i.e. "How to become a dog friendly venue" content is present on the "Dog Friendly" page.

A possible future structure was also proposed should business goals be achieved and the scope of the brand, the site and its content expands. 

The purpose of the revised structure would be to reduce the reliance on external social media platforms and increase the potential user base by expanding across different dog breeds and different geographic locations. 

As an aside this is the justification for the inclusion of a strapline or sub-heading, as this would form the overarching brand as currently the main brand is both geographically and breed constrained. 

![Planned Site Structure](assets/images/future_structure.PNG)

The expanded structure would segregate geographic content, and breed specific content within that and add in common features such as an online store. 

### Skeleton

### Surface

Where possible the use of absolute units has been avoided in preference for relative units. This is to ensure maximum site responsiveness.

## Features

### Existing Features

### Future Features

Tooltips on venue icons.

Subscribe form functionality. 

* Event sign-up on site
    * Replace social media signup
* Product review/advice
* On site store for products
* Site Gallery
    * User photo/video upload
    * Requires administrator review/approval


## Technologies Used

### Bootstrap 4.4.1

Bootstrap was used to provide a front-end component library structure and responsive design framework.

#### License

The MIT License (MIT)

Copyright (c) 2011-2020 Twitter, Inc.
Copyright (c) 2011-2020 The Bootstrap Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

### LogoMakr

Produced the brand logo using a combination of Google Fonts and icons.

https://logomakr.com

https://logomakr.com/getstarted/terms-conditions/

### Google Fonts

Google Fonts offers open source font styling options for personal and commercial use.

#### License

The use of this product was inline with Google API's terms of service https://developers.google.com/terms

### Font Awesome 5.1.3.

Font Awesome provides text based icons which can be manipulated and controlled by CSS styling.

#### License

Icons are licensed under the CC BY 4.0 https://creativecommons.org/licenses/by/4.0/

Fonts are licensed under SIL OFL 1.1 https://scripts.sil.org/OFL

Code is licensed under MIT https://opensource.org/licenses/MIT

### Google Maps

Specific maps were created in Google Maps highlighting specific groups of locations. these were embedded as iframes into various pages on the site.

#### License

The use of this product was inline with Google API's terms of service https://cloud.google.com/maps-platform/terms?_ga=2.160045053.1717626391.1589905262-667397718.1588149057

## Testing

## Deployment

## Credits

### Content

Site content is original and developed by the author to offer an opinion and reccomendation in good faith. No liability is assumed for any user experiences outside of this website.

The content was correct to the best of the authors knowledge at the time of issue.

The content was created without outside influence including but not limited to payment for advertisement or promotion and bias based upon personal relationships and experiences.

### Media

All images are originals and the property of the author and subject to copyright restrictions and limitations.

All videos are orginals and the propery of the author and subject to copyright restrictions and limitations.

The logo was created by the author in logomakr online tool and is accredited as per the instruction of the tool's developer. It is subject to copyright restrictions and limitations

### Acknowledgements
