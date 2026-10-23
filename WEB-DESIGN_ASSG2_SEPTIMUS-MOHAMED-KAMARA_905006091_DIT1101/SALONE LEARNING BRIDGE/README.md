# Salone Learning Bridge website

## About the website

Salone Learning Bridge is a desktop website concept for a community-focused non-governmental organisation in Sierra Leone. It introduces the organisation, explains its learning and youth-support programmes, and gives visitors a clear way to ask questions or enquire about joining a programme. The site is designed for young people, caregivers, mentors, community partners and other people seeking information about local learning opportunities.

The website presents three programme areas: community learning clubs, girls’ mentoring circles and practical digital skills. Its content focuses on accessible learning, confidence, supportive relationships and useful technology skills. The organisation and its services are presented as a website concept; the contact and enquiry forms are demonstrations and are not connected to a real organisation or server.

## Main sections and visitor tasks

- **Home (`index.html`)** introduces the organisation’s purpose, highlights the three programmes, and directs visitors to programme details or the contact form.
- **About (`about.html`)** explains the organisation’s community-led approach, guiding values and intended audiences.
- **Services (`services.html`)** describes the learning clubs, mentoring circles and digital-skills programme, including each programme’s focus and an enquiry link.
- **Contact (`contact.html`)** provides general enquiry and safeguarding information alongside a message form.
- **Programme enquiry (`programme-enquiry.html`)** lets visitors select a programme, provide a name and preferred reply method, and write a question. Programme links can open this page with a programme preselected.
- **Enquiry confirmation (`enquiry-confirmation.html`)** acknowledges a completed demonstration form and provides a route back to the home page.

The main header links connect Home, About, Services and Contact. The “Ask about a programme” header button opens the programme enquiry page. Link-style buttons that lead to the page currently open are marked as the current page and shown in green. Footer links provide routes to Contact and safeguarding information.

## Visual design

The site uses a restrained forest-green, white and warm-sand palette. Generous spacing separates the content into readable sections, cards organise programme information, and simple SVG marks identify the organisation and its services. Photographs show schools and learners in Sierra Leone. The layout is intentionally desktop-only and uses a fixed desktop page width; it has not been adapted for mobile screens.

## Project files

- `index.html`, `about.html`, `services.html`, `contact.html`, `programme-enquiry.html` and `enquiry-confirmation.html` contain the individual site pages.
- `css/styles.css` contains the shared desktop layout, colours, typography, cards, buttons and active-page styling.
- `js/script.js` sets current-page states for matching links, preselects a programme from the page URL, and handles the demonstration form flow.
- `assets/brand-mark.svg` and `assets/icon-*.svg` contain the logo and interface symbols.
- `assets/photos/` contains two locally stored PNG photographs: the Rogbesseh school pupils and the students using solar-powered laptops in Sahn Malen.
- `assets/IMAGE-CREDITS.md` records the photographers, source pages and license information for the site photographs.

Three photographs—the Koidu classroom, the schoolgirl and the rural school building—are still loaded from Wikimedia Commons and require an internet connection. The other two photos load from the local `assets/photos/` folder. The photo-credit page and visible photo-source links have been removed from the website; attribution and license details remain in the assets folder.

## Open and view the website

1. Extract `Salone_Learning_Bridge_Standalone_Website.zip` if you are starting from the ZIP package.
2. Open `Salone_Learning_Bridge.code-workspace` in Visual Studio Code, or open the `website_code` folder.
3. Open `index.html` in a web browser.
4. Use the header, programme cards and page buttons to explore the site. Select a programme to open the enquiry form with that programme selected.

The prototype uses plain HTML, CSS and JavaScript. It does not need package installation or a build step. Internet access is needed for the three remaining externally hosted photographs.

## Prototype limitations

The contact and programme forms validate required fields in the browser and then navigate to the confirmation screen. They do not save or send submitted information. To receive real enquiries, the forms would need to be connected to an organisation-approved form service or a server-side backend. The site has no database, authentication, content-management system or mobile layout.

                                                                                            CREATED BY: SEPTIMUS MOHMAED KAMARA