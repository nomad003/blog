# blog
https://nomad003.github.io/blog/

hugo
    hugo version   
    hugo new site myblog
    themes
        mkdir themes
        git clone https://github.com/vaga/hugo-theme-m10c.git
    posts
         hugo new posts/new my_first_blog.md
    run
         hugo server 
github
    hugo --theme=hyde --baseUrl="https://github.com/nomad003/nomad003.github.io.git"
    git init 
    git add -A
    git commit -m "这是用Hugo建立的一个网站"
    git remote add origin https://github.com/nomad003/nomad003.github.io.git
    git push -u origin master 
    
