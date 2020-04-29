# Dotnet project sample

Sample to test license_finder and gradle

## use dotnet command

```
dotnet restore # restore obj dir
```

## license_finder directly 

```
license_finder --project-path=.\src\
```

## license_finder gradle

```
gradlew  clean msbuild # build project
gradlew clean report # report license use into your project
```