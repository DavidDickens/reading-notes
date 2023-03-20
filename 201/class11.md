## Class  11 Notes

## Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- Early 2000s: Flash video becomes popular. Adobe Flash was a plugin that allowed web developers to create interactive content, including video and audio. Flash video became popular in the early 2000s because it was one of the few ways to reliably play video on the web.

- Mid-2000s: YouTube is founded. YouTube was founded in 2005 and quickly became the dominant platform for sharing and watching videos on the web. YouTube used Flash video in its early days, but eventually switched to HTML5 video.

- Late 2000s: HTML5 video and audio. HTML5 introduced new tags for embedding video and audio directly in web pages, without the need for plugins like Flash. This made it much easier for web developers to create and share video and audio content, and paved the way for the rise of video-sharing platforms like Vimeo and Dailymotion.

- Early 2010s: WebRTC. WebRTC is a technology that allows web browsers to communicate with each other directly, without the need for plugins or additional software. This made it possible to create real-time audio and video communication applications directly in the browser, such as video conferencing and live streaming.  

## Describe the use of the src and controls attributes in the 'video' element.

- Users must be able to control video and audio playback. You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.


## Why is it important to have fallback content inside the 'video' element?

- This will be displayed if the browser accessing the page doesn't support the 'video' element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.

## Write a very short story where 'audio' and 'video' are characters.

- I really don't understand what you are asking for here.

## How does Grid layout differ from Flex?

- The basic difference between CSS Grid Layout and CSS Flexbox Layout is that flexbox was designed for layout in one dimension - either a row or a column. Grid was designed for two-dimensional layout - rows, and columns at the same time.

## Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- To make an HTML element behave as a grid container, you have to set the display property to grid or inline-grid.Grid containers consist of grid items, placed inside columns and rows.

- What goes into the grid container.

- To place an item on the grid, we set the line on which it starts, then the line that we want it to end on.

## Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- This helps to improve performance across different devices.

## Define the following 'img' attributes srcset and sizes. Write an example of how they are used.

- img, srcset, and sizes are used to provide several additional source images along with hints to help the browser pick the right one

## How is srcset more helpful for responsive images than CSS or JavaScript?

- srcset allows you to define a list of different image resources along with size information so that browser can pick the most appropriate image based on the actual device's resolution. The actual width of the image or display density.