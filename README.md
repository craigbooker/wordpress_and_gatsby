# COURSENAME

This is the repository for the LinkedIn Learning course `Building a Headless WordPress Site with Gatsby`. The full course is available from [LinkedIn Learning][lil-course-url].

![course-name-alt-text][lil-thumbnail-url]

_See the readme file in the main branch for updated instructions and information._

## Instructions

This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches

The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter.
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

## Installing

1. To use these exercise files, you must have the following installed:
   - [Node.js](https://nodejs.org/en/)
   - [Gatsby CLI](https://www.gatsbyjs.com/docs/quick-start/)
2. To pull data from a WordPress site, you need a WordPress site (preferably a local WordPress development environment using [local](https://localwp.com/) or similar) with the following installed:
   - [WordPress Theme Unit Test](https://codex.wordpress.org/Theme_Unit_Test) data or other prototype content.
   - [WPGatsby](https://wordpress.org/plugins/wp-gatsby/) plugin
   - [WPGraphQL](https://wordpress.org/plugins/wp-graphql/)
3. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
4. In terminal, while on the `main` branch, navigate to the project folder and run the command `npm install`.
5. Configure the `url` option for `gatsby-source-wordpress` in `./gatsby-config.js`.
6. To start developing, run the command `gatsby develop`.

[0]: # "Replace these placeholder URLs with actual course URLs"
[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: http://
