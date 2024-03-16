This is a fork of https://github.com/m4gr3d/Godot-Android-Plugin-Template which is provided by godot's official documentation: https://docs.godotengine.org/en/stable/tutorials/platform/android/android_plugin.html#building-a-v2-android-plugin

It integrates the GameAnalytics sdk (Code taken from https://github.com/GameAnalytics/GA-SDK-GODOT/tree/master/android_godot_3_2)
so it can be built and used by godot 4.2+

I'm using this in my project so i'll aim to maintain this as much as i can for future godot builds.

## Usage

- Download the files from [arr-plugins](/arr-plugins) and copy inside your godot project inside android/plugins
- Check gradle build and GameAnalytics in project->export->Android in godot


## Updating and building aar 

- I used java 17 from https://adoptium.net/en-GB/temurin/releases/?variant=openjdk17 (reference by godot official docs)
- Install Android SDK which installs graddle in your local env
- Checkout root project here 
- Run `./gradlew.bat assemble`
- Files build will be located under `GodotGameAnalytics\build\outputs\aar`
- Plugin usage docs can be found [here](https://docs.gameanalytics.com/integrations/sdk/godot/#initialization)