# Quiz Step Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Quiz Step Completed",
    "quiz": {
        "quizName": "<quizName>",
        "quizStep": "<quizStep>",
        "quizStepNumber": <quizStepNumber>,
        "quizStepResponse": "<quizStepResponse>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|quiz.quizName|string|The name of the quiz being tracked.  Should be the same for all steps within the quiz|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||
|quiz.quizStep|string|Describes the step within a quiz. Should depict the question being asked.|Indoor \/ Outdoor, Durability, Mood|||||||
|quiz.quizStepNumber|integer|Indicates the step number within a multi-step quiz. |1, 2, 3, 4||||1|||
|quiz.quizStepResponse|string|Describes the reponse to a quiz step upon step completion|Hardwood, High Traffic, Happy, Fiction|||||||




