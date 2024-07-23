# Optimizing Mentor-student Communication Using LLM-Based Automated Labeling Information States
The appendix and a brief tutorial for the paper "Optimizing Mentor-student Communication Using LLM-Based Automated Labeling Information States"

## Overview
We provide the appendix here to show the messages that are used for testing ChatGPT-3.5 and Claude-3 and their answers to these messages.

Currently, we use an LLM to give labels to the message extracted from an instant messaging tool and change the color of a bubble chat by the output results. The function of the LLM is shown in this repository and users can modify the code by their willingness. 

## Installation

The code requires Python >= 3.8  
request => 2.31.0

if not please use:
```
pip install request
```

Recommend:
The code can also be directly used in Google Colab.

## License

LLM in message code released under the Apache License 2.0. See [LICENSE](LICENSE) for additional details.

## Citing us ٩(๑>◡<๑)۶

If you find this repository useful, please consider giving a star :star: and citation:

```
@inproceedings{Jin:2024:LS,
author = {Jin, Yuanzhe and Yu, Jiali},
title = {Optimizing Mentor-student Communication Using LLM-Based Automated Labeling Information States},
year = {2024},
isbn = {9798400706332},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3657604.3664691},
doi = {10.1145/3657604.3664691},
abstract = {As more and more countries pay attention to the quality of university education in recent years, the number of students and mentors in schools has grown rapidly. In the higher education scenario, the communication between mentors and students has long been a focal point of research. Within the communication between students and mentors, understanding information in non-face-to-face interactions often poses a challenge to communication efficiency. When using instant messaging tools for text exchanges, recipients often find themselves needing to infer the sender's intentions. With the recent rapid development of large language models (LLMs) in text comprehension capabilities, we propose to use LLMs to encode information states of the sending message, aiming to achieve a more accurate understanding of the states between mentors and students. Through experiments, we have found that using LLMs for encoding information states can assist mentors and students in better understanding responses to each other and avoid misunderstandings.},
booktitle = {Proceedings of the Eleventh ACM Conference on Learning @ Scale},
pages = {284–288},
numpages = {5},
keywords = {automated labeling, education scenario, information states, large language model, mentor-student communication},
location = {Atlanta, GA, USA},
series = {L@S '24}
}
```
