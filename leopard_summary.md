**Summary**

The PAD-UFES-20 dataset, collected in collaboration with the Dermatological and Surgical Assistance Program (PAD) at the Federal University of Espírito Santo (UFES-Brazil) in during 2018 and 2019 and there are 50 types of skin lesions that were collected during this period. It comprises 2,298 samples of six distinct types of skin lesions and can be categorized as skin cancer or skin disease: BCC, MEL and SCC are considered to be skin cancers, whereas ACK, NEV and SEK are skin diseases. Each sample includes a clinical image and up to 22 clinical features such as patient age, lesion location, Fitzpatrick skin type, and lesion diameter. The lesions encompass Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). Biopsy confirmation is available for BCC, SCC, and MEL, while other diagnoses are clinically determined by dermatologists. Approximately 58% of the dataset is biopsy-proven. The images vary in size due to collection with different smartphone devices, all in .png format. 

Metadata for each lesion comprises up to 26 features, with patient and lesion references for each image/sample. The dataset collection adheres to ethical standards, approved by the university ethics committee and the Brazilian government, ensuring patient consent and privacy protection. This metadata encompasses various factors including previous cancer history, access to water, lesion diameter, and boolean indicators regarding the lesion's characteristics (e.g., does it hurt, does it bleed, etc.). Leveraging this metadata alongside masks and annotations could facilitate assessing whether image recognition results align with specific parameters.

Skin cancer can manifest in various ways with symptoms such as itching or pain, non-healing sores, scaly or red patches, shiny red bumps, or changes in the size, shape, or color of existing spots. Basal cell carcinoma (BCC) typically occurs in sun-exposed areas and presents as recurring sores, rough patches, or waxy bumps. Squamous cell carcinoma (SCC) also appears in sun-exposed regions and may include itchy or painful lesions with irregular borders. Melanoma (MEL) can develop anywhere on the body, often from existing moles, and may exhibit dark lesions, changes in mole appearance, or the growth of irregularly edged spots.

Additionally, skin conditions like Actinic Keratosis (ACK), characterized by rough, scaly patches due to sun exposure, and Seborrheic Keratosis (SEK), which presents as waxy, crusty growths. Nevus (NEV), commonly known as a mole, is a benign skin growth that varies in color, size, and shape.

Diagnosis for skin cancer involves skin biopsies, while dermatologists typically diagnose non-cancerous conditions through visual examination, with biopsies sometimes performed for confirmation.

While annotating images of skin lesions, we encountered several obstacles and made some observations. The primary challenge in annotating these images came from the diverse forms and shapes of the skin lesions. Below, we further explain the complications we encountered during the process of annotaiton of the skin lesions.

**Image clarity** 

Images within the dataset have a difference in quality, which makes the annotation harder. Some images are very clear, and the lesions are obvious, these images can easily and faster be annotated. While other images are unclear and faded due to color matching, in a way that the lesions fade into the skin because of the skin color, which makes the prosses of annotating more challenging and end with non-reliability results.

**Inconsistency in metadata completion**

Looking at metadata made us realize missing information in some cases. We do not have a complete information, which leads to information gaps. For exaple we are missing some answers regarding smoke or drink in some cases. Additionally, we are missing parent background information in some cases. This results an incomplete dataset and can lead to wrong or nonvalid results.

**Gender ambiguity**

Again, another lack of information. We are missing information in some patient records. Which is patient’s gender, this causes problems for accurate patient description and analysis. Lack of gender identity will indeed hinder the interpretation some dermatological conditions, because sex-specific factors may influence disease presentation and progression. 





<<<<<<< HEAD

**Loss of details** 
=======
**Image edge distortion in caption** 
>>>>>>> parent of 455ad4e (changes added to annotation comments and summary)

During the annotation of patient images from the PAD-UFES-20 dataset, an interesting observation was made regarding the impact of annotation on image details, especially in marginal lesions. When reviewing raw images, edges appear clear and well-defined, allowing easy identification of lesion boundaries. The edges have natural shapes and curves, reflecting the organic nature of the skin lesion. 
However, after marking the lesions during annotation, a notable transformation occurs. Edges that were once clear and nuanced become distinctly straight and no longer have the shape or curvature they once had in the raw image. This phenomenon suggests that the act of annotation can unintentionally distort the natural characteristics of the lesion, leading to loss of detail and fidelity of the annotated image.

https://www.sundhed.dk/borger/patienthaandbogen/kraeft/sygdomme/hud-kraeft/hudkraeft-basalcelle-og-pladeepithelkraeft/
https://www.sundhed.dk/borger/patienthaandbogen/hud/sygdomme/modermaerker-pigmenteret-udslaet/modermaerkekraeft-malignt-melanom/


As a viable pathway for improving the diagnosis of skin cancer, the PAD-UFES-20 dataset emerges as a catalyst for the fusion of dermatology and contemporary technologies. A possible advance in early diagnosis is presented by the use of this dataset to train machine learning algorithms to identify skin cancer. The variety of photos and data in the dataset gives these algorithms a deep comprehension of different types of skin lesions, which promotes flexibility and effectiveness that are essential for handling each person's distinct characteristics. Considering the inherent variability in human shapes and sizes, this versatility proved invaluable in the healthcare industry. The algorithm's intelligence is increased by overcoming obstacles like guaranteeing image clarity and accurate annotations, which makes it a useful tool for healthcare professionals. Beyond aiding experts, these algorithms enable people requesting assessments for skin cancer, promoting a pro-active approach to healthcare.To put it briefly, machine learning in dermatology streamlines diagnostic processes and relieves the workload of medical personnel. In order to better help patients in their quest for prompt diagnosis and treatment of skin cancer, technology and healthcare professionals are working together to improve the efficacy of diagnostic instruments. A new age of accuracy and efficiency in the diagnosis of skin cancer has been ushered in by the collaboration of dermatology and machine learning.











