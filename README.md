# PhotoFromPhotos
Create an "average" photo from a collection of photos.

## Goal
At the current time of writing the goal is to create an averaged photo based on a collection of photos.

- *Implementation* - Count the individual rgb values for each pixel and for each portrait, and divide those values by the number of portraits.

## Future Goals
- Smart cropping tool that takes a collection of images and then crops them all centered around a common object in all of the photos. We'll take the eyes for example. I could loop through to find the largest depiction of eyes and then zoom the rest of the photos in so that the size of the eyes match up.

## Concerns
- Handling different photo aspect ratio.


## Inspiration
- [Tiemen Rapati](https://www.flickr.com/photos/rapatski/5742643409/in/photostream
  )
- [Dylan Mason](https://medium.com/@dylnmasn/everyday-72e44ab3eed2)
- [Feltron](http://feltron.com/info.html) and [his talk](https://vimeo.com/122852255)
- [Noah Kalina](http://feltron.tumblr.com/post/31539534739/averaged-noah-kalina-via-kottke)
- [William Wilkinson](http://will.global) and his [everyday app](http://everyday-app.com)
