# Docker Failure Stories

A compiled list of links to public failure stories related to Docker.
Most recent publications on top.

* [Docker in Production: A History of Failure - 1 NOVEMBER 2016](https://thehftguy.com/2016/11/01/docker-in-production-an-history-of-failure/)
    * involved: 
    * impact: production issues

# Why?
A long time ago (2015 I think, when Go was a few years old and docker was the trend) while searching ways, with an old colleague of mine, to have fast and easy deployemnts and won't have to deal with different environments (docker seemed to solve this), I came accross a blog post from a devops/enigneer where they have moved their codebase to Go (switched from monolithic to microservices as well, I think) and they used Docker for production deployemnt. Nevertheless, it failed spectacularly as some containers crashed (can't remember why) and dragged the rest of the healthy containers along with them, thus creating a domino effect. 

Now, for the life of me, I cannot remember that post's url or the blog's name.

So while searching once again for it, I came accross https://github.com/hjacobs/kubernetes-failure-stories and https://news.ycombinator.com/item?id=18954430 and I thought to myself, "Why not?".

I now, have a little side project in search of that forgotten blogpost, and hopefully an informative and fun stories list about Docker production deployments.

# Contributing

Please help the community and **[share a link to your failure story by opening a Pull Request!](https://github.com/georgekaf/docker-failure-stories/edit/master/README.md)**
Failure stories can be anything like blog posts, conference/meetup talks, incidents, tweetstorms etc.

# Thanks

Thanks to all contributors and everybody who writes public Docker Failures! 👏

Thanks to https://github.com/hjacobs/ and https://news.ycombinator.com/user?id=gspetr for inspiring this! 👏
