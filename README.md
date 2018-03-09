# graph-pusher-android
Realtime Android app that graphs the used RAM memory from a the Node.js script you can find in this [repo](https://github.com/eh3rrera/memory-pusher). Follow the tutorial [here](https://pusher.com/tutorials/graph-android/).

## Getting Started

1. Clone this repository and open it with Android Studio.
2. Create a [Pusher app](https://dashboard.pusher.com).
3. Enter your Pusher app information in `com/pusher/memorygraph/MainActivity.java`.
4. Build the project and run it.
5. Execute the Node.js process (with the same Pusher app information) and see how the graph is updated in realtime.

### Prerequisites

- [Android Studio 2.3.1](https://developer.android.com/studio/index.html)
  - MinSdkVersion: 15
  - TargetSdkVersion: 25
  - buildToolsVersion: 25.0.2
- [Pusher account](https://pusher.com/signup)

## Built With

* [Pusher](https://pusher.com/) - APIs to enable devs building realtime features
* [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart) - Android chart view/graph view library

## Acknowledgments
* Thanks to [Pusher](https://pusher.com/) for sponsoring this tutorial.

## LICENSE
MIT
