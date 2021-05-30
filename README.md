# Official Webite of Nexus, SJCET
This is the official website of Nexus, SJCET. It is built using [Hugo](https://gohugo.io/), 
a static site generator and deployed using [Gitlab Pages](https://docs.gitlab.com/ee/user/project/pages/).
The website aspires to be simple yet functional, the aim of which being that even someone who only has basic
knowledge in web development should be able to make any necessary changes to the website. In addition to this
it was our aim make it possible for non technical folks to be able to add content such as blog posts to this 
website this is still a working progress.

## Adding Blog posts to this website.
You add blog posts to this website by adding markdown files (files ending in .md) to the contents/post folder.
Just make sure to add the relevant frontmatter at the begining of the file. You can refer to existing posts to
see the available metadata that can be added in the frontmatter.

## Testing the website locally.
- Install hugo using instructions for your operating system from this [page](https://gohugo.io/getting-started/installing/).
- Clone this repo using the following command:
  ```
  git clone https://gitlab.com/thenexusproject/thenexusproject.gitlab.io.git
  ```
- Change directory to the cloned repository and run the following command:
  ```
  hugo server -D
  ```
- The above command will start a development server at `localhost:1313/`. So you can open `localhost:1313/` in your browser to
  view the website locally.

## Licensing
All content in this website is licensed under Creative Commons 4.0 License.
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
