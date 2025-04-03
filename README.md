# Assignment 2

## Team
- Ana Rivera Faraco arive273@mtroyal.ca (201767273).
- Nicholas de Laive ndela524@mtroyal.ca (201753524).

## Website
This is a responsive and accessible website about video games. It contains 3 pages:
- The main page (index.html) will show some popular video games.
- The 2nd page (upcomingReleases.html) will show the future new releases.
- The 3rd page (bestSellers.html) will show a table with the best sellers.

## Taskwork
| Task                                  | Performed by |
| ------------------------------------- | ------------ | 
| Make index.html responsive            | Ana          |
| Make bestSellers.html responsive      | Nicholas     |
| Make upcomingReleases.html responsive | Both         |
| Make hamburger dropdown               | Ana          |
| Add skip to main content button       | Nicholas     |
| Check tab order and add focus ring    | Both         |
| Check Accessibility                   | Both         |
| Check color contrast                  | Nicholas     |
| Validate pages in validator           | Ana          |
| Test website in different browsers    | Both         |
| Test screen reader                    | Both         |
| Write accessibility notes             | Both         |

## Accessibility (Issues Identified and How They Were Solved)
Based on the checlist criteria, manual accessibility test and automated tests, these were the changes we needed to make.
### Perceivable: 
- Images missing title attribute: The title attribute was added to all images.
- Required text in form is not contrasted: The red color was added to the * of the required fields to make the contrast.
- Color contrast for the hero block: The text was black and it failed with the dark blue background, so we changed the color text to white with a black outline.
- Color contrast for the required fields in the contact form: The automated analysis displayed a contrast error for the *, so we changed red color to dark red.
### Operable
- We did not have the skip link to main content: We added a hidden skip link to main content at the beginning (Although we always had the "Take a look" button in the hero block).
### Understandable
- No issues here, the website was kept consistent, and the headings changed size based on the screen size (We used xx-large, large, medium ...).
### Robust
- No issues here, the website was tested in Chrome, Edge, Safari, Opera and Firefox. The website is responsive to small, medium and large screens and the tests passed in the validator.

## References
Content: https://loremipsum.io/generator?n=4&t=p
Validator: https://validator.w3.org/
Hamburger Menu: https://codepen.io/ngochuynh/pen/yKrvVZ

