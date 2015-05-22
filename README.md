# gretzky.js

![Gretzky Face](/images/gretzky.png?raw=true)

**The Great One**

### Installation

`bower install https://github.com/mondorobot/gretzky.git`

### Usage
1) Bower install

2) Include `base.js` and `factory.js` on the page

3) Extend widgets using `$.widget('mondo.*YourWidgetNameHere*', $.mondo.base, { ...`

4) Call `window.WidgetFactory.refresh()` to instantiate/refresh widgets

### Dependencies
- jQuery
- jQuery UI (just the Widget module)
- Vanilla JS (at least v5.0)
