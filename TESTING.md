# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

Feature-by-Feature Testing:

- Navigation: I've ensured smooth transitions between pages and the links direct to the correct destinations.
- Responsive Design: I have checked for compatibility across various devices and screen sizes.
- Images/Videos: I have made sure that all images and videos are at high quality on different screen sizes. 
- Display: I verified that each page were properly showcased with accurate descriptions, images, and links.
- Form: I tested the form submission process, ensuring the user receives a confirmation message.

<details>
<summary>Click here to see website on different size devices</summary>

- Mobile

![Mobile](documentation/screenshots/mobile.jpeg)

- Tablet

![Tablet](documentation)

- Laptop

![Laptop](documentation/screenshots/laptop.jpeg)

- Desktop

![Desktop](documentation)
</details>
<br>
User Experience Testing:

- Usability Testing: I had users interact with the site and provide feedback.
1. 
2.
3.
- Accessibility Testing: I checked screen reader compatibility, proper alt text for images, and keyboard navigation would work.

Compatibility Testing:

- Browser Compatibility: I tested on different browsers, to ensure consistent performance.

<details>
<summary>Click here to see the site on different browsers</summary>

- Firefox

[Firefox](documentation/screenshots/firefox.png)

- Safari

[Safari](documentation) 

- Chrome

[Chrome](documentation/screenshots/chrome.png)
</details>
<br>
- Device Compatibility: I ensured functionality across various devices.

<details>
<summary>Click here to see the site on different devices</summary>

- Huawei

![Huawei](documentation/screenshots/mobile.jpeg)

- Fire

![Fire](documentation)
</details>
<br>
- Performance Testing:
  - Speed and Load Testing: I used PageSpeed Insights to check page load times and optimized where necessary.
  ![screenshot]()
  - Scalability Testing: I assessed how the site handled increased traffic.
  ![screenshot] ()
Regression Testing:

Documentation and Logs:

  - Whilst inputting my Favicon I notice when screens were in dark mode the image was visibly flawed. To fix this I had to change to a more clearer icon. The issue: [screenshot](documentation/issues/dark-favicon.png). The fix: [screenshot](documentation/issues/light-favicon.png)  
User Feedback Incorporation:

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| documentation/validation/screenshot.png | index.html | ![screenshot](documentation/validation/screenshot.png) | no errors occurred when checking |
| documentation/validation/screenshot.png | gallery.html | ![screenshot](documentation/validation/screenshot.png) | no errors occurred when checking |
| documentation/validation/screenshot.png | form.html | ![screenshot](documentation/validation/screenshot.png) | no errors occurred when checking |
| documentation/validation/screenshot.png | 404.html | ![screenshot](documentation/validation/screenshot.png) | no errors occurred when checking |

## Browser Compatibility

- [Chrome](https://www.google.com/chrome)
- [Firefox](https://www.mozilla.org/firefox)
- [Edge](https://www.microsoft.com/edge)
- [Safari](https://support.apple.com/downloads/safari)

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Gallery | Form | 404 | Notes |
| --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/browsers/browser-chrome-home.png) | ![screenshot](documentation/browsers/browser-chrome-about.png) | ![screenshot](documentation/browsers/browser-chrome-contact.png) | ![screenshot](documentation/browsers/browser-chrome-etc.png) | Works as expected |
| Firefox | ![screenshot](documentation/browsers/browser-firefox-home.png) | ![screenshot](documentation/browsers/browser-firefox-about.png) | ![screenshot](documentation/browsers/browser-firefox-contact.png) | ![screenshot](documentation/browsers/browser-firefox-etc.png) | Works as expected |
| Edge | ![screenshot](documentation/browsers/browser-edge-home.png) | ![screenshot](documentation/browsers/browser-edge-about.png) | ![screenshot](documentation/browsers/browser-chrome-edge.png) | ![screenshot](documentation/browsers/browser-edge-etc.png) | Works as expected |
| Safari | ![screenshot](documentation/browsers/browser-safari-home.png) | ![screenshot](documentation/browsers/browser-safari-about.png) | ![screenshot](documentation/browsers/browser-safari-contact.png) | ![screenshot](documentation/browsers/browser-safari-etc.png) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Gallery | Form | 404 | Notes |
| --- | --- | --- | --- | --- | --- |
| Mobile | ![screenshot](documentation/responsiveness/responsive-mobile-home.png) | ![screenshot](documentation/responsiveness/responsive-mobile-about.png) | ![screenshot](documentation/responsiveness/responsive-mobile-contact.png) | ![screenshot](documentation/responsiveness/responsive-mobile-etc.png) | Works as expected |
| Tablet | ![screenshot](documentation/responsiveness/responsive-tablet-home.png) | ![screenshot](documentation/responsiveness/responsive-tablet-about.png) | ![screenshot](documentation/responsiveness/responsive-tablet-contact.png) | ![screenshot](documentation/responsiveness/responsive-tablet-etc.png) | Works as expected |
| Desktop | ![screenshot](documentation/responsiveness/responsive-desktop-home.png) | ![screenshot](documentation/responsiveness/responsive-desktop-about.png) | ![screenshot](documentation/responsiveness/responsive-desktop-contact.png) | ![screenshot](documentation/responsiveness/responsive-desktop-etc.png) | Works as expected |
| XL Screen | ![screenshot](documentation/responsiveness/responsive-xl-home.png) | ![screenshot](documentation/responsiveness/responsive-xl-about.png) | ![screenshot](documentation/responsiveness/responsive-xl-contact.png) | ![screenshot](documentation/responsiveness/responsive-xl-etc.png) | Scaling starts to have minor issues |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/lighthouse-home-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-home-desktop.png) | Some minor warnings |
| Gallery | ![screenshot](documentation/lighthouse/lighthouse-about-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-about-desktop.png) | Some minor warnings |
| Form | ![screenshot](documentation/lighthouse/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-gallery-desktop.png) | Some minor warnings |
| 404 | ![screenshot](documentation/lighthouse/lighthouse-gallery-mobile.png) | ![screenshot](documentation/lighthouse/lighthouse-gallery-desktop.png) | Some minor warnings |

## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to be able to quickly find where to stop, so that I can move on to decide what to pack. | ![screenshot](documentation/features/feature04.png) |
| As a new site user, I would like to change pages without having to scroll to the top of the screen, so that I can. | ![screenshot](documentation/features/feature04.png) |
| As a new site user, I would like to see a variety of images, so that I can see what Kuwait looks like. | ![screenshot](documentation/features/feature04.png) |
| As a new site user, I would like to see videos of what activities can be done, so that I can decide what I would like to do when I'm there. | ![screenshot](documentation/features/feature04.png) |
| As a new site user, I would like to be able to follow the websites social media, so that I can keep up to date with any new information. | ![screenshot](documentation/features/feature04.png) |
| As a returning site user, I would like to be able to keep my details in the form, so that I don't have to refill it every time I leave the site and return at a later date. | ![screenshot](documentation/features/feature07.png) |
| As a returning site user, I would like to be able to click on images and see them full-screen, so that I can see any particular image clearer. | ![screenshot](documentation/features/feature07.png) |
| As a returning site user, I would like to have easy to understand the information given, so that I can tell others about it. | ![screenshot](documentation/features/feature07.png) |
| As a returning site user, I would like to watch more videos, so that I can see different food establishments. | ![screenshot](documentation/features/feature07.png) |
| As a returning site user, I would like to be able to click on links that take me to specific accommodation, so that I can find out more about what they have to offer. | ![screenshot](documentation/features/feature07.png) |
| As a site administrator, I should be able to see statistics, so that I can monitor the websites usage. | ![screenshot](documentation/features/feature07.png) |
| As a site administrator, I should be able to be notified when a user submits the form, so that I can examine the information provided and reply. | ![screenshot](documentation/features/feature08.png) |
| As a site administrator, I should be able to monitor how many users click on certain external links, so that I can update links if needed. | ![screenshot](documentation/features/feature09.png) |

## Bugs

> [!NOTE]  
> There are no remaining bugs that I am aware of.