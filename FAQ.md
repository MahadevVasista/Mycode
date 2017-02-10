VISION

1.  How is age and gender determined?
> Using a predictive model trained on over 27 facial landmarks (as model features)

2.  What is OCR
> Optical Character Recognition

3.  Can we also analyse a building picture e.g Eiffle tower
> Yes, with the Computer Vision APIs (Computer Vision API offers image âtaggingâ, or person/place/thing identification, based on more than 2000 recognizable objects, living beings and actions).

4. How are the emotions are analyzed?
> Using the predictive model trained on basic facial expressions, emotion in a face is categorized and scored.  The emotions detected are:  happiness, sadness, surprise, anger, fear, contempt, disgust or neutral.

5. Can we have group of people to get the age and gender the image
> Yes, up to 64 faces in an image can be identified.

6. What is the scripting medium/ language behind the analysis algorithm (model)?
> One can write scripts to interact with the REST APIs in any language and we provide code samples in Curl, C#, Java, JavaScript, ObjC, PHP, Python and Ruby which can be found in the 'API Reference' of each API.

7. Based on emotion api and vision api , can it also identify whether he is swiming or drowning ?
> The combination of these two APIs is possible, but would be a custom add-on.

8.  The JSON that we see on the screen, is that returned as API response to a image being uploaded?
> Yes

9. Does these features work only on Azure Platform or are these service collections platform independent. Say for example can this be made to work on AWS - If so what are the prerequisites.
> These REST APIs may be called from anywhere, however most of the models are already trained and ready to use as-is (with the exception of Language Understanding, Knowledge Exploration and a few others).  The power is in, both the continually retrained models as well as the training data set (e.g. for Search APIs, billions of web records are used in the training set).

10. How do we integrate Cognitive API's with Chat bot
> These are covered in the class and at https://docs.botframework.com/en-us/bot-intelligence/getting-started/#navtitle

11. Are there existing models that can identify objects, for instance, merchandise at a retail store?
> Computer Vision API -> image analysis functionality

12. Are there existing models that can identify name of the brand etc
> Computer Vision API -> OCR functionality

13. Also I would like to know how accurately these images are predicted and by using which models of ML?
> The confidence scores for the "tagged items" in an image (people/places/things) are part of the response along with a natural language caption and associated confidence score.  For the ML algorithms used here, please see "The research behind Computer Vision API" section at the end of the documentation here:  https://www.microsoft.com/cognitive-services/en-us/computer-vision-api/documentation

14. Grouping? same set of people?
> Given one set of unknown faces, the face grouping capability (part of Face API) automatically divides them into several groups based on similarity. 

15. How do we train these API's to identify objects in a different category say products used in Retail or Manufacturing
> The models used in the Vision API are already trained and may be leveraged, but not retrained in a custom manner.

16.  Its so cool but how would it be so perfect to say the name and convey the emotions as it differs to person to person even though if you fix these values to calculate the emotion logically
> A score for 8 emotions are returned where the sum of all of the scores is 1 (so, normalized scores).

17. How to decide the image is billboard/camera, etc?
> The image is decomposed into pixels and a deep convolutional neural network model trained on a large dataset of other decomposed images is used in the Computer Vision API for object recognition.  The "decision" is based on the is trained model and the labeled data it has been trained upon.

18. Can we also get the details of how we capture & Analyse these APIs in backend?
> See 17.

19. What are the criteria to decide the emotions?
> It's based on facial markers.

20. Are these done via Machine Learning? I mean, is there any role of ML here?
> Yes, the Cognitive Services are all predictive ML solutions.

21. How the image processing is done?
> See 17.

22. Apart Python and Node.js does any other languages supported to build API? Java or .NET sdk ?
> There are samples of performing REST API calls to particular services in Curl, C#, Java, JavaScript, ObjC, PHP, Python and Ruby on the API Reference pages.

SPEECH

23. Does Speech API support multi Lanagugae support?
> Yes

24. Can you give an example of the speech 'intent' recognition ?
> In the phrase, "Order me a pizza" or "Find me news on tennis", Order and Find are intents, respectively.

25. How speech recognition in this is different from Google voice recognition?
> Unsure regarding Google voice recognition, but Google has a Google Cloud Speech API that is likely fairly similar to our Cognitive Services Speech API, however I do not have any side-by-side comparisons.

26. Speech Intent recognition - Does it take into account accents and demography ?
> You would likely want to use Custom Recognition API under Speech for this purpose for speech-to-text and for intent could use LUIS.

27. If we play recorded voice then also it will recognize?
> Yes.

28. How is the baseline model calculated? Is it baselined by individual to provide more accurate results or what is the sample set for baselining here?
> In the Speaker Recognition API, the speaker verification procedure, will require a user submit 3 samples of a phrase.  The phrase may be selected from a list of supported phrases in the API.

29. How do we filter out noise
> This is done in part by the algorithm, but using a clear sample from the same microphone is recommended.

30. Does speech api guesses what person was intending to speak ? like given a video , tracking lip movement to guess what is being said.? or isolate a person voice surrounding noise. 
> The speech API does not necessarily use lip-tracking data or that sort of model.  It leverages existing deep learning models with the video data and many, many features.  The Speaker Recognition API can recognize a person voice over some amount of noise and Custom Recognition API can be tuned for certain environments and might be a better choice if there's a great deal of environmental noise.

31. Do we have to train the algorithm to recognize the voice?
> No, but you must register the voice to get an id.

32. Does it follow Fuzzy logic or something neural logic algorithms?
> Deep learning algorithms are used.

33. Are the Microsoft Cognitive Services API only accessible through .NET or is it accessible through other languages such as  Python, R etc?  
> They are accessible through any language that can leverage https and REST calls.

34. How would it recognize different languages?
> Many languages are supported by Bing Speech and can be found at https://www.microsoft.com/cognitive-services/en-us/speech-api/documentation/overview#supported-languages.  Translator could be integrated as well.

35. These features are available under various mature open-source packages like OpenCV, OpenNLP etc. Same can be used to build a distributed system to expose similar APIs. What is the advantage of using Microsoft/Azure services?
> Some advantages include that very little or no programming is required, tiers for scaling are available and the free tier scales well for small to medium apps, sample code and SDKs are numerous (see https://www.microsoft.com/cognitive-services/en-us/SDK-Sample) and many scenarios can be handled well (an example list: https://github.com/Azure/bot-education/wiki/Cognitive-Services-Scenarios).
