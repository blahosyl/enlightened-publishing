Deployed page: [https://blahosyl.github.io/academic-publishing/](https://blahosyl.github.io/academic-publishing/)

# Academic Publishing

## User Experience (UX)

### User stories

#### Client goals

#### First-time visitor goals

#### Returning visitor goals

#### Frequent visitor goals

Find new material

## Design

### Flow

The client heavily preferred a continuous website rather than separate clickable pages, citing results that show that user engagement drastically decreases after each time a user has to click.

In accordance with this, the website consists of 3, visually separate sections that can be continuously scrolled through:

1. Problems & Solutions
2. About/Credentials
3. Contact

To ease navigation, the header remains visible throughout.

### Problems & Solutions section

#### Colors and images

The problems subsection features a dark color scheme, grayscale images with a dark tint, and images suggesting overwhelm.

The Solutions section has a bright colored background and color images that are only slightly tinted with the same bright color.

#### Layout

Each subsection consists of 2 text boxes, each with an accompanying image. The text appears below the image on mobile, and next to it on tablets and larger screens. 

For the side-by-side arrangement, every second image-text pair is reversed, so that the image appears alternately on the left and the right side of the image.

In the Problems section, the cut-off point between the image and text is at the same place. In the Solutions section, the text/image width ration is the same in the two boxes. Both arrangements create a similar but subtly different symmetry. 

### About/Credentials section

This section details the relevant past experience of the client. After a hero image and a short introductory text, the different jobs/positions/experiences are presented in a responsive grid. By default, only the institution and position title (XXX logo?) is visible; details are uncovered on tap (mobile, tablet) or hover (laptop/desktop).

### Contact section

### Color scheme

Palette: Arctic, northern lights

Color arrangement inspiration: [https://youpreneur.com/](https://youpreneur.com/)

2 salient colors combined with white, gray and black. 

Contrast between 2 salient colors: 7.75:1 ([WebAIM](https://webaim.org/resources/contrastchecker/))

<!--TODO: decide if we wanna introduce a 3rd salient color, like the green accents on hover-->

Color variables were used instead of hard-coding colors for each element, so that the overall color scheme can easily be modified in the future if needed. This was based on the [W3Schools tutorial on variables](https://www.w3schools.com/css/css3_variables.asp), a resource pointed out by my mentor.

### Images

The [hero image of the Problems & Solutions section](https://www.pexels.com/photo/blue-and-green-sky-and-mountain-3617500/) shows an arctic landsape with mountains, water, and northern lights. It alludes to the client's professional background in Norway. The northern lights evoke a sense of awe and hope (light in the darkness).


The [hero image of the about section](https://raw.githubusercontent.com/blahosyl/academic-publishing/main/assets/images/curtrice-green-2.webp) shows the client in a confident pose in front of a grafitti wall. It centers the client as both competent and approachable. 

### Typography

[Google Fonts](https://fonts.google.com/) are used in this project. The client chose [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab?subset=latin&noto.script=Latn) for headings, and [Lato](https://fonts.google.com/specimen/Lato?subset=latin&noto.script=Latn) for normal text.



### Imagery

### Wireframes

## Features

### Logo

### Nav bar

### Footer with social media links

### Problems and solutions section

### About section

#### Credential cards

The client's relevant experience is displayed on individual cards to avoid creating a large block of text and break up the information into smaller, digestible pieces.

The cards are arranged in a responsive grid using Flexbox, similarly to the "running times" section of the Love Running project.

Additionally, the information within each card is divided into 2, and presented as a result of user interaction:

- By default, each cards shows the name of the institution/organisation, the position the client held there, as well as the logo XXXX. 
- When the user taps or hovers over a card (depending on the type of device used), this information is replaced by a more detailed description of the client's experience. 

In accordance with my mentor's suggestion, I have added explicit text to tap or hover for more information. I have decided to add this text to each card rather than just adding it once above the card block, because I consider it better for accessibility. The tap/hover text is also visually different from the rest of the text on the card, to make the functionality more explicit.


### Contact section

### Future implementations

### Accessibility

aria labels, alt text, colour scheme, font choices

## Technologies used

### Languages used

HTML, CSS

### Frameworks,  Libraries & Programs Used

Atom – code editor

Balsamiq – wireframes

Git – version control

GitHub – store the source files

GitHub Desktop – GitHub UI

[Google Fonts](https://fonts.google.com/) - import fonts used on the website

Google Dev Tools – troubleshoot, test responsivity and styling

FontAwsome – icons

<!--TinyPNG – compress images

-->

[Birme](https://www.birme.net/) – resize images and convert to `webp` format

Favicon.io – create the favicon

Am I Responsive? – to show the website image on a range of devices

<!--Shields.io – add badges to README
-->
[Coolors.co](https://coolors.co/) - color palettes, 

[WebAIM](https://webaim.org/resources/contrastchecker/) – color contrast checking

[Lipsum](https://www.lipsum.com/), [loremipsum.io](https://loremipsum.io/) – Lorem Ipsum generators

[Pixelied](https://pixelied.com/convert/jpg-converter/jpg-to-webp) – `jpg` to `webp` converter

## Deployment

## Testing

### Automated testing
W3C validator
Lighthouse

### Manual testing
Testing user stories
Full testing of functionalities

####Footer

The links to the client's social media accounts open in a new tab.

### Accessibility testing
Wave
Web Disability Simulator

### Bugs

[Known](https://github.com/blahosyl/love-running/issues) and [solved](https://github.com/blahosyl/love-running/issues?q=is%3Aissue+is%3Aclosed) bugs are handled in [GitHub Issues](https://github.com/blahosyl/love-running/issues/).

## Credits

### Code

Variables https://www.w3schools.com/css/css3_variables.asp

[Recommended image sizes](https://tiny-img.com/blog/best-image-size-for-website/), [2](https://www.foregroundweb.com/image-size)

[Make the header sticky](https://gomakethings.com/how-to-create-a-sticky-navigation-with-only-css/)

[Pseudoclasses](https://www.w3schools.com/css/css_pseudo_classes.asp) (credential cards)

[Push 1 paragraph to to bottom of container without affecting the rest](https://stackoverflow.com/a/39613036) (credential cards)

[`filter`](https://www.w3schools.com/cssref/css3_pr_filter.php)

[hue-rotate](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/hue-rotate), [2](https://www.quackit.com/css/functions/css_hue-rotate_function.cfm)

[calculate filter](https://stackoverflow.com/a/73824920), [2](https://isotropic.co/tool/hex-color-to-css-filter/)

[`iframe`](https://www.w3schools.com/html/html_youtube.asp)

[Embedding YouTube videos](https://www.lifelearn.com/2019/02/25/youtube-videos-on-your-website/#:~:text=To%20sort%20which%20videos%20you,embed%20functionality%20has%20been%20enabled.)

### Content

### Media

#### Images

[Substack logo](https://substack.com/brand)

The books favicon comes from [Favicon.io](https://favicon.io/emoji-favicons/books/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

[Fontawesome](https://fontawesome.com/)

[Hero image](https://www.pexels.com/photo/blue-and-green-sky-and-mountain-3617500/) by [Benjamin Suter](https://www.pexels.com/@benjaminjsuter/)

[CLient image in the Problems & Solutions section](https://raw.githubusercontent.com/blahosyl/academic-publishing/main/assets/images/presentation.webp) by Benjamin Ward, modified to reduce optical noise by Peter Litauszki (with permission).

[Client image: About section](https://raw.githubusercontent.com/blahosyl/academic-publishing/main/assets/images/curtrice-green-2.webp) by Benjamin Ward, colors modified to fit the site's color scheme by Peter Litauszki (with permission).

#### Videos

### Readme

[Creating your first README with Kera Cudmore](https://www.youtube.com/watch?v=XbYJ4VlhSnY)

[Bodelschwingher Hof](https://github.com/4n4ru/CI_MS1_BodelschwingherHof/tree/master) by Ana Runje

### Acknowledgements
