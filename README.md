## LOLCales

LOLCales is a simple iOS app that outputs the available locales on a device/simulator. That's it.


### Command line usage
In order to run in the Simulator from the command line, you need a tool such as [WaxSim](https://github.com/square/WaxSim) ([or this updated fork](https://github.com/jonathanpenn/WaxSim)) to launch the Simulator with the app:

```
xcodebuild -sdk iphonesimulator && waxsim build/Release-iphonesimulator/LOLCales.app
```