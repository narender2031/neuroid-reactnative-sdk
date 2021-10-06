# neuroid-reactnative-sdk

Neuro-ID React Native SDK

## Installation

- `yarn` from root directory
- Run `npm run updateSDK` in order to pull latest NeuroID Pod from Github and have it added to XCode project. Add the files to XCode, in the left hand rail file explorer. Make sure to select the TARGET when adding
- Add sqlite3 compiler options

If you are on a M1, install Podfile with `arch -x86_64 pod install` if you get stucks

## Usage

Run the example:
`yarn example ios`

```js
import { configure } from 'neuroid-reactnative-sdk';
configure('key_test_vtotrandom_form_mobilesandbox')

```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
