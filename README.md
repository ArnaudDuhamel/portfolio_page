# Portfolio page

This is the fifth and last project done to obtain the Free Code Camp Responsive Web Design certification.

[**Code Pen link**](https://codepen.io/Arnaud-Duhamel/full/wvOBMdO)

<details>
  <summary>HTML code</summary>
  
```html

<!DOCTYPE html>
<html lang="en">
    <head>
            <meta charset="utf-8" />
            <meta name="viewport" content="width=device-width, initial-scale=1.0" />
            <meta name="description" content="5th project for Free Code Camp Responsive Web Design certification" />
            <title>Portfolio</title>
            <link rel="stylesheet" href="styles.css" />
    </head>
    <body>

        <!-- NAVIGATION BAR -->

       <header role="banner" aria-labelledby="navbar">
            <nav id="navbar">
                <ul id="navlist">
                    <li>
                        <a href="#welcome-section">About</a>
                    </li>
                    <li class="navlist_separator"></li>
                    <li>
                        <a href="#projects">Projects</a>
                    </li>
                    <li class="navlist_separator"></li>
                    <li>
                        <a href="#contact_informations">Contact</a>
                    </li>
                </ul>
            </nav>
       </header>

       <!-- PRESENTATION -->

       <section id="welcome-section" role="region">
            <h1>
                Hi there my name is Arnaud Duhamel and this is my 5th and last project of the Free Code Camp
                Responsive Web Design certification. Below are my other certification projects.
            </h1>
       </section>

       <!-- PROJECTS -->

       <section id="projects" role="region">
        <div class="project_tile_container">
            <div class="project-tile">
                <a href="https://codepen.io/Arnaud-Duhamel/full/OJaBMLy" target="_blank">
                    <img src="https://github.com/ArnaudDuhamel/portfolio_project/assets/113102976/9264542f-57c5-4c6c-8255-98871396bc8f" alt="picture of a survey page" />
                    <p>Survey page</p>
                </a>
            </div>
            <div class="project-tile">
                <a href="https://codepen.io/Arnaud-Duhamel/full/XWyxmgg" target="_blank">
                    <img src="https://github.com/ArnaudDuhamel/portfolio_project/assets/113102976/d8ff5830-6fc7-4fa4-b39d-c466b3d338c1" alt="picture of a tribute page to Kulman Ghising" />
                    <p>Tribute page to Kulman Ghising</p>
                </a>
            </div>
            <div class="project-tile">
                <a href="https://codepen.io/Arnaud-Duhamel/full/vYQozjK" target="_blank">
                    <img src="https://github.com/ArnaudDuhamel/portfolio_project/assets/113102976/78439181-2e15-4751-b7df-fbbf32150c19" alt="picture of a website of the weather modification information act" />
                    <p>The Weather Modification Information Act</p>
                </a>
            </div>
            <div class="project-tile">
                <a href="https://codepen.io/Arnaud-Duhamel/full/wvOvybq" target="_blank">
                    <img src="https://github.com/ArnaudDuhamel/portfolio_project/assets/113102976/bf7f5506-b747-483c-ad88-d36d0fba3a11" alt="picture of a product landing page" />
                    <p>Product Landing page</p>
                </a>
            </div>
            </div>
       </section>

       <!-- CONTACTS -->

       <footer id="contact_informations">
            <h1>My contacts</h1>
            <div>
                <a id="profile-link" href="https://www.freecodecamp.org/ArnaudDuhamel" target="_blank"><svg class="logo" xmlns="http://www.w3.org/2000/svg" height="32" width="36" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2023 Fonticons, Inc.--><path d="M97.2 96.2c10.4-10.7 16-17.1 16-21.9 0-2.8-1.9-5.5-3.8-7.4A14.8 14.8 0 0 0 101 64.1c-8.5 0-20.9 8.8-35.8 25.7C23.7 137 2.5 182.8 3.4 250.3s17.5 117 54.1 161.9C76.2 435.9 90.6 448 100.9 448a13.6 13.6 0 0 0 8.4-3.8c1.9-2.8 3.8-5.6 3.8-8.4 0-5.6-3.9-12.2-13.2-20.6-44.5-42.3-67.3-97-67.5-165C32.3 188.8 54 137.8 97.2 96.2zM239.5 420.1c.6 .4 .9 .6 .9 .6zm93.8 .6 .2-.1C333.2 420.6 333.2 420.7 333.3 420.6zm3.1-158.2c-16.2-4.2 50.4-82.9-68.1-177.2 0 0 15.5 49.4-62.8 159.6-74.3 104.4 23.5 168.7 34 175.2-6.7-4.4-47.4-35.7 9.6-128.6 11-18.3 25.5-34.9 43.5-72.2 0 0 15.9 22.5 7.6 71.1C287.7 364 354 342.9 355 343.9c22.8 26.8-17.7 73.5-21.6 76.6 5.5-3.7 117.7-78 33-188.1C360.4 238.4 352.6 266.6 336.4 262.4zM510.9 89.7C496 72.8 483.5 64 475 64a14.8 14.8 0 0 0 -8.4 2.8c-1.9 1.9-3.8 4.7-3.8 7.4 0 4.8 5.6 11.3 16 21.9 43.2 41.6 65 92.6 64.8 154.1-.2 68-23 122.6-67.5 165-9.3 8.4-13.2 14.9-13.2 20.6 0 2.8 1.9 5.6 3.8 8.4A13.6 13.6 0 0 0 475.1 448c10.3 0 24.7-12.1 43.5-35.8 36.6-44.9 53.1-94.4 54.1-161.9S552.3 137 510.9 89.7z"/></svg> Free Code Camp profile</a>
                <a id="profile-link" href="https://www.linkedin.com/in/arnaudduhamel/?locale=en_US" target="_blank"><svg class="logo" height="32" viewBox="0 0 72 72" width="32" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M8,72 L64,72 C68.418278,72 72,68.418278 72,64 L72,8 C72,3.581722 68.418278,-8.11624501e-16 64,0 L8,0 C3.581722,8.11624501e-16 -5.41083001e-16,3.581722 0,8 L0,64 C5.41083001e-16,68.418278 3.581722,72 8,72 Z" fill="#007EBB"/><path d="M62,62 L51.315625,62 L51.315625,43.8021149 C51.315625,38.8127542 49.4197917,36.0245323 45.4707031,36.0245323 C41.1746094,36.0245323 38.9300781,38.9261103 38.9300781,43.8021149 L38.9300781,62 L28.6333333,62 L28.6333333,27.3333333 L38.9300781,27.3333333 L38.9300781,32.0029283 C38.9300781,32.0029283 42.0260417,26.2742151 49.3825521,26.2742151 C56.7356771,26.2742151 62,30.7644705 62,40.051212 L62,62 Z M16.349349,22.7940133 C12.8420573,22.7940133 10,19.9296567 10,16.3970067 C10,12.8643566 12.8420573,10 16.349349,10 C19.8566406,10 22.6970052,12.8643566 22.6970052,16.3970067 C22.6970052,19.9296567 19.8566406,22.7940133 16.349349,22.7940133 Z M11.0325521,62 L21.769401,62 L21.769401,27.3333333 L11.0325521,27.3333333 L11.0325521,62 Z" fill="#FFF"/></g></svg><p class="copyright">®</p> LinkedIn profile</a>
                <a id="profile-link" href="https://github.com/ArnaudDuhamel?tab=repositories" target="_blank"><svg class="logo" enable-background="new 0 0 512 512" height="32px" id="Layer_1" version="1.1" viewBox="0 0 512 512" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><g><path clip-rule="evenodd" d="M296.133,354.174c49.885-5.891,102.942-24.029,102.942-110.192   c0-24.49-8.624-44.448-22.67-59.869c2.266-5.89,9.515-28.114-2.734-58.947c0,0-18.139-5.898-60.759,22.669   c-18.139-4.983-38.09-8.163-56.682-8.163c-19.053,0-39.011,3.18-56.697,8.163c-43.082-28.567-61.22-22.669-61.22-22.669   c-12.241,30.833-4.983,53.057-2.718,58.947c-14.061,15.42-22.677,35.379-22.677,59.869c0,86.163,53.057,104.301,102.942,110.192   c-6.344,5.452-12.241,15.873-14.507,30.387c-12.702,5.438-45.808,15.873-65.758-18.592c0,0-11.795-21.31-34.012-22.669   c0,0-22.224-0.453-1.813,13.592c0,0,14.96,6.812,24.943,32.653c0,0,13.6,43.089,76.179,29.48v38.543   c0,5.906-4.53,12.702-15.865,10.89C96.139,438.977,32.2,354.626,32.2,255.77c0-123.807,100.216-224.022,224.03-224.022   c123.347,0,224.023,100.216,223.57,224.022c0,98.856-63.946,182.754-152.828,212.688c-11.342,2.266-15.873-4.53-15.873-10.89   V395.45C311.1,374.577,304.288,360.985,296.133,354.174L296.133,354.174z M512,256.23C512,114.73,397.263,0,256.23,0   C114.73,0,0,114.73,0,256.23C0,397.263,114.73,512,256.23,512C397.263,512,512,397.263,512,256.23L512,256.23z" fill="#0D2636" fill-rule="evenodd"/></g></svg> GitHub profile</a>
            </div>
       </footer>
    </body>
</html>

```

</details>

<details>
  <summary>CSS code</summary>
  
```css

/* project colors */
@media (prefers-reduced-motion: no-preference) {
    * {
      scroll-behavior: smooth;
    }
  }

:root {
    --main-background: #EEB73A;
    --main-black: #220F00;
    --section-bottom-border: 0.1rem;
    --navlist-height: 3.5rem;
    --header-height: calc(var(--section-bottom-border) + var(--navlist-height));
    --min-width: 460px;
}

/* 
    Makes sure that all element have no padding & margin by default
    
    Also sets the font size. 16px * 62.5% equals 10px. This is done
    to be able to easily use the rem unit. Which is now 10px.

    rem will therefore be sued for size values, margin and padding.
    Some media queries further down reduces the size when the screen
    reduced. It will therefore have an impact on properties using rem.

    16px * 62.5% is used in stead of just 62.5% to ensure uniformity 
    accross browsers that may have a different default then 16px.

    And a % is used to more easily make changes to the font size.
*/

html {
    font-size: calc(16px * 62.5%);
}

html * {
    margin: 0;
    padding: 0;
}

/* 
   All content elements are set to inherit by default
   so that if an element changes its box-sizing, its children
   will inherit its box sizing.
   
   It is set by default to border-box sizing in the body
*/

html *,
html *::before,
html *::after {
    box-sizing: inherit;
}


@media (max-width: 1200px) {
    html {
        font-size: calc(16px * 60%);
    }
}
  

@media (max-width: 980px) {
    html {
        font-size: calc(16px * 58%);
    }
}
  
  
@media (max-width: 460px) {
    html {
        font-size: calc(16px * 55%);
    }
}


body {
    font-family:'Times New Roman', Times, serif;
    font-size: 1.8rem;
    font-weight: 700;
    line-height: 1.5;
    box-sizing: border-box;
    background-color: var(--main-background);
}

h1,
h2 {
  font-weight: bold;
  text-align: start;
}

h1 {
    font-size: 3.8rem;
}
  
h2 {
    font-size: 2.8rem;
}

header {
    width: 100%;
    position: fixed;
    top: 0;
    left: 0;
    background-color: var(--main-background);
    border-bottom: var(--section-bottom-border) solid var(--main-black);
}

#navbar {
    width: 100%;
}

ul {
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    list-style: none;
}

#navlist {
    width: var(--min-width);
    height: var(--navlist-height);
}

a {
    text-decoration: none;
    color: var(--main-black);
}


#navlist a {
    display: flex;
    align-items: center;
    height: 3rem;
    color: var(--main-black);
    padding: 0.8rem;
    border: 0.2rem solid var(--main-background);
}

#navlist a:hover {
    border-color: var(--main-black);
    transition: border-color 0.3s ease-out;
}

.navlist_separator {
    width: 0.1rem;
    height: 1.8rem;
    background-color: var(--main-black); 
}

#welcome-section {
    margin-top: var(--header-height);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    border-bottom: var(--section-bottom-border) solid var(--main-black);

    /*
        This attributes make sure that the height of the section is as high as the viewport 
        minus the height of the navigation bar. That way, the user sees the whole section and
        its content without having to scroll. 
    */
    min-height: calc(100vh - var(--header-height));
    width: 100%;
    min-width: var(--min-width);

    /*
        This attribute using the header-height variable ensures that, when a link to that 
        section is clicked the section will be placed right under the navigation bar. 
    */
    scroll-margin-top: var(--header-height);
}

#welcome-section h1 {
    width: 95%;
    min-width: var(--min-width);
}

#projects {
    width: 100%;
    min-width: var(--min-width);
    border-bottom: var(--section-bottom-border) solid var(--main-black);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    scroll-margin-top: var(--header-height);
}

.project_tile_container {
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    width: 95%;
    min-width: var(--min-width);
    gap: 0.5rem;
}

.project-tile {
    width: 45%;
    min-width: var(--min-width);
    max-width: 500px;
}

img {
    min-height: 200px;
    height: 45vh;
    width: 100%;
    object-fit: fill;
}

.project_tile_container p {
    font-size: 1.5rem;
}

#projects a {
    display: flex;
    flex-direction: column;
    align-items: start;
    justify-content: start;
    border: 0.3rem solid var(--main-background);
}

#projects a:hover {
    border-color: var(--main-black);
    transition: border-color 0.3s ease-out;
}

footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: start;
    border-bottom: var(--section-bottom-border) solid var(--main-black);
}

footer div {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
    margin-bottom: 1rem;
}

footer a {
    padding: 0.5rem 0.75rem;
    border: 0.3rem solid var(--main-background);
}

footer a:hover {
    border-color: var(--main-black);
    transition: border-color 0.3s ease-out;
}

.logo {
    width: unset;
    margin: -0.5rem 0 0 0;
    vertical-align: middle;
}

.copyright {
    display: inline-block;
    vertical-align: middle;
    font-size: 1rem;
    margin-top: -1.8rem;
}

/*
    This media query changes the contact list from horizontal
    to vertical when the screen will have a screen width of 970 
    px or less, the space between each list item is also reduced
    and the distance between the list and the section title is also
    reduced
*/
@media (max-width: 970px) {
    footer div {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: start;
        gap: 0;
        margin-top: -0.5rem;
        margin-bottom: 1rem;
    }
}

```

</details>

The design was inspired by this page:  

<img src="images/portfolio_idea.png" height="600px" width="800px" />

## Final product

<img src="images/final_product.png" />
