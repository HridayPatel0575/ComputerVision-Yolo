# 🚧 PPE Detection for Construction Site Safety

A computer vision project to **detect Personal Protective Equipment (PPE)** and safety compliance violations (like missing helmets, masks, vests, etc.) on construction site videos or images using **YOLOv8**.

This system can be used for:
- Safety compliance monitoring
- Real-time alerts for PPE violations
- Automating site safety audits
- Integration with CCTV or surveillance systems

## 📦 Dataset

We use the **Construction Site Safety Dataset** from **Roboflow Universe** — a multi-class object detection dataset annotated in YOLO format.  
🔗 **Dataset Link:** https://universe.roboflow.com/roboflow-universe-projects/construction-site-safety/dataset/30# 

## 📥 Model Weights

Download the trained model weights here:  
🔗 **Weights (Google Drive):** https://drive.google.com/drive/folders/1vtGSUjSSkW50jfBnSo7v-mGF-i61PMNQ?usp=sharing

Place the `best.pt` file inside your project under:
runs/detect/train/weights/best.pt


---

## 🧠 Classes in the dataset

The dataset includes the following object categories:

- Excavator  
- Gloves  
- Hardhat  
- Ladder  
- Mask  
- NO-Hardhat  
- NO-Mask  
- NO-Safety Vest  
- Person  
- SUV  
- Safety Cone  
- Safety Vest  
- Bus  
- Dump Truck  
- Fire Hydrant  
- Machinery  
- Mini-van  
- Sedan  
- Semi  
- Trailer  
- Truck and Trailer  
- Truck  
- Van  
- Vehicle  
- Wheel Loader  

*(Full list available on the dataset page)*
