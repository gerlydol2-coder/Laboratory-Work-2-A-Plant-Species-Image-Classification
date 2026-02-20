# Laboratory-Work-2-Plant-Species-Image-Classification
##  A. Project Overview

### Brief Description of the Project
This project focuses on building an **image classification system** that can identify different **cereal crops** from images. The model is trained on a dataset of labeled cereal crop images, including finger millet, corn (maize), rye, pearl millet, rice, barley, and oats. By analyzing the visual features of each crop, the system can automatically recognize the type of cereal crop in an image.

### Purpose of the Image Classification Model
The model aims to **assist farmers, agricultural researchers, and agronomists** in quickly and accurately identifying cereal crops from photos. This supports tasks like crop monitoring, farm management, and data collection. Automating crop recognition reduces manual work, minimizes errors, and improves efficiency in agricultural practices.
## B. Plant Species Section

### 🌾 Cereal Crop Species Profiles

| Image | Common Name | Scientific Name | Description |
| :---: | :--- | :--- | :--- |
| <img src="https://milnepublishing.geneseo.edu/app/uploads/sites/235/2020/06/image1-34-1024x768.jpeg" width="100"> | **Rice** | *Oryza sativa* | Semi-aquatic grass; staple food for half the world. |
| <img src="https://cdn.britannica.com/36/167236-050-BF90337E/Ears-corn.jpg" width="100"> | **Corn (Maize)** | *Zea mays* | Tall grass with large, grain-bearing ears in husks. |
| <img src="https://blog.suvie.com/wp-content/uploads/2021/08/wheat-2526829_1920-1360x907.jpg" width="100"> | **Wheat** | *Triticum aestivum* | The primary grain used for bread and gluten products. |
| <img src="https://blog.suvie.com/wp-content/uploads/2021/08/wheat-2526829_1920-1360x907.jpg" width="100"> | **Einkorn** | *Triticum monococcum* | Ancient wheat with a simple genetic structure. |
| <img src="https://img.freepik.com/premium-photo/emmer-wheat-with-hulled-grains-robust-spikes_1079150-77348.jpg" width="100"> | **Emmer** | *Triticum dicoccum* | Early staple wheat; used in specialty gourmet dishes. |
| <img src="https://sovereignfoods.com.au/cdn/shop/products/Spelt-Grain-Biodynamic-20kg-Burrum-Biodynamics-Sovereign-Foods-1665628161_1100x.jpg" width="100"> | **Spelt** | *Triticum spelta* | Ancient wheat subspecies with a nutty flavor. |
| <img src="https://images.squarespace-cdn.com/content/v1/60f6b8e171d5c44bc51ef29a/1630509038314-W4BK85LZPP75NWANBBP3/Triticale+cereal+from+Seedtech.JPG" width="100"> | **Triticale** | *× Triticosecale* | Hybrid of wheat and rye; combines yield and hardiness. |
| <img src="https://i0.wp.com/www.smartfood.org/wp-content/uploads/2021/01/FingerMilletCropTrust.jpg?fit=1230%2C833&ssl=1" width="100"> | **Finger Millet** | *Eleusine coracana* | High-calcium grain with hand-shaped seed heads. |
| <img src="https://naro.go.ug/wp-content/uploads/2023/11/pearlmillet-900x600.jpg" width="100"> | **Pearl Millet** | *Pennisetum glaucum* | Drought-tolerant grain with cylindrical spikes. |
| <img src="https://5.imimg.com/data5/SE/AX/EM/SELLER-73880490/thenai-korralu-kangni-thina-navane-setaria-italica-.jpg" width="100"> | **Foxtail Millet** | *Setaria italica* | Ancient East Asian crop with tail-like spikes. |
| <img src="https://tassieseeds.com.au/wp-content/uploads/2018/02/IMG_2669.jpeg" width="100"> | **Barnyard Millet** | *Echinochloa esculenta* | Fast-growing millet; a popular rice substitute. |
| <img src="https://www.coyograinmachine.com/uploads/202324479/fonio-millet-quinoa-scouring-destonerc45ccdd8-dae6-4a60-af8b-4baa15d43b64.jpg" width="100"> | **Fonio** | *Digitaria exilis* | Smallest species of millet; matures in 6-8 weeks. |
| <img src="https://img.lb.wbmdstatic.com/vim/live/webmd/consumer_assets/site_images/articles/health_tools/healthy_grains_slideshow/1800ss_getty_rf_sorghum.jpg" width="100"> | **Sorghum** | *Sorghum bicolor* | Drought-tolerant grain; staple in semi-arid regions. |
| <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmBrAVipw0nSCvulMh-I7xH2qZ-sv2EZ_s1Q&s" width="100"> | **Barley** | *Hordeum vulgare* | Noted for long awns; used in brewing and fodder. |
| <img src="https://garrettseed.com/wp-content/uploads/2020/08/Rye-Grain.jpg" width="100"> | **Rye** | *Secale cereale* | Cold-hardy grain used for dark breads and spirits. |
| <img src="https://cdn.britannica.com/87/187187-050-31B10B3D/oats-harvest.jpg" width="100"> | **Oats** | *Avena sativa* | Cool-season grain; high in heart-healthy fiber. |
| <img src="https://www.adaptiveseeds.com/wp-content/uploads/2014/12/teff-al-white-3.jpg" width="100"> | **Teff** | *Eragrostis tef* | Tiny, iron-rich Ethiopian ancient grain. |
| <img src="https://wpcdn.web.wsu.edu/wp-labs/uploads/sites/2703/2023/08/IMG_20190812_101453343_HDR-1-scaled.jpg" width="100"> | **Quinoa** | *Chenopodium quinoa* | High-protein Andean seed; naturally gluten-free. |
| <img src="https://www.johnstonseed.com/wp-content/uploads/2017/08/buckwheat-4424194_1280.jpg" width="100"> | **Buckwheat** | *Fagopyrum esculentum* | Gluten-free seed with a unique triangular shape. |
| <img src="https://as1.ftcdn.net/v2/jpg/01/82/39/40/1000_F_182394013_LzaD94QJMmHgTKTP1zpITxMFyBjJGIZS.jpg" width="100"> | **Amaranth** | *Amaranthus caudatus* | Vibrant ancient seed crop; highly nutritious pseudocereal. |

## C. 📊 Model Training Details

<table>
<tr>
<td width="30%">
<img src="https://github.com/user-attachments/assets/6bf9aec2-c6cc-4292-996e-26c97c64c287" width="100%" alt="Teachable Machine Settings" />
</td>
<td width="50%">

### ⚙️ Why I Chose These Values

* **Epochs: 50** I selected 50 epochs to ensure the model had sufficient opportunities to learn patterns without overfitting. This allowed the accuracy to stabilize and reach its peak performance.
* **Batch Size: 16** A batch size of 16 was chosen to balance training stability and computational efficiency. It allows for smoother weight updates and prevents memory issues during the training process.
* **Learning Rate: 0.001** This rate ensures gradual and controlled optimization. It prevents the model from "overshooting" the optimal solution, supporting a smooth reduction in loss.

</td>
</tr>
</table>

---

## D. 📈 Model Evaluation

To verify the effectiveness of the training, I monitored the accuracy and loss curves. These graphs indicate how well the model learned over time and whether it can generalize to new data.

<img src="https://github.com/user-attachments/assets/761d2862-324a-4dc0-bb34-6a2c37e0a885" width="90%" height="110" alt="Accuracy and Loss Graphs" />

### 🔍 Key Metrics Observed:eight

* **Accuracy Curve:** The blue line represents the training accuracy, while the orange line shows the test accuracy. Both lines converged toward **100%**, indicating that the model successfully learned the unique characteristics of each fruit class.
* **Loss Curve:** The loss significantly dropped during the first 10 epochs and stabilized near zero. This confirms that the model's predictions became increasingly precise as training progressed.
* **Generalization:** Since the test accuracy closely followed the training accuracy, it shows that the model is robust and not overfitted to just the training images.

---
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


---

