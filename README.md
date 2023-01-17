# Flutter IntegrationTest

Flutter integration testting example

### Run commands without flavor

```dart
flutter drive \
  --driver=test_driver/integration_test_driver.dart \
  --target=integration_test/app_test.dart
```


### Run commands with flavor

```dart
flutter drive \                                                          
  --driver=test_driver/integration_test_driver.dart \
  --target=integration_test/app_test.dart --flavor stg lib/main_stg.dart
```



```dart
flutter drive \                                        
  --driver=test_driver/integration_test.dart \
  --target=integration_test/authentication_test.dart --flavor prod -t lib/main.dart
```

### Want to know what is integration testing ?

[Click here](https://martinfowler.com/bliki/IntegrationTest.html)
