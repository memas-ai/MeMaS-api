# MeMaS-api

This package contains the OpenAPI specs of MeMaS, as well as gradle scripts using OpenAPI Generator to generate MeMaS client and SDKs for various languages.

Currently we generated clients and sdks for the following languages:
- Java
- Python
- Typescript (Node)
- Go
- Rust

They have each been cloned as submodules in this repo. Running commands like `./gradlew javaClient` or `./gradlew javaSDK` will regenerate these packages.