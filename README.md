# firebase-tools

[Firebase CLI](https://www.npmjs.com/package/firebase-tools) installed globally over the official [NodeJS image](https://hub.docker.com/_/node)

![version](https://img.shields.io/docker/v/liveonit/firebase-tools?sort=semver)
![image_pulls](https://img.shields.io/docker/pulls/liveonit/firebase-tools?label=pulls)
![build status](https://github.com/liveonit/firebase-tools/actions/workflows/default.yml/badge.svg)

```
THIS DOCKER IMAGE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE MAINTAINERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE DOCKER IMAGE OR THE USE OR OTHER DEALINGS IN THE DOCKER IMAGE.
```

## Quick reference

#### Tags & Dockerfiles
* [latest-node-18](https://github.com/liveonit/firebase-tools/blob/main/Dockerfile.node18)
* [latest-node-16](https://github.com/liveonit/firebase-tools/blob/main/Dockerfile.node16)
* [latest-node-14](https://github.com/liveonit/firebase-tools/blob/main/Dockerfile.node14)

#### Where to find more versions and tags
[the Tags page on Docker Hub](https://hub.docker.com/r/liveonit/firebase-tools/tags)

#### Where to file issues
[the Issues page on Github](https://github.com/liveonit/firebase-tools/issues)


## Image content

* Firebase CLI
* Firebase emulators
* Node.js (from the base image)
* OpenJDK 11
* Yarn (from the base image)

## Exposed ports

| Port | Purpose           |
| ---- | ----------------- |
| 4000 | Emulator Suite UI |
| 5000 | Firebase Hosting  |
| 5001 | Cloud Functions   |
| 8080 | Cloud Firestore   |
| 8085 | Cloud Pub/Sub     |
| 9000 | Realtime Database |
| 9005 | Firebase Login    |
| 9099 | Authentication    |
| 9199 | Cloud Storage     |

## Guides

[Running Firebase Emulators](https://github.com/liveonit/firebase-tools/blob/main/doc/guide/running_firebase_emulators.md)
