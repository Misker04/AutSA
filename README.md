# AutSA
Autism Social Aid

## Inspiration
Autistic individuals often face criticism for their differences, making social interactions challenging and isolating. Our app, AutSA (Autistic Social Aid), provides tools to help bridge these gaps, enabling autistic individuals to connect with others and build meaningful relationships, ensuring a more fulfilling and supportive life.

## What it does
Autistic individuals often struggle with making eye contact and understanding complex social cues during interactions. AutSA addresses this by analyzing video inputs of these interactions, identifying the emotions being expressed, and simplifying the conversation into clear, formal audio that’s easier for the autistic person to comprehend. Additionally, the app suggests potential dialogue responses, helping the individual engage more confidently in social exchanges.

## How we built it
The application first takes video inputs, extracting both video frames and audio content. The video frames are analyzed using deep learning to detect the emotions being expressed, while speech-to-text recognition is applied to the audio. The resulting text is then processed by an OpenAI model to simplify it into clear, formal English dialogue. The simplified dialogue is converted back into audio for the user. Additionally, the app suggests potential conversational responses to help the user continue the interaction smoothly.

## Challenges we ran into
We faced several challenges while developing this application. First, understanding the unique behaviors and interaction difficulties of autistic individuals required extensive research. Enabling smooth, natural conversations posed another challenge, as we had to find effective ways to simplify complex social interactions. We also had to carefully select the best models for emotion recognition and text simplification to ensure accuracy and effectiveness. Additionally, debugging integration issues was tricky due to the varying dependencies between the different modules used in the project. Despite these hurdles, the project aims to help autistic individuals navigate social interactions more easily.

## Accomplishments that we're proud of
We are proud that AutSA successfully extracts both video and audio content from the provided MP4 input. The results we achieved aligned with our expectations, which is a significant milestone. We believe that this model is robust and holds great potential in supporting autistic individuals. With its broad use cases, AutSA can make a meaningful impact in facilitating smoother social interactions and improving communication for those who need it most.

## What we learned
Throughout the development of AutSA, we gained valuable insights into the behaviors and interactions of autistic individuals. We firmly believe that autism is not a disease to be cured, but rather a different way of living that requires greater understanding from society. With this perspective, we identified key use cases and developed AutSA to support autistic people in their daily interactions. Along the way, we deepened our knowledge of various AI models, learned how crucial it is to select the right one for our product, and recognized the significance of research in shaping effective solutions. Working on such an impactful project made building AutSA both enjoyable and a meaningful responsibility.

## What's next for AutSA
Currently, AutSA exists as a web application, which is useful but falls short as a daily support system for users. To enhance its functionality and accessibility, our future goal is to evolve AutSA into a wearable device. We envision it as a pair of headphones with a connected camera on top, designed to record interactions with others. The device would then process the captured content, delivering simplified dialogue through the headphones, along with possible replies for the user to choose from. Essentially, AutSA would function as regular headphones but seamlessly activates its support features when an interaction occurs, making it a more practical and integrated solution for autistic individuals.

## TechStack
### Backend:
- **Flask** (Web Framework)
- **OpenAI API** (Natural Language Processing)
- **DeepFace** (Facial Emotion Recognition)
- **MoviePy** (Video Processing)
- **SpeechRecognition** (Speech-to-Text)
- **gTTS (Google Text-to-Speech)** (Text-to-Speech Conversion)
- **OpenCV** (Computer Vision for Video Frame Analysis)

### Frontend:
- **HTML** (Markup Language)
- **CSS (Bootstrap 4.5.2)** (Styling Framework)
- **JavaScript** (Frontend Logic for Form Handling and Data Display)
