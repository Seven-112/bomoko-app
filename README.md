---
noteId: "20630520a92011ebbccd99903f9da0e3"
tags: []

---

# African Fintech APP

> Help Congolese small-scale farmers who are unbanked to have access to affordable loans using mobile phones (USSD). Our solution is to facilitate the financial inclusion of farmers and use mobile phones to give loans to smallholder farmers. Built with: React Native, Redux, Couchbase, Docker, and NodeJs. Play store, Official website,

Additional description about the project and its features.

## Built With

- React native
- React/Redux
- Expo
- Genymotion Android Emulator
- Docker, Nodejs and Couchbase (server side)
- localStorage

## Links

[Play store](https://play.google.com/store/apps/details?id=com.wezalab.bomoko4), 
[Official website](http://bomoko-app.com/)

## Getting Started

In order to run locally this project type the following commands over the terminal in Linux or Mac or the Windows cmd console:

```s
$ git clone https://github.com/myshine112/bomoko-app.git
$ cd bomoko-app
$ npm install
$ expo start

```

```s
$ npx expo start --offline
```

## Build

Now that we have set up our build profile and app signing, running a build for internal distribution is just like any other build.

`eas build --profile preview --platform all`

## Publish an update

Once the update is built and uploaded to EAS and the command completes, force close and reopen your app up to two times to download and view the update.

`eas update --branch preview --message "Updating the app"`
