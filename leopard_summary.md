**Summary**

The PAD-UFES-20 dataset, collected in collaboration with the Dermatological and Surgical Assistance Program (PAD) at the Federal University of Espírito Santo (UFES-Brazil) in during 2018 and 2019 and there are 50 types of skin lesions that were collected during this period. It comprises 2,298 samples of six distinct types of skin lesions and can be categorized as skin cancer or skin disease: BCC, MEL and SCC are considered to be skin cancers, whereas ACK, NEV and SEK are skin diseases. Each sample includes a clinical image and up to 22 clinical features such as patient age, lesion location, Fitzpatrick skin type, and lesion diameter. The lesions encompass Basal Cell Carcinoma (BCC), Squamous Cell Carcinoma (SCC), Actinic Keratosis (ACK), Seborrheic Keratosis (SEK), Bowen’s disease (BOD), Melanoma (MEL), and Nevus (NEV). Biopsy confirmation is available for BCC, SCC, and MEL, while other diagnoses are clinically determined by dermatologists. Approximately 58% of the dataset is biopsy-proven. The images vary in size due to collection with different smartphone devices, all in .png format. 

Metadata for each lesion comprises up to 26 features, with patient and lesion references for each image/sample. The dataset collection adheres to ethical standards, approved by the university ethics committee and the Brazilian government, ensuring patient consent and privacy protection. This metadata encompasses various factors including previous cancer history, access to water, lesion diameter, and boolean indicators regarding the lesion's characteristics (e.g., does it hurt, does it bleed, etc.). Leveraging this metadata alongside masks and annotations could facilitate assessing whether image recognition results align with specific parameters.

Skin cancer can manifest in various ways with symptoms such as itching or pain, non-healing sores, scaly or red patches, shiny red bumps, or changes in the size, shape, or color of existing spots. Basal cell carcinoma (BCC) typically occurs in sun-exposed areas and presents as recurring sores, rough patches, or waxy bumps. Squamous cell carcinoma (SCC) also appears in sun-exposed regions and may include itchy or painful lesions with irregular borders. Melanoma (MEL) can develop anywhere on the body, often from existing moles, and may exhibit dark lesions, changes in mole appearance, or the growth of irregularly edged spots.

Additionally, skin conditions like Actinic Keratosis (ACK), characterized by rough, scaly patches due to sun exposure, and Seborrheic Keratosis (SEK), which presents as waxy, crusty growths. Nevus (NEV), commonly known as a mole, is a benign skin growth that varies in color, size, and shape.

Diagnosis for skin cancer involves skin biopsies, while dermatologists typically diagnose non-cancerous conditions through visual examination, with biopsies sometimes performed for confirmation.

While annotating images of skin lesions, we encountered several obstacles and made some observations. The primary challenge in annotating these images came from the diverse forms and shapes of the skin lesions. Below, we further explain the complications we encountered during the process of annotaiton of the skin lesions.

**Image clarity** 

Images within the dataset have a huge difference in quality and clarity, which makes the annotation part more difficult. Some images were very clear, and the lesions were obvious this made the prosses much easier and faster, which leads to a better result, while other images were unclear in a way that the lesions were faded with the skin due to the color match with patients’ skin color, the lesions were faded into the skin and made the annotation part hard and challenging. In some cases, the lesions were very spread and tiny even some images couldn’t be annotated, this will indeed effect the reliability of diagnostic results.


**Inconsistency in metadata completion**

Looking at the metadata made us realize lack of information and revealed inconsistencies in data completion. We do not have full information for some patients, which leads to information gaps. For example, we do not know parental history for some patients, another example is that we are missing some answers regarding whether the patient smoke or drink. Additionally we are missing answers regarding cancer history for some patients, which results in incomplete data set.


**Gender ambiguity**

Again, missing information in metadata. This time we are missing some number of patients’ gender. This lack of information would only lead to problems for accurate patient description and analysis and wrong and invalid results. Lack of gender identity may hinder the interpretation of some dermatological conditions because sex-specific factors do indeed influence disease presentation and progression.


**Loss of detail** 

During the annotation of patient images from the PAD-UFES-20 dataset, an interesting observation was made regarding the impact of annotation on image details, especially in marginal lesions. When reviewing raw images, edges appear clear and well-defined, allowing easy identification of lesion boundaries. The edges have natural shapes and curves, reflecting the organic nature of the skin lesion. 
However, after marking the lesions during annotation, a notable transformation occurs. Edges that were once clear and nuanced become distinctly straight and no longer have the shape or curvature they once had in the raw image. This phenomenon suggests that the act of annotation can unintentionally distort the natural characteristics of the lesion, leading to loss of detail and fidelity of the annotated image.


https://www.sundhed.dk/borger/patienthaandbogen/kraeft/sygdomme/hud-kraeft/hudkraeft-basalcelle-og-pladeepithelkraeft/
https://www.sundhed.dk/borger/patienthaandbogen/hud/sygdomme/modermaerker-pigmenteret-udslaet/modermaerkekraeft-malignt-melanom/

With PAD-UFES-20 dataset we can combine dermatology and modern technologies to enhance, provide more accurate and faster diagnosis of skin cancer. This is done by feeding machine learning algorithms the data from the set, so we can train the model to spot skin cancer, which could help detect skin cancer early in. With all the diverse images and information in this dataset, the algorithms can get really good at telling the difference between various skin lesions. The variety of skin conditions covered in the dataset gives these algorithms knowledge as broad as the variance in skin lesions, making them adaptable and efficient. This adaptability is important when making tools for healthcare, since all humand come in different shapes and sizes. Additionally, dealing with obstacles like making sure the pictures are clear, annotation are consistent and precise, will help the algortihm become smarter and more accurate. Not only are the algorithms supporting healthcare workers, but they are also helping the indivual person getting checked out for skin cancer. To sum up, by going beyond combning machine learning technology with dermatology, we can support healthcare systems and make them more efficient, which could minimise the workload for healthcare workers and provide better helpt for patients. 









