## How to reproduce

Run the following command and verify it works:
```shell
./gradlew m1:byteBuddy
```

Now run this next command and verify it doesn't work:
```shell
./gradlew --parallel m1:byteBuddy
```
