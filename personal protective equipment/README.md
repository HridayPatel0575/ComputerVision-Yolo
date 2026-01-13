# 🚧 PPE Detection for Construction Site Safety

A computer vision project to **detect Personal Protective Equipment (PPE)** and safety compliance violations (like missing helmets, masks, vests, etc.) on construction site videos or images using **YOLOv8**.

This system can be used for:
- Safety compliance monitoring
- Real-time alerts for PPE violations
- Automating site safety audits
- Integration with CCTV or surveillance systems

## 📦 Dataset

We use the **Construction Site Safety Dataset** from **Roboflow Universe** — a multi-class object detection dataset annotated in YOLO format.  
🔗 **Dataset Link:** https://universe.roboflow.com/roboflow-universe-projects/construction-site-safety/dataset/30# :contentReference[oaicite:0]{index=0}

### 🧠 Classes in the dataset
The dataset includes the following objects (25+ classes) such as:
- PPE items: Hardhat, Gloves, Mask, Safety Vest, Safety Cone, etc.
- Non-PPE violations: NO-Hardhat, NO-Mask, NO-Safety Vest, etc.
- Vehicles & machines: Excavator, Bus, Truck, Wheel Loader, etc.
- People: Person  
*(Full list available in dataset page)* :contentReference[oaicite:1]{index=1}


