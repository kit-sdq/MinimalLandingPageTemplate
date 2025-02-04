# Minimal Landing Page Template

| ![Desktop Image](docs/desktop.png) | ![Mobile Image](docs/mobile.png) |
|-|-|

## Customization

### Logo

Change the logo by replacing the src of the image on line 15.
https://github.com/kit-sdq/MinimalLandingPageTemplate/blob/62e1d51061aa175f9b377d8bbbeb0bbe1161adba/index.html#L15


### Favicon

To change the favicon replace the href of the link on line 9 with your desired favicon.

### Title

Change the tile by replacing the text on line 6.

https://github.com/kit-sdq/MinimalLandingPageTemplate/blob/62e1d51061aa175f9b377d8bbbeb0bbe1161adba/index.html#L6

The two headings can be changed on lines 18 and 19.
https://github.com/kit-sdq/MinimalLandingPageTemplate/blob/62e1d51061aa175f9b377d8bbbeb0bbe1161adba/index.html#L18-L19

### Adding a link

To add a new link copy the following code and paste it into `div#link-list`, so that the link is placed in the desired place.

```html
<a href="" class="link-N icon">
  <i class="fa-solid fa-vials"></i>
</a>
<a href="" class="link-N text">
  <span class="title">Title</span> <span class="desc">Longer describtion</span>
</a>
```

Change the `href` of both links to the desired location.
In the `i` change the icon to be the desired Font Awesome icon.
Change the text in the spans with class `title` and `desc` to the desired text.
`title` is the short description that is always displayed on mobile and colorful on desktop.
`desc` is the longer description that is only displayed on desktop.

Add this code to the style section:
```css
.link-N {
  --col: #000;
}
```

Change the value of the `--col` variable to the desired color of the icon.
You can change the `N` in the class name to any desired text. Make sure to also adjust this class accordingly in the html you pasted previously.

Lastly change the `--link-count` variable to the new total link count:
https://github.com/kit-sdq/MinimalLandingPageTemplate/blob/62e1d51061aa175f9b377d8bbbeb0bbe1161adba/index.html#L46

### Icon size
The icon size on the desktop can be changed here:
https://github.com/kit-sdq/MinimalLandingPageTemplate/blob/62e1d51061aa175f9b377d8bbbeb0bbe1161adba/index.html#L47
