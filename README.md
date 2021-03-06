NimbusBase Android Tutorial
===========================

NimbusBase Android is a product that allows you to replicate your app's sqlite storage on to the personal cloud (Dropbox, box) storage of a user.

This app here is a simple app store that shows you how to link NimbusBase Android to your app.

For more information please visit our [Tutorial Page](http://nimbusbase.com/articles/tutorial-android.html).

## Try this out

The app is built base on sqlite and contains only one table named **User**, which you can explore under **Playground**.

![Playground to Table User](https://raw.githubusercontent.com/NimbusBase/NimbusBase_Android_Tutorial/master/Resource/Github/img/index_to_playground.png)

To create, retrieve, update and delete new records:
+ **Create**: Tap the **INSERT** button on the right top corner, fill some fields then tap **SAVE**
+ **Retrieve**: The **name** and **email** fields are displayed on the list view. For detail info, just tap an existent record
+ **Update**: Under the detail info mode, tap the **EDIT** button on the right top corner, edit it then tap the **UPDATE** button to confirm the changes
+ **Delete**: In list view, long press a record till the **DELETE** button pop up then tap it.

![CRUD Table](https://raw.githubusercontent.com/NimbusBase/NimbusBase_Android_Tutorial/master/Resource/Github/img/CRUD.png)

To sync your data to cloud

1. Sign in one cloud by tapping the switch on the right
1. Tap the signed in server to start synchronization

![To sync](https://raw.githubusercontent.com/NimbusBase/NimbusBase_Android_Tutorial/master/Resource/Github/img/sync.png)

Then you can check if your data is synced on another Android or iOS device or open up the folder containing your data and see the records themselves.

## How to run

### Run directly from .apk

Download [NimbusBase_Android_Tutorial.apk](http://nimbusbase.com/download/NimbusBase_Android_Tutorial.apk), and run.

### Build yourself

0. Clone the project to your computer with command `git clone https://github.com/NimbusBase/NimbusBase_Android_Tutorial.git`
0. Open the project with [Android Studio](https://developer.android.com/sdk/installing/studio.html), build it and run

## Relevance

You can also download our iOS tutorial and sync data between iOS and Android.

Companion project: [NimbusBase iOS Tutorial](https://github.com/NimbusBase/NimbusBase_iOS_Tutorial) 
