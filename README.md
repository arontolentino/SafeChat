
# SafeChat
- A Slack-like chatbot that detects whether text contains toxic content such as threatening language, insults, obscenities, identity-based hate, or sexually explicit language.

## Technology Stack
- HTML/CSS/JS
- [jQuery](https://jquery.com/)
- [Tensorflow.js](https://www.tensorflow.org/js) ([Text toxicity detection](https://github.com/tensorflow/tfjs-models/tree/master/toxicity))
- [Director.js](https://github.com/flatiron/director) (Routing)
- [Firebase Firestore](https://firebase.google.com/docs/firestore) (NoSQL DB)

## Minimum Viable Product (MVP)
- As a user, I can generate random insults and compliments.
- As a user, I can type my own insults or comments. 
- As a user, I can see a log of comments that went through the classifier (nice comments). 

## Stretch Goals
- As a user, I can see an emoji representation of what type of toxicity a comment represents. 
- As a user, I can attach my name to the comment. 
- As a user, I can reply to an existing comment. 
- Use regex to filter out really really really bad words. 
