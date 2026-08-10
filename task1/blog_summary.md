## Short Review: *Can Your Camera Tell if You’re Bored in Class?*

The article **“Can Your Camera Tell if You’re Bored in Class?”** explains how computer vision can be used to understand facial expressions using **MediaPipe** by Google. The basic idea is pretty cool because instead of a teacher asking, “Why does everyone look half asleep?”, a camera could actually try to figure it out and could also be used in analysis of student behavior. MediaPipe detects **468 3D facial landmarks**, and converts it into x, y and z co-ordinates. These points can then be used to understand how a person's face is changing.

The article mainly focuses on **three steps**. First, the facial landmarks are normalized so things like the distance from the camera or the angle of the face don't mess up the results. Second, useful features are extracted from these landmarks. This can be done using measurements, deep learning or MediaPipe's **52 blendshape scores**. Third, a machine-learning model such as Random Forest, SVM, CNN, GNN and MLP can use these features to classify expressions. I found this part interesting because there is actually a lot happening behind what looks like a simple “camera looking at your face.”

The important thing to note is that although AI can analyze faces, it still lacks the ability to understand raw human emotions and hence actions should be taken mindfully
