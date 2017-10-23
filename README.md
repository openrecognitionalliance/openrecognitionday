[![Build Status](http://travis-ci.org/openrecognitionalliance/openrecognitionday.svg?branch=master)](http://travis-ci.org/openrecognitionalliance/openrecognitionday)

## Open Recognition Day

25 October 2016, the participants at the [ePIC conference](http://openepic.eu) in Bologna launched the [Bologna Open Recognition Declaration](http://www.openrecognition.org/bord/). 

One year later, in 2017 the signatories of the Bologna Open Recognition Declaration took the initiative to launch the first [Open Recognition Day](https://openrecognitionday.org), a time to promote Open Recognition, calling for a universal open architecture for the recognition of lifelong and lifewide learning & the open endorsement of skills & achievements.

Participants can contribute to this day by organising their own events, such as ceremony awards, webinars, workshops, etc. 

Or online:  by giving recognition & get recognised for your achievements, skills , learnings or just as appreciation for who you are and what you do.

Check <https://openrecognitionday.org/> for public website.

## Editing / contributing

This site is built with [Lektor](https://www.getlektor.com/) & copied of the [Open Data Day](https://www.opendataday.org) website build by Open Knowledge Foundation. 

It has a bunch of [dependencies](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/package.json), so do `npm install` and then `npm run build`.

`grunt` will watch for changes to your [SCSS files](https://github.com/openrecognitionalliance/openrecognitionday/tree/master/assets/scss), and also [icons](https://github.com/openrecognitionalliance/openrecognitionday/tree/master/assets/icons) (see [svgstore](https://github.com/FWeinb/grunt-svgstore)).

`git push` will deploy to firebase hosting, putting changes live, if you have deploy permissions.

### TODO

#### Translations

To translate the site we need to duplicate the [contents.lr](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/content/contents.lr) file, and save with the language code in the file name, like [contents+de.lr](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/content/contents%2Bde.lr).

We also need to add translations to [global-content.ini](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/databags/global-content.ini) and [main-nav.ini
](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/databags/main-nav.ini).

If we are adding new language to the site we also need to:

- Add the new language to [languages.json](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/databags/languages.json)
- Add the language to [project.lektorproject](https://github.com/openrecognitionalliance/openrecognitionday/blob/master/project.lektorproject).


