## PlayJson for AkkaHttp

[![Build Status](https://github.com/evolution-gaming/akka-http-play-json/workflows/CI/badge.svg)](https://github.com/evolution-gaming/akka-http-play-json/actions?query=workflow%3ACI)
[![Coverage Status](https://coveralls.io/repos/github/evolution-gaming/akka-http-play-json/badge.svg?branch=master)](https://coveralls.io/github/evolution-gaming/akka-http-play-json?branch=master)
[![Version](https://img.shields.io/badge/version-click-blue)](https://evolution.jfrog.io/artifactory/api/search/latestVersion?g=com.evolutiongaming&a=akka-http-play-json_2.13&repos=public)
[![License](https://img.shields.io/badge/License-Apache%202.0-yellowgreen.svg)](https://opensource.org/licenses/Apache-2.0)

This project contains implicit marshaller and unmarshaller to enable simple endpoint and consumer development.  

## Setup

```scala
addSbtPlugin("com.evolution" % "sbt-artifactory-plugin" % "0.0.2")

libraryDependencies += "com.evolutiongaming" %% "akka-http-play-json" % "0.1.13"
```

## Usage
```scala
import akka.http.scaladsl.marshallers.playjson.PlayJsonSupport._
```