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

<img src="https://github.com/user-attachments/assets/c8ed46a8-2712-4efd-96cd-50a633f513c8" width="100%"/>
# Reflection Questions

**1. How did the number of images per class affect your model’s accuracy?**  
Classes with more images generally led to higher accuracy because the model had more examples to learn from. In contrast, classes with fewer images sometimes caused the model to misclassify, as it did not have enough data to generalize well.

**2. Which plant species were most commonly misclassified and why?**  
Crops that looked visually similar, such as finger millet and pearl millet, were most commonly misclassified. This is likely because their textures and shapes share similar patterns, making it harder for the model to distinguish between them.

**3. How did changing the epochs, batch size, or learning rate affect the training results?**  
Increasing the number of epochs helped the model converge better but could lead to overfitting if too high. A larger batch size made training faster but sometimes reduced accuracy, while a smaller batch size gave more precise updates. Adjusting the learning rate affected how quickly the model learned—too high caused instability, too low made training slow.

**4. What challenges did you encounter during dataset collection and labeling?**  
Collecting enough high-quality images for each cereal crop was time-consuming. Some images were unclear, taken from unusual angles, or included multiple crops, making labeling more difficult. Ensuring consistency in image size and quality was also a challenge.

**5. If you were to improve your model, what specific changes would you make and why?**  
To improve the model, I would increase the dataset size for underrepresented crops, apply data augmentation to improve generalization, and experiment with deeper neural network architectures. Additionally, fine-tuning hyperparameters like learning rate and batch size could further enhance accuracy and reduce misclassification.

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

<img width="605" height="766" alt="image" src="https://github.com/user-attachments/assets/761d2862-324a-4dc0-bb34-6a2c37e0a885" />
## https://teachablemachine.withgoogle.com/models/[...]

# Plant Profile: Rice

![Rice Plant](https://milnepublishing.geneseo.edu/app/uploads/sites/235/2020/06/image1-34-1024x768.jpeg)

- **Common Name:** Rice / Asian Rice / Paddy
- **Scientific Name:** *Oryza sativa*
- **Description:** *Oryza sativa* is an annual, semi-aquatic grass in the family **Poaceae**. It serves as a primary staple food for over half the global population. The plant features long, flat leaves and a branching flowering head called a **panicle**. It is specifically adapted to flooded environments through internal air channels (**aerenchyma**) that facilitate oxygen transport to submerged roots.

 # Plant Profile: Corn (Maize)

![Ears of Corn](https://cdn.britannica.com/36/167236-050-BF90337E/Ears-corn.jpg)

- **Common Name:** Corn / Maize
- **Scientific Name:** *Zea mays*
- **Description:** *Zea mays* is a tall, annual cereal grass in the family **Poaceae**. Domesticated in Mesoamerica, it is distinguished by its large, grain-bearing ears enclosed in husks. Unlike most grasses, it is monoecious, featuring a pollen-producing tassel and silk-covered ears. It is a fundamental global staple used for food, livestock feed, and industrial products like ethanol and bioplastics.
- # Plant Profile: Barley

![Barley](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmBrAVipw0nSCvulMh-I7xH2qZ-sv2EZ_s1Q&s)

- **Common Name:** Barley
- **Scientific Name:** *Hordeum vulgare*
- **Description:** *Hordeum vulgare* is a versatile annual cereal grain in the family **Poaceae**. Known for its prominent awns (bristles) and tolerance to poor soil and cold climates, it is a staple crop used extensively in the brewing industry, for animal fodder, and as a nutritious human food source.
