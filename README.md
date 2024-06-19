# ROTT
ROTT is a personal OTT channel project made with love using BrightScript, BrighterScript and SceneGraph for fun and educational purposes.

## BrighterScript based project
Written in [BrighterScript](https://github.com/rokucommunity/brighterscript) and initially forked from [BrighterScript-Template](https://github.com/rokucommunity/brighterscript-template). Collection video gallery is from https://jonathanbduval.com, made available inside this repo for HA. HLS streams are Big Buck Bunny =:3 from https://test-streams.mux.dev, Video test from Bitmovin https://cdn.bitmovin.com/content/assets/art-of-motion-dash-hls-progressive/m3u8s/f08e80da-bf1d-4e3d-8899-f0f6155f6efa.m3u8 and Video Test from Flowplayer https://cdn.flowplayer.com/a30bd6bc-f98b-47bc-abf5-97633d4faea0/hls/de3f6ca7-2db3-4689-8160-0f574a5996ad/playlist.m3u8. Icons by https://remixicon.com/.

## To-do milestone list:
- [x] Base app.
- [x] Use an open database of movies to display on a grid.
- [x] Create detailed view of individual content.
- [ ] Create video player with playable content.
- [ ] Integrate Unit Testing (Roca / Rooibos).
- [ ] Double check entire app and latest version of BrighterScript for any upgradeable code BRS -> BS.

## Setup instructions
1. Install npm dependencies
    ```bash
    npm install
    ```
2. Build a zip of the project
    ```bash
    npm run package
    ```

## Debugging
This repository comes pre-configured to work with the [BrightScript Language](https://github.com/rokucommunity/vscode-brightscript-language) extension for Visual Studio Code / VSCodium. So once you have that plugin installed, debugging your project is as simple as clicking the "Start Debugging" button.
