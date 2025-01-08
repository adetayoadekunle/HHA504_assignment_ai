# HHA504_assignment_ai
## I used a famous quote from the movie "Predator" where Arnold Schwarzenegger says "Get to the Chopper" and included a poster with the quote as well.

## Work with Pre-trained Speech Models
- **GCP Speech-to-Text:**
**Used pre-configured notebook to interact with GCP Speech to Text, uploaded sample file, and transcribed results with the model: "this is a chopper"**
![Vertex AI Workbench User-Managed Notebook](https://github.com/user-attachments/assets/322fa512-a8e6-4986-ac48-7ddca59e3985)
![GCP Speech-to-Text part 1](https://github.com/user-attachments/assets/1d172a8e-b029-4832-bcd9-6077313318fc)
![GCP Speech-to-Text part 2](https://github.com/user-attachments/assets/e06298bd-a972-4364-9bb7-875e2d24fc3f)
![GCP Speech-to-Text part 3](https://github.com/user-attachments/assets/71832dea-aa20-46bc-9d79-7a24b8694787)

## Work with Pre-trained Vision Models
**Uploaded an image, used GCP Vision API model to detect objects and text in the image**
- **GCP Vision API:**
![GCP Vision API part 1](https://github.com/user-attachments/assets/930c87f3-01de-44f8-8d21-4e4b3224078a)
![GCP Vision API part 2](https://github.com/user-attachments/assets/dff838b6-60db-4290-96b2-c7082169aa00)
![GCP Vision API part 3](https://github.com/user-attachments/assets/9f7705e3-c697-422c-9eb6-23c228cf46b2)

- **Azure AI Vision:**
- **Used Pre-trained model to detect objects and text in the image**
![Azure Computer Vision Resource](https://github.com/user-attachments/assets/fd4a32e5-a45e-4ad4-af3e-ae0010c0933a)
![Azure AI Vision Part 1](https://github.com/user-attachments/assets/d6282601-f4d1-46ed-837d-aedb539657dc)
![Azure AI Vision Part 2](https://github.com/user-attachments/assets/fb16c073-0987-4bba-ae91-d90ea4a076c6)
![Azure AI Vision Part 3](https://github.com/user-attachments/assets/21547aa8-fca4-4ae2-a519-1dad359eebe8)

## Comparison of the results from GCP and Azure
When looking at the results of the Pre-trained models, GCP Vision API and Azure AI Vision did well in different aspects. In terms of the detected objects, Azure AI Vision produced more descriptive results because it included the aircraft, person, and poster. GCP Vision API did a good job as well but only included the helicopter and person. In terms of the detected text, GCP Vision API did a better job printing the text from the image ("GET TO DA CHOPPA") than the Azure AI Vision ("GET TO DA ........... T"). Also,  setting up the Pre-trained model with GCP Vision API and the GCP Speech-to-Text Pre-trained Speech was easier and faster than working with Azure AI Vision. Other reasons for this include GCP's simplicity which provides a better experience with working with their user interface. The speech-to-text GCP model produced "this is a chopper" instead of "get to da choppa" but the results were close.
