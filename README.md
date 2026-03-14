# Hello Scala Native

## First install needed things under Ubuntu

Scala: https://www.scala-lang.org/download/

gcc etc:

```
sudo apt install clang libstdc++-12-dev libgc-dev 
```

## Run and package with scala:
scala package . --native --power --force -o hello

## Run with sbt:
sbt run
