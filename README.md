# BelaLibrary
#gradle 
#step1
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
 #step2
 dependencies {
	        implementation 'com.github.belatyara:BelaLibrary:Tag'
	}
  
