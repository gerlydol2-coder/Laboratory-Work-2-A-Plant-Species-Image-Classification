# A-Plant-Species-Image-Classification
##  Cereal Crop Image Classification Project Overview

### Brief Description of the Project
This project focuses on building an **image classification system** that can identify different **cereal crops** from images. The model is trained on a dataset of labeled cereal crop images, including finger millet, corn (maize), rye, pearl millet, rice, barley, and oats. By analyzing the visual features of each crop, the system can automatically recognize the type of cereal crop in an image.

### Purpose of the Image Classification Model
The model aims to **assist farmers, agricultural researchers, and agronomists** in quickly and accurately identifying cereal crops from photos. This supports tasks like crop monitoring, farm management, and data collection. Automating crop recognition reduces manual work, minimizes errors, and improves efficiency in agricultural practices.

## 📊 Model Training Results

<table>
<tr>
<td width="50%">

<img src="https://github.com/user-attachments/assets/761d2862-324a-4dc0-bb34-6a2c37e0a885" width="100%"/>
# Reflection Questions


</td>
<td width="50%">

## ⚙️ Training Configuration

**Epochs: 50**  
I selected 50 epochs to ensure that the model had sufficient opportunities to learn the patterns in the dataset. This allowed the model to improve its classification performance while avoiding undertraining. The accuracy increased steadily and stabilized, showing that this value was appropriate.

**Batch Size: 16**  
A batch size of 16 was chosen to balance training stability and computational efficiency. It enables smoother weight updates without excessive memory usage, resulting in stable convergence.

**Learning Rate: 0.001**  
The learning rate of 0.001 ensures gradual and controlled optimization. It prevents overshooting and supports smooth loss reduction during training.

---

### ✅ Overall Performance
These hyperparameter settings were selected to achieve high accuracy while maintaining stable and efficient training performance.

</td>
</tr>
</table>

## 🌾 Cereal Classification Dataset

| Image | Crop Name |
|:-----:|:---------:|
| <img src="https://github.com/user-attachments/assets/40980c22-87f1-471a-bcfa-e831fac7b73e" width="250" /> | Finger Millet |
| <img src="https://github.com/user-attachments/assets/e8af36f1-e96e-44cf-9267-1cc91cc4d84d" width="250" /> | Corn (Maize) |
| <img src="https://github.com/user-attachments/assets/29be8a61-9824-420d-bd6e-f3999406b290" width="250" /> | Rye |
| <img src="https://github.com/user-attachments/assets/38fd7a02-1e03-4015-b7d4-c4e53d1b92dc" width="250" /> | Pearl Millet |
| <img src="https://github.com/user-attachments/assets/34a6728a-535f-4f3b-b21d-e15989d6be60" width="250" /> | Rice |
| <img src="https://github.com/user-attachments/assets/cbbb761d-111b-4868-920d-17a7df7353ef" width="250" /> | Barley |
| <img src="https://github.com/user-attachments/assets/2c03d044-3917-47a2-ae74-5ccc9b537004" width="250" /> | Oats |
| <img src="https://github.com/user-attachments/assets/4ad8870e-ca91-44de-a48d-01918d71bf4b" width="250" /> | Sorghum |
| <img src="https://github.com/user-attachments/assets/d7cc803f-43a1-4405-939f-6cadd3a47e2e" width="250" /> | Buckwheat |
| <img src="https://github.com/user-attachments/assets/a51a5023-bee9-4ef9-b947-ed5a5e852800" width="250" /> | Foxtail Millet |
# Reflection Questions

**1. How did the number of images per class affect your model’s accuracy?**  
Classes with more images generally led to higher accuracy because the model had more examples to learn from. In contrast, classes with fewer images sometimes caused the model to misclassify, as it did not have enough data to generalize well.

**2. Which plant species were most commonly misclassified and why?**  
Crops that looked visually similar, such as finger millet and rice, also the sorghum were most commonly misclassified. This is likely because their textures and shapes share similar patterns, making it harder for the model to distinguish between them.

**3. How did changing the epochs, batch size, or learning rate affect the training results?**  
Increasing the number of epochs helped the model converge better but could lead to overfitting if too high. A larger batch size made training faster but sometimes reduced accuracy, while a smaller batch size gave more precise updates. Adjusting the learning rate affected how quickly the model learned—too high caused instability, too low made training slow.

**4. What challenges did you encounter during dataset collection and labeling?**  
Collecting enough high-quality images for each cereal crop was time-consuming. Some images were unclear, taken from unusual angles, or included multiple crops, making labeling more difficult. Ensuring consistency in image size and quality was also a challenge.

**5. If you were to improve your model, what specific changes would you make and why?**  
To improve the model, I would increase the dataset size for underrepresented crops, apply data augmentation to improve generalization, and experiment with deeper neural network architectures. Additionally, fine-tuning hyperparameters like learning rate and batch size could further enhance accuracy and reduce misclassification.

## https://teachablemachine.withgoogle.com/models/[...]

## 🌾 Cereal Crop Species Profiles

Kini nga table nagpakita sa 20 ka mga lugas (grains) nga importante sa agrikultura sa tibuok kalibutan.

| Image | Common Name | Scientific Name | Description |
| :---: | :--- | :--- | :--- |
| <img src="https://milnepublishing.geneseo.edu/app/uploads/sites/235/2020/06/image1-34-1024x768.jpeg" width="100"> | **Rice** | *Oryza sativa* | Semi-aquatic grass; staple food for over half the global population. |
| <img src="https://cdn.britannica.com/36/167236-050-BF90337E/Ears-corn.jpg" width="100"> | **Corn (Maize)** | *Zea mays* | Tall grass with large, grain-bearing ears enclosed in husks. |
| <img src="https://vlsci.com/wp-content/uploads/2022/07/melissa-askew-y4xZxzN754M-unsplash-scaled.jpg" width="100"> | **Wheat** | *Triticum aestivum* | Primary grain for bread-making due to its high gluten content. |
| <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmBrAVipw0nSCvulMh-I7xH2qZ-sv2EZ_s1Q&s" width="100"> | **Barley** | *Hordeum vulgare* | Noted for its long awns; used in brewing and animal fodder. |
| <img src="https://img.lb.wbmdstatic.com/vim/live/webmd/consumer_assets/site_images/articles/health_tools/healthy_grains_slideshow/1800ss_getty_rf_sorghum.jpg" width="100"> | **Sorghum** | *Sorghum bicolor* | Extremely drought-tolerant grain; staple in semi-arid regions. |
| <img src="https://images.unsplash.com/photo-1594145070102-3f749a0d8508" width="100"> | **Oats** | *Avena sativa* | Cool-season grain with drooping panicles; rich in beta-glucan. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Single_rye_ear.jpg/800px-Single_rye_ear.jpg" width="100"> | **Rye** | *Secale cereale* | Cold-hardy grain used for dark breads and whiskey production. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Tef_Eragrostis_tef.jpg/800px-Tef_Eragrostis_tef.jpg" width="100"> | **Teff** | *Eragrostis tef* | Tiny ancient grain from Ethiopia; gluten-free and high in iron. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1e/Pennisetum_glaucum_seeds.jpg/800px-Pennisetum_glaucum_seeds.jpg" width="100"> | **Pearl Millet** | *Pennisetum glaucum* | Produces cylindrical spikes; thrives in very poor, sandy soils. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/Ragi_In_the_field.jpg/800px-Ragi_In_the_field.jpg" width="100"> | **Finger Millet** | *Eleusine coracana* | Hand-shaped seed heads; known for exceptionally long storage life. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/07/Setaria_italica_1.JPG/800px-Setaria_italica_1.JPG" width="100"> | **Foxtail Millet**| *Setaria italica* | Bushy, tail-like spikes; one of the oldest cultivated millets. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Echinochloa_esculenta_01.jpg/800px-Echinochloa_esculenta_01.jpg" width="100"> | **Barnyard Millet**| *Echinochloa esculenta* | Fast-growing millet; used as a substitute for rice in many dishes. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Buckwheat_flowers_and_seeds.jpg/800px-Buckwheat_flowers_and_seeds.jpg" width="100"> | **Buckwheat** | *Fagopyrum esculentum* | A pseudocereal with triangular seeds; not related to wheat. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/Quinoa_plant_in_the_sun.jpg/800px-Quinoa_plant_in_the_sun.jpg" width="100"> | **Quinoa** | *Chenopodium quinoa* | High-protein pseudocereal; contains all essential amino acids. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Triticale_close-up.jpg/800px-Triticale_close-up.jpg" width="100"> | **Triticale** | *× Triticosecale* | A hybrid of wheat and rye; combines yield with hardiness. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/16/Spelt_wheat_close-up.jpg/800px-Spelt_wheat_close-up.jpg" width="100"> | **Spelt** | *Triticum spelta* | Ancient subspecies of wheat with a distinct nutty flavor. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0a/Einkorn_Wheat.jpg/800px-Einkorn_Wheat.jpg" width="100"> | **Einkorn** | *Triticum monococcum* | One of the earliest forms of cultivated wheat (founder crop). |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Emmer_wheat.jpg/800px-Emmer_wheat.jpg" width="100"> | **Emmer** | *Triticum dicoccum* | Ancient hulled wheat; a staple of Neolithic agriculture. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/41/Amaranth_seeds_plant.jpg/800px-Amaranth_seeds_plant.jpg" width="100"> | **Amaranth** | *Amaranthus caudatus* | Vibrant pseudocereal seeds; culturally significant in Mesoamerica. |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Fonio_seeds_close-up.jpg/800px-Fonio_seeds_close-up.jpg" width="100"> | **Fonio** | *Digitaria exilis* | Smallest species of millet; matures extremely fast in 6-8 weeks. |
