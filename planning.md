# Content

Page 1 – Berly introduction
    Navigation Bar linking to all 4 pages
        Home, Vote, Pics, Resources
    1 header using H1
        Berly – A Portraiture (pic sitting pretty)
    3 sections of text with H2 headers
        Early life/origin story – found in Cali
        Journey to Chicago
        Life in Chicago
    1 image
Page 2
    Navigation Bar linking to all 4 pages
    H1
    Vote on a Berly Adventure
    HTML form with a minimum of:
    1 fieldset
    3 inputs
    2 text
    1 checkbox
    1 textarea
    Appropriate labels for the above
    1 button
Page 3
    Navigation Bar linking to all 4 pages
    1 header using H1
    Resources for Rescue Cats
    1 ordered or unordered list of links to 5 other websites
Page 4
    Navigation Bar linking to all 4 pages
    1 header using H1
    Berly – Up Close and Personal
    6 images displayed 3 wide and 2 down
    A label for each image
    Clicking on the image opens the source of that image in a new window



Layout based on google adsense layout: https://www.google.com/adsense/new/accept-agreement?authuser=0#home

html element modifier
    font-family: Roboto,Helvetica,Arial,sans-serif;

body element modifier
    background-color: light grey?;

class main - for main content (excluding footer and top nav)
    max-width: 764px;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    width: 100%;
    height: 100%;

class card - for content that sits inside main
    display: flex;
    flex-direction: column;
    margin: 32px 8px 0;
    padding: 24px;

colored border depending on which page you're on
colors - hot pink, baby blue, neon orange, neon green

Google example:
box-shadow: 0 4px 5px 0 rgba(0,0,0,.14), 0 1px 10px 0 rgba(0,0,0,.12), 0 2px 4px -1px rgba(0,0,0,.2)

class footer - content inside body element but outside card element
    display: flex;
    gap: 10px;
    justify-content: space-around;
