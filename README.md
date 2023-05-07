Download Link: https://assignmentchef.com/product/solved-lab-1-gps-location-reverse-geocoding-simple-http
<br>
<strong>IMPORTANT. </strong>You must save all your work in a way that you are able to present them to teacher during the evaluation discussion. You could use for instance GIT. You also need to have working developer environment where you can run the assignments.

Please view all videos and documents from Moodle first.

<h2>1. GPS Location</h2>

Create an Android app which shows GPS location on the device screen.

You have two possible apis which you could use to fetch the location (you can choose or do both ways)

Older API: <a href="https://developer.android.com/guide/topics/location/strategies">https://developer.android.com/guide/ </a><a href="https://developer.android.com/guide/topics/location/strategies">topics/location/strategies</a>

Newer API: <a href="https://developer.android.com/training/location/retrieve-current">https://developer.android.com/training/ </a><a href="https://developer.android.com/training/location/retrieve-current">location/retrieve-current</a>

Please note that you must declare permissions in the manifest file and also ask the permission runtime. More info from here: <a href="https://developer.android.com/training/permissions/requesting#java">https://developer.android.com/training/permissions/ </a><a href="https://developer.android.com/training/permissions/requesting#java">requesting#java</a>

<h2>2. Reverse geocoding</h2>

Reverse geocoding is a way to get an address based on the latitude and longitude coordinates.

Modify previous assignment in a way that it will show the lat / lon coordinate + city and country for that location.

This class will help you: <a href="https://developer.android.com/reference/android/location/Geocoder.html">https://developer.android.com/reference/android/location/ </a><a href="https://developer.android.com/reference/android/location/Geocoder.html">Geocoder.html</a>




<h2>3. Simple HTTP</h2>

Create app that can be used to load textual content from network addresses. Please follow the ui style on the image.

You can use this class to fetch data: <a href="https://developer.android.com/reference/java/net/HttpURLConnection">https://developer.android.com/reference/java/net/ </a><a href="https://developer.android.com/reference/java/net/HttpURLConnection">HttpURLConnection</a>

Remember to Add INTERNET permission to manifest file.

Also, because we have not yet studied thread programming you must add this code to make possible to load data from the network in the main (ui) thread.

StrictMode.ThreadPolicy policy =

new StrictMode.ThreadPolicy.Builder().permitAll().build();

StrictMode.<em>setThreadPolicy</em>(policy);