<!--
    Copyright (c) 2017
    @author:        Sean Denny
    @description:   Fluent Design Custom Elements by SD
    @license:       MIT
    @source:        https://github.com/Nektro/fluent-elements
-->
# Fluent Elements

[Fluent Design](http://fluent.microsoft.com/) is the design guideline for Universal Windows Platform
applications. Using the Custom Elements in this package it is possible to use many of the UWP components
in your web apps.

Make sure to check the browser compatibility for Web Components in your tests!
- [Custom Elements v1](https://caniuse.com/#feat=custom-elementsv1)
- [Shadow DOM v1](https://caniuse.com/#feat=shadowdomv1)
- [HTML Imports](https://caniuse.com/#feat=imports)(Recommended)([Polyfill](https://github.com/webcomponents/html-imports))

📘 = link to Fluent Design documentation  

## Elements (Coverage)

### Layout
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/lists) `<fl-listview>`
- [x] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/navigationview) `<fl-navigationview>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/split-view) `<fl-splitview>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/tabs-pivot) `<fl-pivot>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/tree-view) `<fl-treeview>`

### Input
- [x] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/buttons) `<fl-button>` (`<button is="fl-button">`)
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/checkbox) `<fl-checkbox>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/color-picker) `<fl-colorpicker>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/calendar-date-picker) `<fl-calendardatepicker>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/date-picker) `<fl-datepicker>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/time-picker) `<fl-timepicker>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/auto-suggest-box) `<fl-autosuggestbox`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/radio-button) `<fl-radiobutton>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/rating) `<fl-ratingscontrol>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/search) `<fl-searchbox>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/slider) `<fl-slider>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/text-box) `<fl-textbox>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/password-box) `<fl-passwordbox>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/toggles) `<fl-toggleswitch>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/lists#drop-down-lists) `<fl-combobox>`

### Other
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/hyperlinks) `<fl-hyperlink>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/images-imagebrushes) `<fl-image>`
- [x] [📘](https://docs.microsoft.com/en-us/windows/uwp/style/segoe-ui-symbol-font) `<fl-icon>` (\*Requires Windows 10)
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/calendar-view) `<fl-calendarview>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/person-picture) `<fl-personpicture>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/progress-controls#progressbar) `<fl-progressbar>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/progress-controls#progressring) `<fl-progressring>`
- [ ] [📘](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/progress-controls) `<fl-inprogressbar>`

## Notes
- [Default font](https://docs.microsoft.com/en-us/windows/uwp/style/typography) on `body` is set to [`Segoe UI`](https://www.microsoft.com/typography/fonts/family.aspx?FID=331)
- `todo` Style the [Scroll Bar](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/scroll-controls) to Windows UWP style
- `todo` Add [ToolTip](https://docs.microsoft.com/en-us/windows/uwp/controls-and-patterns/tooltips)s

## Colors Cheatsheet
- `#cfcfcf` - light gray
- `#7f7f7f` - basic border
- `#0078cf` - accent blue
- `#afafaf` - dark gray
