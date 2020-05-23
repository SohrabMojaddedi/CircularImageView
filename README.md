Installation
Add this into your root build.gradle file:

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Add the dependency to your module build.gradle:

dependencies {
	        implementation 'com.github.SohrabMojaddedi:CircularImageView:1.0.0'
}
