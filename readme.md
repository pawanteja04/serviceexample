# services
Services in Android is a component that facilitates an application to run in the background in order to perform long-running operation tasks. 

# implimentation
Add the following dependency to your app's build.gradle file:
dependencies {
implementation 'com.example.musicapp:services:1.0.0'
}
 Initialize the services in your application's onCreate() method:

MusicPlayerService playerService = new MusicPlayerService();
playerService.initialize(this);

