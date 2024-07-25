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

- Device Compatibility: I ensured functionality across various devices.

<details>
<summary>Click here to see the site on different devices</summary>

- Huawei

![Huawei](documentation/screenshots/mobile.jpeg)

- Dell

![Dell](documentation/screenshots/chrome.png)
</details>
<br>
Performance Testing:

- Speed and Load Testing: I used PageSpeed Insights to check page load times and optimized where necessary.

![screenshot]()

- Scalability Testing: I assessed how the site handled increased traffic.

![screenshot] ()

Regression Testing:

Documentation and Logs:

- Whilst inputting my Favicon I notice when screens were in dark mode the image was visibly flawed. To fix this I had to change to a more clearer icon. 
  - The issue: [screenshot](documentation/issues/dark-favicon.png) 
  - The fix: [screenshot](documentation/issues/light-favicon.png)
  
User Feedback Incorporation:

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| documentation/screenshot/ | index.html | ![screenshot](documentation) | no errors occurred when checking |
| documentation/screenshot | gallery.html | ![screenshot](documentation) | no errors occurred when checking |
| documentation/screenshot | form.html | ![screenshot](documentation) | no errors occurred when checking |
| documentation/screenshot | 404.html | ![screenshot](documentation) | no errors occurred when checking |
| documentation/screenshot | conformation.html | ![screenshot](documentation) | no errors occurred when checking |

### CSS

I have used the recommended [CSS W3C Validator](https://validator.w3.org) to validate my CSS file.

| Directory | File | Screenshot | Notes |
| --- | --- | --- | --- |
| documentation/validation/screenshot.png | css.styles | ![screenshot](documentation) | no errors occurred when checking |

## Browser Compatibility

- [Chrome](https://www.google.com/chrome)
- [Firefox](https://www.mozilla.org/firefox)
- [Edge](https://www.microsoft.com/edge)
- [Amazon Silk](https://www.amazon.co.uk/Amazon-com-Amazon-Silk-Web-Browser/dp/B01M35MQV4)

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Home | Gallery | Form | 404 | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Chrome | ![screenshot](documentation/screenshots/chrome-home.png) | ![screenshot](documentation/screenshots/chrome-gallery.png) | ![screenshot](documentation/screenshots/chrome.png) | ![screenshot](documentation/screenshots/chrome-404.png) | ![screenshot](documentation/screenshots/chrome-confirm.png) | Works as expected |
| Firefox | ![screenshot](documentation/screenshots/firefox.png) | ![screenshot](documentation/screenshots/firefox-gallery.png) | ![screenshot](documentation/screenshots/firefox-form.png) | ![screenshot](documentation/screenshots/firefox-404.png) | ![screenshot](documentation/screenshots/firefox-confirm.png) | Works as expected |
| Edge | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | Works as expected |
| Amazon Silk | ![screenshot](documentation/screenshots/tablet.jpeg) | ![screenshot](documentation/screenshots/amazon-gallery.jpeg) | ![screenshot](documentation/screenshots/amazon-form.jpeg) | ![screenshot](documentation/screenshots/amazon-404.jpeg) | ![screenshot](documentation/screenshots/amazon-confirm.jpeg) | Works as expected |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Home | Gallery | Form | 404 | Confirmation | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mobile | ![screenshot](documentation/screenshots/mob-home.jpeg) | ![screenshot](documentation/screenshots/mobile.jpeg) | ![screenshot](documentation/screenshots/mob-form.jpeg) | ![screenshot](documentation/screenshots/mob-404.jpeg) | ![screenshot](documentation/screenshots/mob-confirm.jpeg)  | Works as expected |
| Tablet | ![screenshot](documentation/screenshots/tablet.jpeg) | ![screenshot](documentation/screenshots/amazon-gallery.jpeg) | ![screenshot](documentation/screenshots/amazon-form.jpeg) | ![screenshot](documentation/screenshots/amazon-404.jpeg) | ![screenshot](documentation/screenshots/amazon-confirm.jpeg) | Works as expected |
| Desktop | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | Works as expected |
| XL Screen | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | ![screenshot](documentation) | Scaling starts to have minor issues |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Mobile | Desktop | Notes |
| --- | --- | --- | --- |
| Home | ![screenshot](documentation) | ![screenshot](documentation) | Some minor warnings |
| Gallery | ![screenshot](documentation) | ![screenshot](documentation) | Some minor warnings |
| Form | ![screenshot](documentation) | ![screenshot](documentation) | Some minor warnings |
| 404 | ![screenshot](documentation) | ![screenshot](documentation) | Some minor warnings |
| Confirmation | ![screenshot](documentation) | ![screenshot](documentation) | Some minor warnings |

## User Story Testing

| User Story | Screenshot |
| --- | --- |
| As a new site user, I would like to be able to quickly find where to stop, so that I can move on to decide what to pack. | ![screenshot](documentation) |
| As a new site user, I would like to change pages without having to scroll to the top of the screen, so that I can. | ![screenshot](documentation) |
| As a new site user, I would like to see a variety of images, so that I can see what Kuwait looks like. | ![screenshot](documentation) |
| As a new site user, I would like to see videos of what activities can be done, so that I can decide what I would like to do when I'm there. | ![screenshot](documentation) |
| As a new site user, I would like to be able to follow the websites social media, so that I can keep up to date with any new information. | ![screenshot](documentation) |
| As a returning site user, I would like to be able to keep my details in the form, so that I don't have to refill it every time I leave the site and return at a later date. | ![screenshot](documentation) |
| As a returning site user, I would like to be able to click on images and see them full-screen, so that I can see any particular image clearer. | ![screenshot](documentation) |
| As a returning site user, I would like to be able to easily understand the information given, so that I can tell others about it. | ![screenshot](documentation) |
| As a returning site user, I would like to watch more videos, so that I can see different food establishments. | ![screenshot](documentation) |
| As a returning site user, I would like to be able to click on links that take me to specific accommodation, so that I can find out more about what they have to offer. | ![screenshot](documentation) |
| As a site administrator, I should be able to see statistics, so that I can monitor the websites usage. | ![screenshot](documentation) |
| As a site administrator, I should be able to be notified when a user submits the form, so that I can examine the information provided and reply. | ![screenshot](documentation) |
| As a site administrator, I should be able to monitor how many users click on certain external links, so that I can update links if needed. | ![screenshot](documentation/) |

## Bugs

> [!NOTE]  
> There are no remaining bugs that I am aware of.