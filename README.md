*This repository is a mirror of the [component](http://component.io) module [tmcw/coords](http://github.com/tmcw/coords). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/tmcw-coords`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
Parse more forms of latitude, longitude, including the
[sexagesimal](http://en.wikipedia.org/wiki/Sexagesimal) form.

```javascript
coords.parse('66° 30′ 0″ N');
// 66.5

coords.parse('66° 30′ 0″ S');
// -66.5

coords.parse('66.5');
// 66.5
```
