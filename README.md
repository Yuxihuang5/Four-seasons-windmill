# Four Seasons Windmill

Interactive glass windmill with four seasonal scenes, mouse and camera-based hand controls.

## Publish

Push these files to the main branch. In repository Settings → Pages, select GitHub Actions as the build source. The included workflow publishes the site over HTTPS.

## Run locally

Run `python3 -m http.server 4173` and open http://localhost:4173/ . Camera gestures require localhost or HTTPS.

## Hand controls

Enable the hand button and allow the camera. Point with your right index finger to create seasonal elements. Open your right palm then close it to spin the windmill. The camera panel shows only a hand skeleton. Video stays in your browser.

MediaPipe Tasks Vision 0.10.21 and the hand model are bundled in vendor/vision. Original software: https://github.com/google-ai-edge/mediapipe (Apache-2.0).
