To use Config for GCP . Eg below textToSpeec

```
// Imports the Google Cloud client library
const textToSpeech = require('@google-cloud/text-to-speech');

// Create the auth config
const config = {
  projectId: 'grape-spaceship-123',
  keyFilename: '/path/to/keyfile.json'
};

// Creates a client
const client = new textToSpeech.TextToSpeechClient(config);
```
