
# Book creation template 
 
:book: This template manages the creation of books in a logical manner.

It also has a Gitlab pipeline configuration included so you book can be autogenerated.

Simple.

## How to use

The template uses a couple of libraries:

- [Pandoc](http://pandoc.org)
- [Kindlegen](https://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211)

Install those first.

Then clone this repo to your machine. `git clone https://github.com/avastmick/book-template.git`

:boom: Boom, you're done!

- Add chapters in the `chapters` directory
- Add cover art and save as `images/book-cover.jpg`
- Put all your planning stuff into planning
- Write away...
    + Add a synopsis set into the `synopsis` folder
    + Add chapters into the `chapters` folder
    + Modify the files in the `publish` folder to suit (see the files there for guidance)

## Use locally

### Dependences

- Install python (should be good to go on Linux or MacOS)
- Install [Pandoc](http://pandoc.org)
- Install [Kindlegen](https://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) and ensure you can get to it from your `$PATH`

### Usage
- Open a terminal
- cd to the directory you are saving your book
- type `./Publish.py -h` (MacOS or Linux) or `python Publish.py -h` (Windows) and follow the instructions

## Using Gitlab

I use [Gitlab](http://gitlab.com), why? It has free private repositories, you want that if you are writing a novel, right? Also, it has a free `continuous integration` feature called Pipeline, this can be configured to create your ebooks each time you save you work.

- Commit your changes and push up to [Gitlab](http://gitlab.com)
- Set up a pipeline for building your
- Check the pipeline for success
- Download the build artefacts 
- Read...

## Using GitHub

GitHub is great if you are writing open source books etc. It has more users and a greater potential readership.

I'll post up some information on how this template will work.

## Support this work

If you like what you find here, and or what updates, please send some  :heart: .

[SEND SOME LOVE](http://www.avastmick.io/donate)
