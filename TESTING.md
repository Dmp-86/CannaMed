# Testing

Return back to the [README.md](README.md) file.

## Code Validation


### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

- I used this link to validate my live deployed site: https://validator.w3.org/#validate_by_uri
- I used this link to validate my divert html code: https://validator.w3.org/#validate_by_input


| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDmp-86.github.io%2FCannaMed%2Findex.html) | ![screenshot](documentation/w3-check1.png) | Pass: No Errors |
| Gallery | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDmp-86.github.io%2FCannaMed%2Findex.html) | ![screenshot](documentation/w3-check2-gal.png) | Initial error - Section lacks header h2-h6 warning. Converted section to a div, negating the need for h2-h6 elements. End result: Pass: No Errors |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2FDmp-86.github.io%2FCannaMed%2Fcontact.html) | ![screenshot](documentation/w3-check3-cont.png) | Pass: No Errors |
| Divert | [W3C](https://validator.w3.org/nu/#textarea) | ![screenshot](documentation/w3-check4-divert.png) | Pass: No Errors |


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

- I used the live deployed site for testing, at the following link : https://jigsaw.w3.org/css-validator/#validate_by_uri

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdmp-86.github.io%2FCannaMed%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en



| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2FDmp-86.github.io%2FCannaMed) | ![screenshot](documentation/w3-css-check.png) | Pass: No Errors |

## Browser Compatibility

I have tested the live deployed site on the following browsers to check for compatibility issues:

- [Chrome](https://www.google.com/chrome)
- [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer)
- [Edge](https://www.microsoft.com/edge)
- [Safari](https://support.apple.com/downloads/safari)


I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/chrome-browser-test.png) | Works as expected |
| Firefox | ![screenshot](documentation/firefox-dev.png) | Works as expected  |
| Edge | ![screenshot](documentation/edge-browser-test.png) | Works as expected |
| Safari | ![screenshot](documentation/safari-broswer2.png) | Minor CSS differences |

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| Personal Mobile - Samsung Galaxy s10 | ![screenshot](documentation/personal-device-home.jpg) | Works as expected |
| Personal Mobile - Samsung Galaxy s10 | ![screenshot](documentation/personal-device-nav.jpg) | Works as expected |
| Personal Mobile - Samsung Galaxy s10 | ![screenshot](documentation/personal-device-gal.jpg) | Works as expected |
| Personal Mobile - Samsung Galaxy s10 | ![screenshot](documentation/personal-device-contact.jpg) | Works as expected |
| Personal Mobile - Samsung Galaxy s10 | ![screenshot](documentation/personal-device-footer.jpg) | Works as expected |
| Mobile (DevTools) | ![screenshot](documentation/galaxys20-devsnip.png) | Works as expected |
| Tablet (DevTools) | ![screenshot](documentation/ipad-mini-devsnip.png) | Works as expected |
| Desktop (DevTools)| ![screenshot](documentation/desktop-responsive.png) | Works as expected |
| Microsoft Surface Pro 7 (DevTools)| ![screenshot](documentation/surface-pro-7-responsive.png) | Works as expected |
| iPhone 12 (DevTools) | ![screenshot](documentation/iphone12-devsnip.png) | Works as expected |


## Lighthouse Audit


I've tested my deployed project using the Lighthouse Audit tool to check for any major issues.
My first test produced some performance issues due to chrome extensions (see screenshot below). To negate further performance issues, I ran Lighthouse Audits in Incognito mode. 

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Desktop | ![screenshot](documentation/lighthouse-dt.png) ![screenshot](documentation/lighthouse-chrome-incognito.png) | Performance issue due to Chrome browser extension. Fixed in Incognito mode |
| Home | Mobile | ![screenshot](documentation/lighthouse-chrome-incog-mob.png) | Performance issue due to Chrome browser extension. Fixed in Incognito mode |
| Gallery | Mobile | ![screenshot](documentation/lighthouse-incog-gall-mob.png) | Slow response time due to large images |
| Gallery | Desktop | ![screenshot](documentation/lighthouse-chrome-incog-dt.png) | A minor warning  |
| Contact | Mobile | ![screenshot](documentation/lighthouse-incog-contact-mob.png) | A minor warning  |
| Contact | Desktop | ![screenshot](documentation/lighthouse-contact-incog-dt.png) | A minor warning  |
| Divert | Desktop | ![screenshot](documentation/lighthouse-incog-divert-dt.png) | A minor warning |
| Divert | Mobile | ![screenshot](documentation/lighthouse-divert-incog-mob.png) | Slow response time due to large images |

## Bugs


- Favicon error: 

    - To fix this, I created a faviconand added it to my hmtl pages.

[Add A Favicon to A Website in HTML](https://www.youtube.com/watch?app=desktop&v=kEf1xSwX5D8)

### GitHub **Issues**


**Fixed Bugs**

All previously closed/fixed bugs can be tracked [here](https://github.com/Dmp-86/CannaMed/issues?q=is%3Aissue+is%3Aclosed).

| Bug | Status |
| --- | --- |
| [JS Uncaught ReferenceError: `foobar` is undefined/not defined](https://github.com/Dmp-86/CannaMed/issues/1) | Closed |
| [Python `'ModuleNotFoundError'` when trying to import module from imported package](https://github.com/Dmp-86/CannaMed/issues/2) | Closed |
| [Django `TemplateDoesNotExist` at /appname/path appname/template_name.html](https://github.com/Dmp-86/CannaMed/issues/3) | Closed |

**Open Issues**

Any remaining open issues can be tracked [here](https://github.com/Dmp-86/CannaMed/issues).


## Unfixed Bugs


There are no remaining bugs that I am aware of.
