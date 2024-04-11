# SOS-Hub

Link- https://soshub.us/

SOS-Hub is an AI-powered emergency response platform that leverages the power of computer vision and natural language processing to assist first responders and emergency services.

SOS-Hub is a web application built using a combination of technologies. The frontend is developed using React, the backend is powered by Flask and integrated seamlessly with our AI models.

For the AI component, we are using the capabilities of the OpenAI API and the Fireworks AI platform. The firellava-13b model from Fireworks is being used for the initial image analysis, providing a detailed description of the emergency situation. This output is then processed by the llama-v2-70b-chat model, which structures the information into a concise JSON format, compares it with user input, and generates tailored recommendations.

To maintain data continuity and optimize storage, we've incorporated Neurelo into the SOS-Hub framework. By using Neurelo's API, we're able to securely house analysis outcomes and insights within the Neurelo database, thereby eliminating the intricacies associated with database programming and enhancing developer productivity.
