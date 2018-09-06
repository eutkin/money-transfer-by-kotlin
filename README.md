# CoinFlipper
An API built in Kotlin using[Ktor](http://ktor.io)and[exposed](https://github.com/JetBrains/Exposed)to generate random coin flips.

Run the app using gradle 
```
./gradlew run
```

or in the IDE. To flip a coin in the terminal (or browser) enter 

```
curl localhost:8080/flip
{"face":"HEADS"}

curl localhost:8080/flip
{"face":"TAILS"}

curl localhost:8080/flip
{"face":"HEADS"}
```
To see the results so far enter
```
curl localhost:8080/outcomes
[{"face":"HEADS"},{"face":"TAILS"},{"face":"HEADS"}]
```
