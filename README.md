# thejourney15-app


The map will be an `<iframe>` embedded in the wordpress page, using whatever shortcode for wordpress. 

The app hasn't been thoroughly tested yet, and might have bugs and inconsistencies across mobile devices. Let us know if you find anything. Styling of pins, dialogs, buttons, etc. can be changed if you have any suggestions. 


Todo
---

**Bugs**

- [x] Side nav menu closes on filter
- [x] Unfocus search bar on side nav open.
- [x] recalculate route when userlocaiton is found and hide side nav
- [x] show() touchbutton after css is loaded
- [x] Change vertical menu to menu icon.
- [x] disable all interaction with map (not just zoom) until touchbutton is pressed.
- [x] make touch here button responsive to mobile (smaller padding)

- [x] make button to change journey type.
- [x] create new full screen icon
- [x] regex the slash out of isntructions.
- [x] download all photos
- [ ] less jerky motion
- [ ] option to close navigation -pane
- [x] make menu collapse smaller
- [ ] color grading
- [ ] get rid of category.
- [ ] proportion the slider to distance
- [ ] put something useful in bubble.
- [ ] move to the ftp
- [ ] test the loading query params
- [ ] create share my journey button
- [ ] create an about collapse with explanation of site.



**functions**

- [x] Filter by walking route
- [x] Search by keyword
- [x] Find my location
- [x] Full screen option
- [x] Show similar pins on hover
- [x] Bouncing markers!
- [x] Add friendly tooltips, toasts, etc.
- [x] Warn user when 26 waypoint limit reached
- [x] ~~Take photo button~~ Tweet this location
- [x] Star/bookmark this pin
- [x] Load/Share your journey link

- [ ] Create introduction help overlay, for first time actions.
- [ ] Create custom map tiles
- [ ] Add spinner or fake photo behind images
- [ ] Fade images in once loaded.
- [ ] Download and resize all images.
- [ ] clear filters button in side nav.
- [ ] Show image placeholder
- [ ] Pinch zoom to open modal with image.
- [ ] Swipe popup to show next marker.
- [ ] Twitter popoup, instead of new window


**Routes**

- [x] Create optimized round-trip route based on your location.
- [x] Route directions
- [x] Choose Walk, Cycle, Drive.
- [ ] Nearest site to me
- [ ] Drop pin to suggest site

**Data**

- [x] Translated our original Google sheet into .geojson data we can edit at www.geojson.io
- [x] Use Google to link URLs in case of missing data.
- [ ] Ensure Data is complete. (photos, descriptions, themes)

**Optimize**

- [ ] Minify CSS, JS.
- [ ] Gzip compression (AILA server?)

