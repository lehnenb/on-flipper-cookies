# On Flipping Cookies

Chrome extension used to set cookies for on developers


## Instructions

- First, build the project using: `yarn run dev`
- Then, go to: `chrome://extensions/` and enable the developer mode at the upper right-hand corner
- Finally, load the package by clicking on `Load unpacked` located at the upper left corner (you have to point to the folder where manifest.json file is, /dist in this case)

## FYI

If you have stored some feature flag cookies before loading the extension, the list will not immediately reflect that.
In order to fix that you have to add those feature flags and then change the value once or twice so the extension starts tracking it (it uses a separate storage mechanism).

## TODO

- Fix the initial cookie synch. mentioned above.


