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

### Color scheme

Palette: Arctic, northern lights

Color arrangement inspiration: https://youpreneur.com/

2 salient colors combined with white, gray and black. 

Contrast between 2 salient colors: 7.75:1 ([WebAIM](https://webaim.org/resources/contrastchecker/))

<!--TODO: decide if we wanna introduce a 3rd salient color, like the green accents on hover-->

Color variables were used instead of hard-coding colors for each element, so that the overall color scheme can easily be modified in the future if needed. This was based on the [W3Schools tutorial on variables](https://www.w3schools.com/css/css3_variables.asp), a resource pointed out by my mentor.

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
#### Known bugs

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


## Credits

### Code

Variables https://www.w3schools.com/css/css3_variables.asp

[Recommended images sizes](https://tiny-img.com/blog/best-image-size-for-website/)


### Content

### Media

#### Images

[Substack logo](https://substack.com/brand)

The books favicon comes from [Favicon.io](https://favicon.io/emoji-favicons/books/), licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

[Fontawesome](https://fontawesome.com/)

#### Videos

### Readme

[Creating your first README with Kera Cudmore](https://www.youtube.com/watch?v=XbYJ4VlhSnY)

[Bodelschwingher Hof](https://github.com/4n4ru/CI_MS1_BodelschwingherHof/tree/master) by Ana Runje

### Acknowledgements
