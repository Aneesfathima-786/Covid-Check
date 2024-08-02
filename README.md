![c44](https://github.com/user-attachments/assets/fc7a060e-fe88-4bb2-8fc8-75171d40299f)
![c44](https://github.com/user-attachments/assets/23dea7c8-e90d-444b-91fb-5388d377004c)
# Covid-Check
Inspiration

The Delta variant of COVID-19, which arrived in India in March 2021, had a devastating impact, leading to over 270,000 deaths in just three months—more than twice the number in the entire year of 2020. This variant affected individuals across all demographics. However, its consequences were disproportionately severe for certain groups. Understanding symptoms and timely diagnosis have become crucial in such scenarios. Covicheck aims to address this need by providing useful information and assisting in self-diagnosis.

What It Does

Covicheck helps users analyze their symptoms to classify them into categories such as COVID-19, common cold, or other viral infections. This tool can assist doctors and provide patients with preliminary self-diagnosis, although we strongly recommend confirming results with healthcare professionals.

How We Built It

    Data Source: We leveraged a relevant dataset from Kaggle, which includes 251 symptoms categorized as follows:
        111 symptoms for COVID-19
        70 symptoms for Viral Pneumonia
        70 symptoms for Common Cold
    Model: Initial attempts with custom models yielded limited accuracy (around 59%). We adopted the VGG16 model, which improved accuracy to 84%, and later to 97% while maintaining a manageable model size of approximately 300 MB. Integration of Twilio OTP for login was also implemented.

How It Works

    User Authentication:
        Users log in or sign up.
    Symptom Input:
        Users upload information about their symptoms and any allergies.
    Processing:
        The system processes the uploaded information and classifies the symptoms.
    Results:
        Users receive results indicating whether their symptoms align with COVID-19, common cold, or other viral infections. Detailed global statistics on COVID-19 cases and fatalities are also provided.

Challenges We Ran Into

    Model Accuracy: Achieving high accuracy was initially challenging. Building a model from scratch resulted in a low accuracy of 59%. Switching to the VGG16 model significantly improved accuracy to 97%.
    Model Size: Managing the model size for deployment on Heroku was another challenge.
    Integration: Incorporating Twilio OTP for secure user authentication was complex but successfully implemented.

Accomplishments

    High Accuracy: Achieving a 97% accuracy rate with the VGG16 model.
    Global Reach: Successfully deploying the project to be accessible to users worldwide.

What We Learned

    FastAPI: Gained expertise in using FastAPI for global type handling and creating unique solutions.
    Twilio: Learned to integrate Twilio for OTP authentication, enhancing the security of user login.

What's Next for Covicheck

    Model Improvements: Plans to refine the model based on user feedback and testing.
    Broader Accessibility: Expanding the tool's availability to a wider range of users and sectors.

Built With

    Godot: Game development
    GDScript: Scripting in Godot
    FireAlpaca: Artwork and game assets
    AI: For enemy behavior and gameplay dynamics

![c3](https://github.com/user-attachments/assets/8187af38-23b7-40b5-b223-0ac99d18cff1)

![c4](https://github.com/user-attachments/assets/dc4d96b3-5f26-46d2-b4fd-ebb49de12cc2)

![c55](https://github.com/user-attachments/assets/412ef143-2275-451e-89dc-3d68946741a1)

![c66](https://github.com/user-attachments/assets/7a16cfb5-9a89-4a70-be10-a3f4488cf12e)

![c2](https://github.com/user-attachments/assets/b47ef04d-6a78-409b-9cde-0929c3afb93c)

![c1](https://github.com/user-attachments/assets/e1d8e6f3-635f-4e78-8de0-3b39a669a779)



