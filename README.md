Wild Tropics Design System

-------------------------------

Project Description:
Wild Tropics is an example of a responsive design system inspired by the tropics, vibrant fauna, and flora found in the jungle. The project showcases the use of design tokens, typography, states, content surfaces, form controls, and two color schemes. This design system is targeted at individuals with an interest in tropical fauna and forest life, along with designers interested in finding out how reusable styles could help create an accessible information page.

-------------------------------
Reset Strategy:
This stylesheet employs a conservative reset strategy and does not strip all the default styles from the browsers. The universal selector ensures that box-sizing: border-box is applied and hence, both padding and borders are taken into account when calculating the element's width. The margin for the body tag is zeroed out since it is the browser's default margin.
-------------------------------

Project Links:
GitHub Repository: https://github.com/aball125-ai/wild-tropics
Published Website: https://aball125-ai.github.io/wild-tropics/

-------------------------------

Design Decisions:
The default theme includes jungle greens, dark teal, and cream colored text with accents of yellow and orange based on wildlife found in the tropics. The optional Tropical Daylight theme includes light backgrounds and dark green text.

Custom CSS properties hold design tokens that are reusable and have meaningful names based on their function. Color tokens define background color, surface color, text color, border color, and accent colors for interactivity. Spacing tokens set up uniform spacing and padding, whereas sizing tokens set up width of the content and reading area, and control height. Radius and elevation tokens manage corner radius and shadows on cards. Typographical tokens hold font and text size tokens. My naming pattern uses the category first, followed by a descriptive role ( `--color-bg` or `--space-large`).

Arial is used as the main font for headings and body text, while Helvetica is the second choice and the generic sans-serif font is the last choice. These fonts are already installed on the computer as they are system fonts and therefore there is no need to download any font externally. The design employs regular fonts for body texts and bold fonts for headings and emphasis.

-------------------------------

Accessibility and Responsiveness:
The page is equipped with labeled form controls, semantically marked up, with visible focus on keyboard nav. The buttons showcase hover, active and disabled states. Two themes are different in terms of text color, background color, border color, and focus color for legibility. The responsiveness test is carried out at three widths (320px, 768px, and 1280px). The zoom test is carried out at 200%.

-------------------------------

Testing Record:

| Test | Expected Result | Observed Result | Revision |

| 320px viewport | No horizontal overflow | Passed | None needed |
| 768px viewport | Layout remains readable | Passed | None needed |
| 1280px viewport | Content is centered and readable | Passed | None needed |
| 200% browser zoom | Content remains usable | Passed | None needed |
| Keyboard navigation | Links, buttons, and controls have visible focus | Passed | None needed |
| Color contrast | Text and controls are readable in both themes | Passed | None needed |
| Font fallback | Page remains readable with fallback fonts | Passed | None needed |
| HTML validation | No errors or warnings | Passed | None needed |
| CSS validation | No errors | Passed | None needed |
| Published website | Page loads from the public URL | Passed | None needed |

Testing-Related Change:
In my analysis of the design system, it was clear that the font of the header was overly bold and really hard to read. In order to achieve this effect, I modified the typography and create a better visual hierarchy. While reviewing the HTML file, it was found that the bullet point list and the inline code example were missing in the Typography section. These have been added and shifted from the Actions & States section into the Typography section for better accessibility.

-------------------------------

Code Defense:
CSS variables make sure that the design values are consistent and the themes are easy to manage. Semantic HTML elements arrange the layout of the page, whereas reusable component classes are used to style buttons, cards, notices, and other controls. The alternative theme is applied to certain color tokens rather than duplicating the whole component stylesheet.

-------------------------------

Disclosure of AI Assistance and Verification Record
AI Tool Used: ChatGPT

How AI Was Used:
CHATGPT acted as an supporting tool in the process of creating the Wild Tropics design system. Once I chose my theme, I utilized the AI to create a preliminary design of the layout, which helped me in organizing different sections for heading, body, buttons, cards, and other elements. After that, I wrote my code for each section, using AI for the purpose of getting token names and comparing designs of certain elements if necessary.
The most interesting aspect of the whole project was the creation of the visual theme and its creation. AI helped me to generate ideas of the color palette and get the required hex color codes. This process proved very useful when developing the jungle like theme and its alternative called Tropical Daylight theme.

Verification:
The responsiveness of the page was checked on 320px, 768px, and 1280px with the help of browser developer tools. I tested keyboard navigation using the Tab key to navigate through the links, buttons, and form controls and confirmed that the focus is visible. I tested the page for 200% zoom, checked the color contrast on both themes and confirmed that the GitHub Pages URL is correct.
The HTML validator did not generate any errors or warnings. There were no errors generated by the CSS validator. The fallback font was legible when the font of the body was temporarily changed using the browser developer tools.

-------------------------------