> Fork from [react-times](https://www.npmjs.com/package/react-times)

> A time picker react-component, no jquery-rely, writing in es6 standard style.

**Check [here](./doc/CHANGELOG.md) to see changed props in new version.**

# Play in local

```bash
$ git clone https://github.com/ecmadao/react-times.git

$ npm install

$ npm run storybook
```

# Install

dependencies:

- [`moment`](https://github.com/moment/moment/)
- [`react`](https://github.com/facebook/react)
- [`react-dom`](https://github.com/facebook/react)

> No jQuery rely 😤😤😤

So generally speaking, you should already have `react` & `react-dom` dependencies in your project. If not:

```bash
$ npm install react react-dom moment moment-timezone --save-dev
# and
$ npm install @zauberware/react-times --save-dev
```

# Usage

This component has two themes now: Material Theme by default, or Classic Theme.

> Always remember import css file when you use react-times

```javascript
// basic usage
// in some react component
import React from 'react';
import TimePicker from 'react-times';

// use material theme
import 'react-times/css/material/default.css';
// or you can use classic theme
import 'react-times/css/classic/default.css';

export default class SomeComponent extends React.Component {
  onTimeChange(options) {
    // do something
  }

  onFocusChange(focusStatue) {
    // do something
  }

  render() {
    <TimePicker
      onFocusChange={this.onFocusChange.bind(this)}
      onTimeChange={this.onTimeChange.bind(this)}
    />
  }
}
```

# Core Contributors from react-times 🎉

- **[carlodicelico](https://github.com/carlodicelico)**
- **[erin-doyle](https://github.com/erin-doyle)**
- **[MatthieuLemoine](https://github.com/MatthieuLemoine)**
- **[naseeihity](https://github.com/naseeihity)**
- **[shianqi](https://github.com/shianqi)**
- **[thg303](https://github.com/thg303)**

# License

[MIT License](./LICENSE)
