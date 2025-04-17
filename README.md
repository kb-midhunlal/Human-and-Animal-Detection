Designed and deployed an edge-based object detection system capable of distinguishing humans and animals in real-time, ideal for surveillance and wildlife monitoring.

Key Contributions:

📷 Custom Dataset: Collected diverse images of humans and animals in varied conditions.

🔍 Annotation & Preprocessing:

Annotated images using Roboflow and Imagesense AI.

Applied data augmentation (flip, rotation, brightness, noise).

🧠 Model:

Used YOLOv8 with transfer learning on a custom dataset.

Integrated a lightweight CNN backbone for efficiency.

🍓 Edge Deployment:

Optimized model for Raspberry Pi using TorchScript.

Built a Python script with OpenCV for real-time camera feed analysis.

🚨 Optional Alert System: Integrated GPIO for alarms upon detection.

Tech Stack: YOLOv8, PyTorch, Roboflow, OpenCV, Raspberry Pi, Imagesense AI, Python
