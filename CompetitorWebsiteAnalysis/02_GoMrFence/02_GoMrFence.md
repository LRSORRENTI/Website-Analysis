# DotCom Project: https://gomrfence.com/

## First impressions

Looking under the hood it looks like it's not wordpress, it's linking to Bootstrap CDN, also using Jquery:

```html
<link
  rel="stylesheet"
  href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"
  integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u"
  crossorigin="anonymous"
/>

<script src="https://cdn.jsdelivr.net/npm/magnific-popup@1.1.0/dist/jquery.magnific-popup.min.js"></script>
```

## The Good

- Color palette jumps out to me straight away, clean use of white, soft white, light grey, and box shadows to create a clean modern look

- The Sections that are using a background image with dark overlay and another container within also with a lighter version of that overlay looks nice, they seem to strategically use these compounding overlays to cleanly display white or light colored text over images

- The Our Simple Process timeline with the dotted line connecting the steps is a clean look

- Their design theory around font weight and size for each section is well structured

- The way they anchor the h2 text & smaller text above it within the images on pages like https://gomrfence.com/fences/aluminum-fences/
  is a clean look

- Their of use of vimeo embed integrates nicely given their color palette, vimeo embeds in general have a clean look and their positioning of these elements next to text blocks are solidly designed EX on this page: https://gomrfence.com/fences/aluminum-fences/

- Contact form structure is clean, it's displayed in a slightly darker grey container, the form input fields are spaced out nicely within the body of the container

- The https://gomrfence.com/faqs/ page is well structured, clean layout, easy to sort through and filter using the left column select, although it becomes a bit of a double-edged sword on desktop as you'll need to scroll all the way back up to view the FAQS

- On the blog pages like https://gomrfence.com/blog/fences/vinyl-fence/best-dog-fence-options-from-a-trusted-indiana-fence-company/?_gl=1%2Ayp2tlz%2A_gcl_au%2AOTYyNTgyNzE0LjE3NDY3MjQ3NzU. the use of category pill tabs under the main blog title is an informative way to quickly attribute descriptors to the blog article

## The bad

- The 'areas we serve toggle' beneath the three column info section seems a bit visually lost, I think for UX it's not a great way to display content, I think for older users or visual impaired users that doesn't work well

- Footer content alignment seems nice, there is gap in the below part of the footer that would look cleaner if all were uniformly left aligned

```
EX:
Mr. Fence
1804 N Burkhardt Rd
Evansville, IN 47715
```

- Some general inconsistencies in the 'Instant Fence Estimator, Frequently Asked Questions, and Talk to the Fence Pros!' some text elements are left aligned, some are center aligned, this creates a disharmony in the design of the section, and actually on the https://gomrfence.com/testimonials/ page they address this issue, all of the above are text-align center

## Functionality overview

- They're using mysalesman fence estimate tool, seens to be widely used across competitor websites not just DotCom projects
