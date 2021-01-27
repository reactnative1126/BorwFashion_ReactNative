![Build Android](https://build.appcenter.ms/v0.1/apps/634daa85-c3a6-4910-b997-13879c74028c/branches/testing/badge)


# Set up fastlane
### for first time
	- Step 1: Install rvm https://rvm.io/rvm/install
  ```\curl -sSL https://get.rvm.io | bash```

	- Step 2: Sync terminal: https://stackoverflow.com/questions/11677771/rvm-command-not-found-mac-ox
  ```$ source ~/.rvm/scripts/rvm```

	- Step 3:
  ```$ cd ./fastlane```
  run to install bundler
  ```gem install bundler```

### If already install bundler
	- Step 4: run bundle to install fastlane and some dependent libraries
  ```bundle```

# Autobuild
- Both iOS and Android:
``` ./build.sh```

- Only iOS
```sh
  cd ./fastlane
  fastlane ios beta
```

- Only Android
```sh
  cd ./fastlane
  fastlane Android beta
```