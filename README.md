**Tag for debug logs**

Add this tag like following:

    Log.d(OlegSPY, "some debug log message that you don't ever want to see in the app repository")

**Gradle**

Module:

    implementation 'org.niksi.olegspy:OlegSPY:0.0.1'

Project:

    allprojects {
        repositories {
            ...
            maven { url 'https://dl.bintray.com/olegryz/niksi'}
        }
    }
