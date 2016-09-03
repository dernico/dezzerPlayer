![Deezer](http://cdn-files.deezer.com/img/press/new_logo_white.jpg "Deezer") 

## NanoPlayer

NanoPlayer is a C application which uses Deezer's Native SDK to play a song once a user was authenticated.

### Features

 - User authentication
 - Playing a Deezer song.

### Build instructions

* Download the latest version of the [Deezer Native SDK][1]
* Unzip it and place the folder, renamed into NativeSDK, at the root of this repository, such as shown below:
```
<native-sdk-samples>
├── NativeSDK
│      ├── Bins
│      └── Include
├── NanoPlayer
└── README.md
```

* To build the sample on Linux and Mac OS
```
> cd NanoPlayer
> make
```

* To build the sample on Windows

Open `NanoPlayer.vcxproj` with Microsoft Visual Studio (2012 or upper).

### Run this sample

* On Linux and Mac OS

(On Linux the application will need **_pulseaudio_** packaged installed.)

```
> ./NanoPlayer
```

* On Windows

Run it through Microsoft Visual Studio debug tool or copy the Deezer Native SDK DLLs in the generated executable folder if you want to execute it in standalone.

 [1]: http://developers.deezer.com/sdk/native
