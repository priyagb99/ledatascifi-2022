# Setting up a website to show off your work
### 04/05/2022

## PURPOSE 
- Learn how to build a website to show off some cool stuff

## GOALS
- Use GitHub Pages to build a website a resume-style website and showcase projects, including your midterm
- Use GitHub Pages to create a website for your final group project at the end of the semester
- Show examples of what you can do with GitHub Pages
- Show examples of “above and beyond” the minimal expectations for a website

## GITHUB PAGES OVERVIEW
- Fast, easy, free way to create and host a website
- Hosted on GH’s servers
- Not required to pay to register for a domain name—though you still can
- Examples:
    - https://julioveracruz.github.io/
        - https://github.com/julioveracruz/julioveracruz.github.io 
    - https://julioveracruz.github.io/testwebsite/
        - https://github.com/julioveracruz/testwebsite  
    - https://donbowen.github.io/slides-2022/
    - https://square.github.io/
        - https://github.com/square/square.github.io 
    - https://yelp.github.io/
        - https://github.com/Yelp/yelp.github.io 

## WALKTHROUGH
### Personal website (template version)
- Go to https://github.com/donbowen/donbowen.github.io 
- Click the green [Use this template] button
- Name it *username*.github.io
    - If you already have a *username*.github.io repo, give it any name you want (perhaps something like, “personal-website”)
        - In the resulting repo, click Settings, then Pages, then make sure the source is the main branch, then save.
- Change the link in the about area to your username. Then go look at the website
- Edit config (to change the left sidebar picture and links)
    - Editable sections are text in blue
- Edit index.md (text and picture, portfolio descriptions, and links, etc)
    - Can edit directly on GitHub.com or through GitHub Desktop
- Edit 10k_nlp_covid.md (to incorporate stuff from the midterm)
- Practice: Convert any ipynb from the class notes folder into MD, add to website (follow steps on regression_practice page)
    - On JupyterLab, save and export any ipynb file into markdown
    - Add that resulting markdown file to your website repo
    - Link to your markdown file by editing index.md
- Note on layout:
    - The template limits you to the “Minimal” theme preset on GitHub.com
    - For more customizability, you can create your own GitHub Pages using other theme presets with themes


### Getting started on a team project website
- Only one person on each team needs to do this.
    - Your work for the project will be in a different repo I set up, but your project's website will be this one.
- Go to https://github.com/donbowen/teamproject
- Click the green [Use this template] button
- Name it something related to the project
    - You can change this later, but any links to the website will need to change
- In the resulting repo, click Settings, then Pages, then make sure the source is the main branch.
    - You can choose a different theme here if you want
- Change the link in the code/about area to the website URL. Then go look at the website
- Settings > Collaborators:
    - Add all teammates, and add Julio and Professor Bowen
- In each person's personal website, change the eventual project link to link to that website

### MOVING FORWARD
- GitHub Pages is just the start of what you could do with creating websites
- Above and beyond..
- Other templates, resources
    - https://github.com/mmistakes/mm-github-pages-starter/generate
    - https://github.com/fastai/fastpages 
    - https://html5up.net/
- HTML, CSS, Javascript-savvy users welcomed



## A little summary of some of your options for creating websites:

| Option                                                                                                                                 | Pros                                                                                                                                                                                                 | Cons                                                                                                                                                                                                |
|----------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Default GitHub templates and Markdown files - https://donbowen.github.io/ - https://donbowen.github.io/teamproject/                    | - Easy start - Can use Plotly, Altair to make interactive charts                                                                                                                                     | - Need explicit page links for interactive table of contents, navigation bar - Limited customization options - Hard to “paste” output content into Markdown files - Have to manually convert .ipynb |
| Finding templates that you like, forking, and customizing - https://jekyllthemes.io/ - http://jekyllthemes.org/ - https://html5up.net/ | - Also easy start - Better customization options - Many have already-developed interactive table of contents, navigation bar, etc. features - Can also use Plotly, Altair to make interactive charts | - Have to learn templates’ repo organizations - Need to reconfigure templates’ files to suit your own needs - Some additional setup needed                                                          |
| Fastpages - https://github.com/fastai/fastpages                                                                                        | - Publishes ipynb files automatically - Interactive visualizations work automatically                                                                                                                | - More overhead learning                                                                                                                                                                            |

