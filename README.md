# Deployed Link

## This contains the details of the sections recreated by me

### Top Navigation Bar

- I have put this section in the `header` semantic tag
- I have used a wrapper div inside it and given it width of 84% because visually Mintlify website uses about 8% margin on left and right throughout the website
- Inside this there are three wrappers to wrap three broad elements as appearing on the Mintlify website, namely logo, navigation and Call to Action
- The header is fixed at the top so it stays visible on scroll
- I have used flexbox with flex-direction row to place logo on the left, navigation in the middle and CTA buttons on the right
- The two CTA buttons are styled with capsule-style border radius

### Hero Section

- This section is inside the semantic `main` tag
- The hero section has the SVG background (`bg-light.svg`) applied to it so that the background and the transparent header appear as one continuous area
- I used a wrapper div with 84% width and flex-direction column to stack the headline, description, email CTA and hero image
- The headline is split into two lines, followed by a short description, then an email input with "Start now" button in a single row, and finally the hero illustration image
- The email CTA is styled as a pill with teal background

### Trusted By Section

- This section displays a grid of logo cards for companies that use Mintlify
- I used grid with four columns to place the logo cards in two rows
- Each logo is wrapped in a card div and the logos are centered using flexbox

### Feature Highlight Section

- This section has a headline and description at the top, centered
- Below that, two image cards are placed side by side using flexbox
- The wrapper uses 84% width and flex-direction column for the overall layout

### Assistant Section

- This section is inside a bordered wrapper with rounded corners
- I used flexbox to place the text content (label, heading and description) and the assistant image in a column layout
- The "ASSISTANT" label uses a green color to match the Mintlify style

### Enterprise Section

- This section has a headline and short description at the top
- Below that, two blocks (Build with partnership, Compliance and access control) are placed in two equal columns using grid
- The wrapper uses 84% width

### Final CTA Section

- Very easy section to make
- Used flexbox to display the headline, description and two buttons (Get Started For Free, Get a demo) in a column and at the center of the page
- One button is primary (filled) and the other is secondary (outline)

### Footer Section

- Put in the footer semantic tag
- Five columns (Product, Company, Resources, Legal, Connect) were put in the layout using flexbox with space-between
- Styled in Mintlify style with light background, dark text and uppercase gray column headings
- The copyright line is at the bottom with a subtle top border
- Link hover uses Mintlify green color

## Conclusion

Overall I have used flexbox and grid heavily to make this website landing page. The webpage is built with only HTML and CSS (no JavaScript, no Tailwind, desktop-only). The class names follow camelCase convention. The webpage I have designed is a clone of the Mintlify website.
