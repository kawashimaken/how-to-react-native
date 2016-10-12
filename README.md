# how-to-react-native
react native development memo

## Tool

Atom

## upgrade react-native
```
react-native upgrade
```

see difference, press d

## after overwrite, you need to do the following

update the info.plist in order to make network access work at development mode.

Add the following to 
```
<key>your_great_domain</key>
  <dict>
    <key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
      <true/>
  </dict>
  
```
under NSAppTransportSecurity->NSExceptionDomains

## if you are using map

[https://github.com/airbnb/react-native-maps](https://github.com/airbnb/react-native-maps)

```
react-native link
```
