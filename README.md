# Gatsby JS Crash Course

REDME.md

```bash
npm i -g gatsby-cli
gatsby new gatsby_crash_course
cd gatsby_crash_course
code .
gatsby develop
```

<http://localhost:8000/>
<http://localhost:8000/about>
<http://localhost:8000/services>

```bash
npm i gatsby-source-filesystem gatsby-transformer-remark gatsby-plugin-catch-links
```

<http://localhost:8000/__graphql>

```graphql
{
  allFile {
    edges {
      node {
        id
      }
    }
  }
}
```

```graphql
{
  allMarkdownRemark {
    edges {
      node {
        frontmatter {
          path
          title
          date
          author
        }
        excerpt
      }
    }
  }
}
```

github, new repository, gatsby_crash_course, Sample website built with Gatsby, create repository

```shell
git init
git add .
git commit -am 'Initial commit'
git remote add origin git@github.com:angelocabanerodedicatoria93/gatsby_crash_course.git
git push -u origin master
```

<https://www.netlify.com/>

netlify, new site from git, github, authorize netlify, gatsby_crash_course, deploy site  
click url for your website  

<https://zealous-lamarr-334f08.netlify.com/blog>
