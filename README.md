# graph-pusher-android
Realtime Android app that graphs the used RAM memory from a the Node.js script you can find in this [repo](https://github.com/eh3rrera/memory-pusher). 

# Requirements

- [Android Studio 2.3.1](https://developer.android.com/studio/index.html)
  - MinSdkVersion: 15
  - TargetSdkVersion: 25
  - buildToolsVersion: 25.0.2
- [Pusher account](https://pusher.com/signup)

# Installation
1. Clone this repository and open it with Android Studio.
.......l.3. Enter your Pusher app information in `com/pusher/memorygraph/MainActivity.java`.
4. Build the project and run it.
5. Execute the Node.js process (with the same Pusher app information) and see how the graph is updated in realtime.

# LICENSE
MIT
