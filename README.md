**Forked repo**

!!! Fork from original https://github.com/olofd/react-native-photos-framework repo

**Works on**

RN 0.60+

**Updated instructions:**

Automatic:

`npm i --save rn-photos-framework`

then

`react-native link rn-photos-framework` and remove Android linking afterwards

Manually:

In package.json add:

`"rn-photos-framework": "vforvasile/rn-photos-framework",`

Add to your Podfile in ios/Podfile:

`pod 'rn-photos-framework', :path => '../node_modules/rn-photos-framework'`

**Original documentation:**
[Guide](./docs/HowToUse.md)
