The PAD-UFES-20 dataset, collected in collaboration with the Dermatological and Surgical Assistance Program (PAD) at the Federal University of Espírito Santo (UFES-Brazil) in during 2018 and 2019 and there are 50 types of skin lesions that were collected during this period. It comprises 2,298 samples of six distinct types of skin lesions and can be categorized as skin cancer or skin disease: BCC, MEL and SCC are considered to be skin cancers, whereas ACK, NEV and SEK are skin diseases. Each sample includes a clinical image and up to 22 clinical features such as patient age, lesion location, Fitzpatrick skin type, and lesion diameter. The lesions encompass Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). Biopsy confirmation is available for BCC, SCC, and MEL, while other diagnoses are clinically determined by dermatologists. Approximately 58% of the dataset is biopsy-proven. The images vary in size due to collection with different smartphone devices, all in .png format. 

Metadata for each lesion comprises up to 26 features, with patient and lesion references for each image/sample. The dataset collection adheres to ethical standards, approved by the university ethics committee and the Brazilian government, ensuring patient consent and privacy protection. This metadata encompasses various factors including previous cancer history, access to water, lesion diameter, and boolean indicators regarding the lesion's characteristics (e.g., does it hurt, does it bleed, etc.). Leveraging this metadata alongside masks and annotations could facilitate assessing whether image recognition results align with specific parameters.

Skin cancer can manifest in various ways with symptoms such as itching or pain, non-healing sores, scaly or red patches, shiny red bumps, or changes in the size, shape, or color of existing spots. Basal cell carcinoma (BCC) typically occurs in sun-exposed areas and presents as recurring sores, rough patches, or waxy bumps. Squamous cell carcinoma (SCC) also appears in sun-exposed regions and may include itchy or painful lesions with irregular borders. Melanoma (MEL) can develop anywhere on the body, often from existing moles, and may exhibit dark lesions, changes in mole appearance, or the growth of irregularly edged spots.

Additionally, skin conditions like Actinic Keratosis (ACK), characterized by rough, scaly patches due to sun exposure, and Seborrheic Keratosis (SEK), which presents as waxy, crusty growths. Nevus (NEV), commonly known as a mole, is a benign skin growth that varies in color, size, and shape.

Diagnosis for skin cancer involves skin biopsies, while dermatologists typically diagnose non-cancerous conditions through visual examination, with biopsies sometimes performed for confirmation.

While annotating images of skin lesions, we encountered several obstacles and made some observations. The primary challenge in annotating these images came from the diverse forms and shapes of the skin lesions. Below, we further explain the complications we encountered during the process of annotaiton of the skin lesions.

**Image clarity** 

Images within the dataset have varying levels of clarity, which affects ease of annotation. Some images show clear and distinguishable lesions, facilitating a simple annotation process. These images provide valuable information about lesion characteristics and facilitate accurate diagnosis. However, a subset of images presents challenges due to subtle and scattered features. Although visible, these features are often blurred and scattered in the surrounding skin, making accurate annotation more difficult. Additionally, some images lack clear lesion delineation, complicating the annotation process and potentially affecting the reliability of diagnostic results.

**Inconsistency in metadata completion**

Analysis of the metadata accompanying patient images revealed inconsistencies in data completion. Some patients do not meet all requirements, leading to information gaps. For example, questions regarding cigarette or alcohol use may remain unanswered in some cases, thereby limiting the completeness of the patient record. Additionally, important background information, such as parental history, may be omitted, resulting in incomplete data sets. These inconsistencies highlight the importance of thorough data collection protocols to ensure complete patient records and robust data set integrity.

**Gender ambiguity**

One notable result was the presence of gender ambiguity in some patient records. In these cases, the patient's gender is not determined, which poses problems for accurate patient description and analysis. Lack of gender identity may hinder the interpretation of some dermatological conditions because sex-specific factors may influence disease presentation and progression. Eliminating gender ambiguity is essential to improve the clinical relevance and applicability of dermatological research results.

**Image edge distortion in caption** 

During the annotation of patient images from the PAD-UFES-20 dataset, an interesting observation was made regarding the impact of annotation on image details, especially in marginal lesions. When reviewing raw images, edges appear clear and well-defined, allowing easy identification of lesion boundaries. The edges have natural shapes and curves, reflecting the organic nature of the skin lesion. 
However, after marking the lesions during annotation, a notable transformation occurs. Edges that were once clear and nuanced become distinctly straight and no longer have the shape or curvature they once had in the raw image. This phenomenon suggests that the act of annotation can unintentionally distort the natural characteristics of the lesion, leading to loss of detail and fidelity of the annotated image.



https://www.sundhed.dk/borger/patienthaandbogen/kraeft/sygdomme/hud-kraeft/hudkraeft-basalcelle-og-pladeepithelkraeft/
https://www.sundhed.dk/borger/patienthaandbogen/hud/sygdomme/modermaerker-pigmenteret-udslaet/modermaerkekraeft-malignt-melanom/

