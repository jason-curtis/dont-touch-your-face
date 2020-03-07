# Don't touch your face!!

## What is this??

Inspired by the COVID-19 outbreak. The [CDC recommends](https://www.cdc.gov/coronavirus/2019-ncov/about/prevention-treatment.html) that you avoid touching your eyes, nose or mouth to prevent contracting the disease.

[**Don't Touch Your Face**](donttouchyourface.net) runs in your browser and detects when you touch your face, and makes an annoying noise to stop you so that you won't contract COVID-19.

## How to use it

Visit [donttouchyourface.net](http://donttouchyourface.net). Then keep that tab open and go about your business.
The tab will constantly check for things that look like hands, covering things that look like faces.

*note: when the tab's in the background, the refresh rate is lower so it won't be as fast to catch you.*

## How it works

Don't Touch Your Face uses deep learning with the [tensorflow.js library](https://www.tensorflow.org/js) and two libraries that have been built on top of it.

Huge props to <a href="https://github.com/victordibia/handtrack.js">handtrack.js</a> which is used to track hands, and <a href="https://github.com/justadudewhohacks/face-api.js">face-api.js</a> which is used to find your face.
    

## Is it perfect?

nope. Sometimes there are false negatives and sometimes there are false positives.
I wrote this in an evening in under 200 lines of code. What a cool world we live in.


## See also

[CDC recommendations](https://www.cdc.gov/coronavirus/2019-ncov/about/prevention-treatment.html)