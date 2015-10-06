# thejourney15-app


The map will be an `<iframe>` embedded in the wordpress page, using whatever shortcode for wordpress. 

The app hasn't been thoroughly tested yet, and might have bugs and inconsistencies across mobile devices. Let us know if you find anything. Styling of pins, dialogs, buttons, etc. can be changed if you have any suggestions. 


Todo
---

**Bugs**

- [ ] Side nav menu closes on filter
- [ ] Unfocus search bar on side nav open.
- [ ] recalculate route when userlocaiton is found and hide side nav
- [ ] show() touchbutton after css is loaded
- [ ] Download and resize all images.
- [ ] Show image placeholder
- [ ] Add spinner or fake photo behind images
- [ ] Add calculating route toast.
- [ ] Change vertical menu to info icon.
- [ ] mapbox cache tiles.
- [ ] make touch here button responsive to mobile (smaller)


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
- [ ] Create introduction help overlay, for first time actions.
- [ ] Make 'next directions' appeear 
- [ ] Create custom map tiles
- [x] Star/bookmark this pin
- [x] Load/Share your journey link
- [ ] Pinch zoom to open modal with image.
- [ ] Swipe popup to show next marker.
- [ ] represent theme filters in two columns


**Routes**

- [x] Create optimized round-trip route based on your location.
- [ ] Route directions
- [ ] Choose Walk, Cycle, Drive.
- [ ] Nearest site to me
- [ ] Drop pin to suggest site
- [ ] Save route in cookie

**Data**

- [x] Translated our original Google sheet into .geojson data we can edit at www.geojson.io
- [x] Use Google to link URLs in case of missing data.
- [ ] Ensure Data is complete. (photos, descriptions, themes)

**Optimize**

- [ ] Minify CSS, JS.
- [ ] Gzip compression (AILA server?)

