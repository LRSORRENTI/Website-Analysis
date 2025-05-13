# Heritage Fence

https://heritagefencellc.com/

## First Impressions

Footer looks great, I like the layout and schema

I like the layout for the /fence-types pages, has a clean layout with the text boxes anchored on the sides of the images
EX:
https://heritagefencellc.com/fence-types/wood-fence/

The layouts on the /fence-installations pages also have a nice style, I like the two-tone container style, I think it's a great technique to display content related to fence types
EX: https://heritagefencellc.com/fence-installation/pool-fence/

Perfect choice of background images for many of the section hero containers EX: https://heritagefencellc.com/deck-construction/ This background images is perfect for the tone of the page

## Main page 'Get a free estimate button'

I noticed that this button is only clickable on the left half? I added a higher z-index and position relative in the chrome dev tools to test which allows the button to have full functionality:

```.elementor-21 .elementor-element.elementor-element-af4cbfa .elementor-button {
    z-index: 2;
    position: relative;
}
```
