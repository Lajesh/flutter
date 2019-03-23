# Flutter

**Flutter** is the Google's cross platform mobile UI framework. It is no secret that Google is working on a third operating system 
that might someday replace whole Android and Chrome. Its called **Fuchsia**. It has been hearing out loudly that the new OS would solve the problem of Android fragmentation but still allowing google to run it on different types of devices including smartphones, tablets and computers.

Along with the new OS , Google is also working on new coding engine that will allow developers to deploy apps to all platforms 
including IOS. The main advantage of flutter is that the Companies don't have to invest in two development teams for Android and IOS
.With Flutter, the companies can code their app at the same time and then deploy then on Android and IOS simultaneously.

As the stable version of the flutter has been introduced, i would strongly recommend all Android developers to give a try.
I will be writing up a series of articles on flutter in the coming weeks. In this tutorial i am going to explain how we can setup flutter in mac.

# Step by step instruction on setting up flutter

# System Requirements

To install and run Flutter seamlessly, the development machine should have the following minimum requirements

- **Operating System** : Mac OS (64 bit)
- **Processor**: Intel Core i5 or higher
- **RAM**: 8GB or higher
- **Disk Space**: 2 GB or higher

# Flutter SDK Installation

1. Download Android studio and install all the required SDKs and tools.
   https://developer.android.com/studio

1. Download the latest stable release of flutter SDK from the below URL.
   https://storage.googleapis.com/flutter_infra/releases/stable/macos/flutter_macos_v1.2.1-stable.zip

2. Extract the dowload package and unzip it to the desired location.

3. Add flutter tool and Android SDK path to the PATH variable. For doing this open terminal and type the below command. 
   ``` touch ~/.bash_profile; open ~/.bash_profile ```
   This will open the bash_profile, now we have to add the following paths in the file.
   ```export PATH=/Users/lajesh/Documents/SDKs/flutter/bin:$PATH ```
   ```export PATH=/Applications/SDK/:$PATH ``` (Update with the actual path)
   
   Once the above paths are added, close the file which will ask you to save the changes. Save the changes and return back to    terminal.
 
    
 

