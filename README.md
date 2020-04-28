# Strava access token generator

Generate Strava API OAuth2 access token for testing purposes. 

Used in pet projects:
- [**stra-bash**](https://github.com/mgryszko/stra-bash) - Strava batch CLI tool written in bash language 
- [**kstrava**](https://github.com/mgryszko/kstrava) -  Strava batch CLI tool written in functional Kotlin using [Arrow](https://arrow-kt.io/)

## Installation 

### Prerequisites

Ruby executable. Tested on macOS with Homebrew Ruby environment managed by `rbenv`.

### Homebrew

```shell script
brew tap mgryszko/strava
brew install strava-access-token
```

## Usage

```shell script
strava-access-token <client_id> <client_secret>
```

If you don't have a client id/secret, register you app following the official [Strava documentation](https://developers.strava.com/docs/getting-started/#account)

