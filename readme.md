<img width="180" alt="Screenshot 2025-06-27 at 5 59 56 PM" src="https://github.com/user-attachments/assets/59cd1fc9-fefe-46cb-8d7a-eccda6f19713" /># Facial Recognition with JavaScript using face-api.js
### To start up the app:
1. run npm install in the root directory
2. run node on server.js
3. go to http://localhost:3000

### Loading 4 primary models
``` javascript
    await Promise.all([
        faceapi.nets.ssdMobilenetv1.loadFromUri('./models'),
        faceapi.nets.faceLandmark68Net.loadFromUri('./models'),
        faceapi.nets.faceRecognitionNet.loadFromUri('./models'),
        faceapi.nets.ageGenderNet.loadFromUri('./models'),
    ])
```
### example output 

<img width="177" alt="Screenshot 2025-06-27 at 6 00 45 PM" src="https://github.com/user-attachments/assets/3521c1d0-8b34-40ea-87c9-b3c26649eea9" />
