# GRAIL Lab Website

This is the website of our academic research group at UNC Chapel Hill.

This website is powered by Jekyll and some Bootstrap, Bootwatch. 

Our website borrows the template from a couple of cool websites:
- [Allan Lab](https://www.allanlab.org/)
- [Chandar Lab](https://chandar-lab.github.io/)

## Guide

* [Publications](#publications)
* [News](#news)
* [People](#people)
  * [When someone joins the group](#when-someone-joins-the-group)
  * [When someone leaves the group](#when-someone-leaves-the-group)

### Publications

When a publication is added or changed:

1. Update [`_data/publications.yaml`](https://github.com/grail-lab-unc/grail-lab-unc.github.io/edit/main/_data/publications.yaml)
2. Create a pull request and ask the current maintainer to review.

### News

When the news section needs to be changed:

1. Update [`_data/news.yaml`](https://github.com/grail-lab-unc/grail-lab-unc.github.io/edit/main/_data/news.yaml)
2. Create a pull request and ask the current maintainer to review.

### People

#### When someone joins the group:

1. Add them to [`_data/people.yaml`](https://github.com/grail-lab-unc/grail-lab-unc.github.io/edit/main/_data/people.yaml)
2. Add their profile picture too [`images/teampic/`](images/teampic/).
3. Create a pull request.


#### When someone leaves the group:

1. Remove them from [`_data/people.yaml`](https://github.com/grail-lab-unc/grail-lab-unc.github.io/edit/main/_data/people.yaml)
2. Remove their profile picture from [`images/teampic`](images/teampic/).
2. Add them to [`_data/alumni.yaml`](_data/alumni.yaml) in the same branch.
3. Create a pull request.