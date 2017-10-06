# React-Native Echo
WebRTC and Kurento Media Server Integration Demo for React-Native

## Description
The client will stream audio to the application server via Webrtc. The application server will then process the stream through Kurento Media Server. The audio stream will then be fed back to the same client.

## Reference
- [react-native-webrtc](https://github.com/oney/react-native-webrtc)
- [Kurento](https://www.kurento.org/)



## Setup

#### KMS
[KMS Setup Guide](http://doc-kurento.readthedocs.io/en/stable/installation_guide.html)


#### Application Server

- cd EchoServer
- npm install
- npm start

#### Client

- cd EchoClient
- npm install
- react-native start

For Android:
- react-native run-android

For iOS:
- react-native run-ios



## License

 Copyright 2017 Jerameel M. Delos Reyes

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
limitations under the License.
