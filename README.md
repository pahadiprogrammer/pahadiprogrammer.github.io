# pahadiprogrammer.github.io

# The blog is maintained using jekyll.

# To Add new post can use thor command belo which will execute the jekyll.thor file. The file is referred from [here](https://gist.github.com/ichadhr/0b4e35174c7e90c0b31b)
`thor jekyll:new The title of the new post --editor=vim`

# Tips on Jekyll
- Use {{ page.path }} to display path of a page in order to link to same
- In ordder to create link among posts/pages use this `[first blog post]({% link _posts/2022-12-24-welcome-to-pahadi-programmer.markdown %})` which can be referred in [this](https://jekyllrb.com/docs/liquid/tags/#links) post too.
- To check if issues with posts use command `jekyll build --verbose`
- To run jekyll server locally to test content use command `bundle exec jekyll serve`