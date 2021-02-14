# My First Blog.... After so long
    | your own code after few months feels like someone else's

    | only sane thing to do after reading someone else's code is to re-write it

So finally I am retiring my old [blog](http://nishantrevo.blogspot.com/). Blogspot is very easy to begin with its simple editor and preview feature. It also lets you add Code snippets via Github gist if you switch to HTML view in code editor and ready to tinker. Or you can go pro and do the whole thing in pure HTML. It has ready made comment section, variety of ready made themes and few other tricks up its sleeve. So why I am switching to something else? Well:
- You are stuck with either a simple editor or HTML code. Either way you are not in control of every aspect of your blog. No way to use static site generator tools like Jekyll, Hugo or deploy your own code with something like Flask.
- Blogspot has a great and functional feature set but it looks old. Everytime I open Blogspot posts or editor, I feel tranported back to time when my Pentium Dual Core with 512MB RAM was cool and 256KB DSL internet was definition of blazing fast internet.
- To learn something new. In starting Twenties of the Twenty First century blog websites like [Medium.com](https://medium.com) or [HackerNoon](https://hackernoon.com/) are the standards. After searching how most developer are creating their blogs, I saw majority is using using site generators along with version controlled Markdown files and CI pipelines. All of this makes a lot of sense for any Software Developer. That is focusing your time and energy on writing and building the pipeline using standard developer tooling. Let it figure out creating, deploying and updating the changes.

So for this I chose Hugo for generating the HTML output. Its very poplular tool with very good documentation, an active community, single binary as dependency, converts Markdown to post, lots of free themes and some more.

For hosting, I am initially choosing Github Pages.

For pipelines, since I already have worked on it, CircleCI is my chosen workhorse for the time being. Later I think I'll switch to Github actions. It will be fun to learn Github Actions but lets focus on one thing at a time.

## How I did it

### 1. Create Github repo
- Explain process of creating repos and Github pages repo. How they are going to relate.

### 2. Initialize Hugo project
- Explain Hugo download in CLI, setup project, commit first time in blog repo.

### 3. Write first blog
- Explain writing sample first blog, view locally, generate output.

### 4. The Pipeline 
- Explain circleci pipeline setup for blog repo, content of config with step by step description

## Conclusion