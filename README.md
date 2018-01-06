# TeamSpeak 3 country flags

[![Join the chat at https://gitter.im/ts-3/less-country-flags](https://badges.gitter.im/ts-3/less-country-flags.svg)](https://gitter.im/ts-3/less-country-flags?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Donate](https://img.shields.io/badge/%E2%99%A5-donate-459042.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MAKZLQGRSBCT2)

This package is intended to help you to use TeamSpeak 3 country flags into your applications.

## Installation
```
npm install @ts3/country-flags
```

## Usage

You have to publish the `public` directory. The flags directory contains all the flags used with the
TeamSpeak 3 client. The less directory contains the less file which help you to use the flags into your web application.

To display the french flag use the CSS classes `ts3 country-fr`, this work for all flags.

```html
<span><i class="ts3 country-fr"></i> French flag</span>
<span><i class="ts3 country-de"></i> German flag</span>
<span><i class="ts3 country-ca"></i> Canadian flag</span>
```

## License

This project is licensed under ISC license. All country flags images are the property of their respective owner and 
are not covered by this license.
