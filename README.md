# Home Config BitBar Example [![Build Status](https://travis-ci.org/kodie/bitbar-home-config.svg?branch=master)](https://travis-ci.org/kodie/bitbar-home-config)
This is a small example of how to mimic the functionality of the [home-config npm module](https://www.npmjs.com/package/home-config) in a bash [BitBar](https://github.com/matryer/bitbar) plugin.

## Requirements
Since this uses associative arrays, bash 4.0 or higher is required. See how to upgrade to bash 4 on Mac OS X here: http://clubmate.fi/upgrade-to-bash-4-in-mac-os-x/

## Config Example
```
[home_config]
color=blue
text=This text came from the config file!
[another_plugin]
apiKey=c9ff119073ea2567730fb42e3a4fe805
```

## License
MIT. See the License file for more info.
