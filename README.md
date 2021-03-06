# @soubai/react-spotifycode

> React library for Spotify codes

[![NPM](https://img.shields.io/npm/v/@soubai/react-spotifycode.svg)](https://www.npmjs.com/package/@soubai/react-spotifycode) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save @soubai/react-spotifycode
```

## Usage

```tsx
import React, { Component } from 'react'

import SpotifyCode from '@soubai/react-spotifycode'

class Example extends Component {
  render() {
    return (
      <SpotifyCode code='spotify:user:spotify:playlist:37i9dQZF1DXcBWIGoYBM5M' />
    )
  }
}
```

## Props

The component accept a few props:

- **code**: The Spotify URI - **required**
- **format** The image format - 'jpeg' | 'png' | 'svg' - **default** : 'jpeg'
- **barColor**: Bar color - 'black' | 'white' - **default** : 'black'
- **backgroundColor**: The background color - **default** : '000' - **example** : '000' or '000000' for #000 color
- **size**: The image size on pixel - **default** : 640

## License

MIT © [AbderrahimSoubaiElidrissi](https://github.com/AbderrahimSoubaiElidrissi)