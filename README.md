# Developer notes

## Creating a new post
1. Create a new post in markdown using:
`hugo new content content/post/<year>/<name>/index.md`
2. Fill the template using the comments (title, description, date, country flag, labels/tags)
3. Add images in `content/post/<year>/<name>/images/`
4. Choose a cover, rename it to cover.jpg and place in `content/post/<year>/<name>/`
5. Git commit, push to dev, merge to main
6. Use github action to update the live website
