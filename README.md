# StudyRepository
* Architecure guides & naming covention : https://github.com/ribot/android-guidelines
* Android study : https://github.com/codepath/android_guides/wiki
* Example about screen : https://pttrns.com
* Gradle for android : https://www.udacity.com/course/gradle-for-android-and-java--ud867
* Advanced android : https://www.udacity.com/course/advanced-android-app-development--ud855
* Sample code : https://github.com/googlesamples/android-architecture/tree/dev-todo-mvp-kotlin,
https://github.com/googlesamples/android-architecture/tree/todo-mvp

* Pratice android : https://codelabs.developers.google.com/?cat=Android
* Dagger 2 : https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-dagger-2-part-i-f2de5564ab25
* RxJava,RxAndroid : https://www.androidhive.info/RxJava/tutorials/
* Java concurrent: https://github.com/eugenp/tutorials/tree/master/core-java-concurrency 



* UnitTest: https://stackoverflow.com/questions/39310848/what-is-the-difference-between-powermock-easymock-and-mockito-frameworks


What I've learned :
*tracking location : Realtime databse + location
*Job schedule : GCM Manager.
*Affected by Idle & Standby state :
*Idle state : low power.
*Standby state : user didnt click screen perioidcally
*Idle suspends background job(scheduler,service,..), GCM(set priority : high), Alarm manager(setAllowtoIlde).
*Standby suspend background job but GCM.
