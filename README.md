# 🌾 Laboratory Work 2: Plant Species Image Classification


---

# 📌 A. Project Overview


🌱 Brief Description of the Project

This project develops an image classification system that can automatically identify different cereal crops from images. The model is trained on a labeled dataset containing crops such as Finger Millet, Corn (Maize), Rye, Pearl Millet, Rice, Barley, and Oats. By learning the unique visual features of each crop, the system can accurately recognize and classify cereal crops in new images, offering a practical tool for agricultural monitoring and management.

## 🎯 Purpose of the Image Classification Model

The model aims to **assist farmers, agricultural researchers, and agronomists** in quickly and accurately identifying cereal crops from photos.

This supports:

- Crop monitoring  
- Farm management  
- Data collection  

Automating crop recognition reduces manual work, minimizes errors, and improves efficiency in agricultural practices.

---

# 🌾 B. Plant Species Section

## 🌾 Cereal Crop Species Profiles

| Image | Common Name | Scientific Name | Description |
|:---:|:---|:---|:---|
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

---

# 📊 C. Model Training Details

<p align="center">
  <img src="https://github.com/user-attachments/assets/6bf9aec2-c6cc-4292-996e-26c97c64c287" width="450"/>
</p>

## ⚙️ Why I Chose These Values

- **Epochs: 50**  
  I selected 50 epochs to ensure the model had sufficient opportunities to learn patterns without overfitting. This allowed the accuracy to stabilize and reach its peak performance.

- **Batch Size: 16**  
  A batch size of 16 was chosen to balance training stability and computational efficiency. It allows smoother weight updates and prevents memory issues during training.

- **Learning Rate: 0.001**  
  This rate ensures gradual and controlled optimization. It prevents the model from overshooting the optimal solution and supports smooth reduction in loss.

---

# 📈 D. Model Evaluation

To evaluate the effectiveness of my model, I monitored the accuracy and loss curves during training.

These graphs help me understand:

- How well the model learned from training data  
- How well it generalizes to unseen data  

---

## 1️⃣ Training Accuracy per Epoch

<p align="center">
  <img src="https://github.com/user-attachments/assets/440279ca-a122-430f-955c-bd6cfa498e23" width="500"/>
</p>

The training accuracy rapidly increased and reached nearly **100% (1.0)**, indicating that my model successfully learned the patterns from the training dataset.

However, high training accuracy alone does not guarantee good performance on new data, so I also analyzed the validation accuracy.

---

## 2️⃣ Validation Accuracy per Epoch

<p align="center">
  <img src="https://github.com/user-attachments/assets/3b98c72f-126d-44c1-8d77-e856ce87f6ab" width="500"/>
</p>

The validation accuracy reached approximately **98–99%**, very close to the training accuracy.

This tells me that my model generalizes well to unseen data and shows minimal signs of overfitting.

---

## 3️⃣ Training Loss per Epoch

<p align="center">
  <img src="https://github.com/user-attachments/assets/87a5af59-1445-43c5-99dd-3194c086b015" width="500"/>
</p>

The training loss started high and quickly decreased toward zero. This means the model progressively minimized prediction errors during learning.

---

## 4️⃣ Validation Loss per Epoch

<p align="center">
  <img src="https://github.com/user-attachments/assets/55feda65-fedd-4075-b3b9-5fdbf3188af2" width="500"/>
</p>

The validation loss also decreased significantly and remained low overall, confirming consistent performance on unseen data.

---

# ✅ Overall Model Performance Summary

- Training Accuracy: ~100%  
- Validation Accuracy: ~98–99%  
- Training Loss: Near 0  
- Validation Loss: Low and stable  
- Overfitting: Minimal  
- Generalization Ability: Strong  

---

# 📌 Final Conclusion

Based on the accuracy and loss curves, I conclude that my model learned effectively and demonstrates strong generalization capability. The high accuracy and low loss values indicate that the model is reliable and suitable for classification tasks.

---

# 🔍 Key Metrics Observed

- **Accuracy Curve:** Training and test accuracy both converged toward 100%, indicating strong learning performance.
- **Loss Curve:** Loss significantly dropped during the first 10 epochs and stabilized near zero.
- **Generalization:** Test accuracy closely followed training accuracy, showing the model is robust and not overfitted.

---

# 🧠 Reflection Questions

### 1. How did the number of images per class affect accuracy?

Classes with more images led to higher accuracy because the model had more examples to learn from. Classes with fewer images sometimes caused misclassification due to limited generalization.

---

### 2. Which plant species were most commonly misclassified and why?

Visually similar crops such as finger millet, rice, and sorghum were most commonly misclassified due to similar textures and shapes.

---

### 3. How did changing the epochs, batch size, or learning rate affect results?

Increasing epochs improved convergence but risked overfitting. Larger batch sizes trained faster but sometimes reduced accuracy. Learning rate adjustments affected stability and convergence speed.

---

### 4. What challenges did you encounter during dataset collection?

Collecting high-quality images was time-consuming. Some images had unclear angles or multiple crops, making labeling more difficult.

---

### 5. If you were to improve your model, what would you change?

I would increase dataset size, apply data augmentation, experiment with deeper architectures, and fine-tune hyperparameters.

---

# 🔗 Model Link

### https://drive.google.com/file/d/1bQVZBT3QNkr6cpWio0WOiW-EA1NZ4_eP/view?usp=sharing

---
