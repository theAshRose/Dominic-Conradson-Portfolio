# Dominic-Conradson-Portfolio

## Description

My proffesional dev portfolio showcasing all web apps/designs thus far. Listed from most recent to oldest, join me on this journey. It is and likely will always be a work in progress.

## Usage
Fully responsive layout with a fun pink glow to the images upon cursor hover. Please, click to your hearts content! Examine this page and subsequent links to determine my eligibility for employment. 
![screenshot](./assets/images/portfolioscreen.png)

[an actual link to the page](https://thedomconrad.github.io/Dominic-Conradson-Portfolio/)

# Code Snippit
some HTML and CSS of clickable images:

```
            <main>
                <section id="top" class="sub-section"> <!--this is the largest image/clickable link-->
                    <figure>
                        <a target="_blank" href="https://thedomconrad.github.io/Dominic-Conradson-Portfolio/">
                            <img src="./assets/images/mouse.png" alt="my portfolio">
                        </a>
                        <h2 class="image-text-link" id="current-project"><a target="_blank" href="">
                                My portfolio!
                                <br>the 3rd webpage from scratch
                            </a>
                        </h2>
                    </figure>
                </section>

                <section id="bottom" class="sub-section"> <!--this is where smaller clickable images are hosted-->
                    <figure>
                        <a target="_blank" href="https://thedomconrad.github.io/prework-study-guide/">
                            <img src="./assets/images/hell2.png" alt="prework study guide">
                        </a>
                        <h2 class="image-text-link" id="completed-works">
                            <a target="_blank" href="https://thedomconrad.github.io/prework-study-guide/">
                                First web edit
                                <br>from source code, a study guide
                            </a>
                        </h2>
                    </figure>

corresponding CSS:

#top figure,
#bottom figure{
    border-style: dashed;
    border-width: 5px;
    color: var(--ddblue);
    transition: 1.5s ease-in 150ms      /*transition rule*/
}

#top figure:hover,                      /*our transition color after hover*/
#bottom figure:hover {
    border-color: var(--lblue);
    box-shadow: 0px 3px 45px 34px var(--pink);
}
                                        /*borders for main images end */

#bottom img {                           /*sizing for smaller central image links*/
    min-width:300px;
    max-width: 300px;
    max-height: 200px;
    min-height: 200px;
}                        

.image-text-link {                      /*styling for image titles*/
    padding: 2px;
    background-color: var(--dblue);
    font-style:italic;
    font-size: 18px;
}                            

```

##Credits
## Author Links
---[Linkedin](https://www.linkedin.com/in/dominic-conradson-76638b172/)---
[GitHub](https://github.com/theDomConrad/)---
[Portfolio](https://thedomconrad.github.io/Dominic-Conradson-Portfolio/)---