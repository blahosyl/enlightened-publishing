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

### Contact section

### Future implementations

### Accessibility

aria labels, alt text, colour scheme, font choices

## Technologies used

### Languages used

HTML, CSS

### Frameworks,  Libraries & Programs Used

Balsamiq – wireframes

Git – version control

GitHub – store the source files

[Google Fonts](https://fonts.google.com/) - import fonts used on the website

Google Dev Tools – troubleshoot, test responsivity and styling

FontAwsome – icons

<!--TinyPNG – compress images

Birne – resize images and convert to `webp` format
-->
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

### Accessibility testing
Wave
Web Disability Simulator

### Bugs

#### To Do

##### Insufficient contrast between hero image and text background (Problems & Solutions)

Experiment with different colors/opacities to improve legibility.
#### Known bugs

##### Nav element not aligned properly within header

There is some vertical space to the right of the `nav` element within the `header`, even though `justify-content: space-between;` is specified for the header with Flexbox.

Developer tools do not show any padding or margin on any of the elements (also checked the descendants: `ul` and `li`). 

Manually corrected using `margin: -2rem;` for now.

##### Substack logo

There is no Substack logo in Fontawesome, so the site is using a [solid bookmark](https://fontawesome.com/icons/bookmark?f=classic&s=solid) as a placeholder for the time being.

Explore the option of either 

 - using the [official logo](https://substack.com/brand) as an image, OR
 - [creating a new icon on Fontawesome](https://fontawesome.com/v5/docs/web/use-kits/upload-icons) (requres a PRO account).

#### Solved bugs

##### Favicon not showing up

When placing the favicon files in the `assets/favicon` directory, the code provided on [Favicon.io](https://favicon.io/emoji-favicons/books/) did not work, since it is written for the use case when files are placed in the root directory.

The code had to be modified to include the correct file paths for the favicon to show up correctly.

##### Sections do not extend all the way to the sides of the screen

When adding background colors to the `section` elements, rather than `main`, I have discovered some extra space around the sections. 

Using `padding: 10%;` rather than`margin: 10%;` for`main > section` partially solved the issue, but there was still some extra space left around the sections, even when the margin of `section` was set to `0`.

Using Developer Tools, I have discovered that the extra space corresponds to the padding of the `main` element. Setting `padding` to `0` for `main` solved the problem.

##### Link box of logo too wide

The `a` element containing the logo extended too far to the right on small screens, so that it almost overlapped with the hamburger menu. As a result, it was hard to choose which one to tap.

Adding `max-width` attributes to the `a` element (one for default, one for extra narrow screens) solved the issue.


## Credits

### Code

Variables https://www.w3schools.com/css/css3_variables.asp

[Recommended image sizes](https://tiny-img.com/blog/best-image-size-for-website/)

[Make the header sticky](https://gomakethings.com/how-to-create-a-sticky-navigation-with-only-css/)

[Pseudoclasses](https://www.w3schools.com/css/css_pseudo_classes.asp)


### Content

### Media

#### Images

[Substack logo](https://substack.com/brand)

The books favicon comes from [Favicon.io](https://favicon.io/emoji-favicons/books/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

[Fontawesome](https://fontawesome.com/)

[Hero image: Problems & Solutions section](https://www.pexels.com/photo/blue-and-green-sky-and-mountain-3617500/) by [Benjamin Suter](https://www.pexels.com/@benjaminjsuter/)

[Hero image: About section](https://raw.githubusercontent.com/blahosyl/academic-publishing/main/assets/images/curtrice-green-2.webp) by Benjamin Ward, colors modified to fit the site's color scheme by Peter Litauszki (with permission).

#### Videos

### Readme

[Creating your first README with Kera Cudmore](https://www.youtube.com/watch?v=XbYJ4VlhSnY)

[Bodelschwingher Hof](https://github.com/4n4ru/CI_MS1_BodelschwingherHof/tree/master) by Ana Runje

### Acknowledgements
