# Class 11 Notes

# Audio, Video, Images

#### Link to article: [Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content#video_and_audio_on_the_web)

#### Link to article: [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/#aa-grid-properties)

#### Link to article: [Responsive images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)


> Video, audio, and images are important components in HTML, CSS, and Javascript as they add a visual and interactive experience for the user. These elements can help to make webpages more engaging and attractive. They can also help to convey more information in a more effective way than text alone.

***

## Video and Audio Content

**Explain how the ability to use video and audio on the web has evolved since the early 2000s..**
> Since the early 2000s, the ability to use video and audio on the web has drastically improved. The emergence of faster internet speeds and more powerful computers has enabled streaming video and audio with little to no buffering, as well as higher video and audio quality. Additionally, new video and audio formats have been developed, such as HTML5, which has further improved the user experience.

**Describe the use of the src and controls attributes in the \<video> element.**
> The src attribute specifies the source of the video file, such as a .mp4, .ogg, .webm, etc. The controls attribute allows the user to control the playback of the video, such as play, pause, volume, etc. The controls can also include playback speed and fullscreen options.

**Why is it important to have fallback content inside the \<video> element?**
> Fallback content is important because it allows browsers that do not support the <video> element to display a message or alternate content. This ensures that all users, regardless of their browser, will have access to the content in some form. Fallback content also provides a backup in case the video fails to load, preventing users from being met with a blank page.

**Write a very short story where \<audio> and \<video> are characters.**
> Audio and Video were two inseparable friends. They enjoyed creating stories together, using their combined talents. Audio would provide the sound, while Video would provide the visuals. They worked hand in hand, complementing each other perfectly.

***

## A Complete Guide to Grid

**How does Grid layout differ from Flex?**
> Grid layout divides a page into rows and columns, allowing for precise placement of elements, while Flex layout distributes elements along a single axis and adjusts their size according to their parent container.

**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**
>
> - Grid Container: A Grid Container is an element that contains all the grid items and the lines that divide them. It defines the width and height of the entire grid.
>
> - Grid Item: Grid Items are elements that are placed into a grid container and laid out according to the grid lines. They can be any HTML element, such as a div or an image.
>
> - Grid Line: Grid Lines are lines that divide the grid into columns and rows. They are used to create a structure for the grid items to be laid out in.

## Responsive Images

**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**
> Responsive images can improve page loading speeds, reduce bandwidth usage, and help ensure users have a consistent experience across all devices. This provides a better user experience, as well as making the website more accessible to those with slower internet connections.

**Define the following \<img> attributes srcset and sizes. Write an example of how they are used.**
> The srcset and sizes attributes are used together to provide the browser with multiple image sources for the same image and to indicate the size of the image for each source. For example, the following code would give the browser three different image sources for a single image, and indicate the size of the image for each source:

\<img src="image.jpg" srcset="image-small.jpg 320w, image-medium.jpg 640w, image-large.jpg 960w" sizes="(max-width: 320px) 280px, (max-width: 640px) 640px, 960px" />

**How is srcset more helpful for responsive images than CSS or JavaScript?**
> Srcset is an HTML markup that allows the browser to make decisions about which image to load based on the size of the viewport. This makes the process of managing responsive images much more efficient and easier than using CSS or JavaScript. It also provides a more accurate and automated approach to delivering the right image at the right size. By adding width descriptors to the srcset attribute of an image, the browser can determine which image to load based on the available space, and can serve optimized images faster than with CSS or JavaScript.