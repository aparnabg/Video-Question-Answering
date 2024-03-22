# Video-Question-Answering
The Video Question Answering (VQA) System leverages advanced computer vision to interpret video content, identifying objects, actions, and spatial relationships. It integrates data from video frames and textual questions using multimodal fusion and utilizes contextual reasoning for context-aware question answering.

## Model

model diagram shown in the following figure

![alt text](https://github.com/aparnabg/Video-Question-Answering/blob/main/images/model-diagram.png?raw=true)


## Key Features

Multimodal Fusion: Integrates multiple types of data, including video frames and textual questions.
Contextual Reasoning: Utilizes contextual information to understand and answer questions more effectively.
Object Detection: Achieves an accuracy of 87% in questions related to object detection.
Single-word Response: Attains an accuracy of 83% in questions requiring single-word answers.


## Methodology

The research emphasizes the importance of multimodal fusion and contextual reasoning in Video Question Answering (VQA) systems. By reviewing various VQA methods, the study proposes a model that achieves an overall accuracy of 74%.

## Limitations

While the proposed model demonstrates promising results, it has certain limitations:

Contextual Prioritization: The model tends to focus on overarching themes of videos rather than specific objects or persons mentioned in questions. For example, when asked "Who is the man wearing a red hat?", the model may respond with "The city skyline is visible" instead of identifying the man with the red hat.
Question-Video Feature Mismatch: The model's behavior suggests a mismatch between the higher-level features extracted from the video input and the specific details required by the question input.

Conclusion
In summary, our model shows significant capabilities in object detection and single-word response tasks, achieving accuracies of 87% and 83%, respectively. However, it exhibits limitations in prioritizing relevant details based on the context of the questions, often focusing on the overall theme of the video rather than specific objects or persons of interest.

Future Work
Future refinements and developments will focus on enhancing the model's ability to prioritize relevant details and improve contextual understanding. This research contributes to the advancement of video understanding systems, paving the way for more sophisticated and human-like video question answering capabilities.
