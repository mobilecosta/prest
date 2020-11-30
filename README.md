# <img align="right" src="https://postgres.rest/logo.png" alt="RESTful API" title="RESTful API"> pREST
[![Build Status](https://travis-ci.org/prest/prest.svg?branch=master)](https://travis-ci.org/prest/prest)
[![GoDoc](https://godoc.org/github.com/prest/prest?status.png)](https://godoc.org/github.com/prest/prest)
[![Go Report Card](https://goreportcard.com/badge/github.com/prest/prest)](https://goreportcard.com/report/github.com/prest/prest)
[![codecov](https://codecov.io/gh/prest/prest/branch/master/graph/badge.svg)](https://codecov.io/gh/prest/prest)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/prest/prest?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Open Source Helpers](https://www.codetriage.com/prest/prest/badges/users.svg)](https://www.codetriage.com/prest/prest)

Serve a RESTful API from any PostgreSQL database, forked and updated to deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

This doesn't deploy a Postgres database for you on purpose, you should attach your Postgres database manually. 

## WARNING!!##
This version has JWT auth disabled by default.. don't deploy unless you want to expose your DB to the world! 

## Postgres version

- 9.4 or higher

## Problem

There is PostgREST written in Haskell, but keeping Haskell software in production is not an easy job. With this need pREST was born. [Read more](https://github.com/prest/prest/issues/41).

## Documentation

https://postgres.rest/ ([source](https://github.com/prest/prest.github.io))
