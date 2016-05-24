# Android M-Pin SDK

## Building the M-Pin Mobile SDK for Android

### Prerequisites

1. Download and install Android Studio or higher with Android SDK 16 or higher
1. Download or Clone the project and its submodule to \<mpin-sdk-android\>

### Building the M-Pin Mobile SDK

#### From Android Studio
1. Import the project - File-> Open -> \<mpin-sdk-android\>
1. From Gradle Tool View select :mpinsdk -> Tasks -> build -> build
1. The assembled aars will be located in \<mpin-sdk-android\>/mpinsdk/build/outputs/aar

#### From Command Line
1. Navigate to \<mpin-sdk-android\>
1. Execute ./gradlew build
1. The assembled aars will be located in \<mpin-sdk-android\>/mpinsdk/build/outputs/aar

For further details, please see the [Milagro Documentation](http://docs.milagro.io)
