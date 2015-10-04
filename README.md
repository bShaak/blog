##Plan for personal website/blog

##User Stories
  - As a user I want to be able to create posts for my blog
  - As a user I want to be able to edit and destroy my posts
  - As a user I want to be able to write posts in markdown
  - As a user I want to be able to highlight syntax on blog posts
  - As a user I want to be able to show visitors examples of my work
  - As a user I want visitors to be able to contact me
  - As a user I want visitors to be able to leave comments on posts

##Features
  - Posts:
    - create/ edit/ destroy
    - markdown
    - syntax highlighting
    - comments (Disqus)
  - Projects:
    - create / edit / destroy
  - Contact:
    - contact form
    - links to social media
    - sendgrid
  - User (devise)

##Modeling our data
  **Post**
    title:string
    content:string
  **Project**
    title:string
    description:text
    link:string
  **User**

## Think though the pages we need in my app
  - Home
  - Posts#index
  - Posts#show
  - Projects#index
  - Projects#show
  - Contact
