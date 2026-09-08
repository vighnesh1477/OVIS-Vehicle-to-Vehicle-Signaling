# OVIS — Vehicle-to-Vehicle Signaling

Real-time vision-based overtaking assistance system using vehicle perception and vehicle-to-vehicle optical signaling.

---

## ⚠️ The Problem

Overtaking on roads can become risky when the driver has limited visibility of the road ahead or cannot reliably determine whether an overtaking maneuver is safe.

In such situations, the absence of clear information from the vehicle ahead can make it difficult for a following driver to decide whether to **overtake, wait, or avoid overtaking**.

### 🎥 Problem Scenario

<p align="center">
  <video controls width="700">
    <source src="YOUR_GITHUB_VIDEO_ASSET_URL" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

The above scenario demonstrates the challenge that motivates the development of OVIS — providing a clear optical indication from the vehicle ahead to assist the following driver during overtaking decisions.

---

## 💡 OVIS — Proposed Solution

OVIS (**Vehicle-to-Vehicle Signaling**) is a real-time vision-based overtaking assistance system that analyzes the surrounding road environment and communicates an overtaking recommendation through an optical signaling interface.

The system provides three signal states:

* 🟢 **Green** — Overtaking permitted
* 🟠 **Orange** — Standby / wait
* 🔴 **Red** — Overtaking not recommended

---

## 🎥 Project Demonstration

<p align="center">
  <a href="https://youtu.be/kccB6SFx-20">
    <img src="https://img.youtube.com/vi/kccB6SFx-20/maxresdefault.jpg" width="700">
  </a>
</p>

<p align="center">
  <b>▶️ Click the image to watch the complete OVIS demonstration</b>
</p>

---

## 🚗 Real-World Testing

### 🟢 Green Signal — Overtaking Permitted

<p align="center">
  <img src="./vehicle%20giving%20the%20green%20signal%20in%20realworld%20testing%20and%20bike%20overtaking.png" width="500">
</p>

Real-world demonstration of the vehicle providing a green optical signal, indicating that overtaking is permitted.

---

### 🟠 Orange Signal — Standby

<p align="center">
  <img src="./vehicle%20giving%20the%20orenge%20signal%20in%20realworld%20testing.png" width="500">
</p>

Real-world demonstration of the orange optical signal, indicating a standby condition before overtaking.

---

### 🔴 Red Signal — Overtaking Not Recommended

<p align="center">
  <img src="./vehicle%20giving%20the%20red%20signal%20in%20realworld%20testing.png" width="500">
</p>

Real-world demonstration of the red optical signal, indicating that overtaking should not be performed.

---

## 📊 Experimental Results

### Environmental Visibility Analysis

<p align="center">
  <img src="./Class-wise%20Precision%2C%20Recall%2C%20and%20F1-score%20of%20the%20Proposed%20Environmental%20Visibility%20Analysis%20Module.png" width="600">
</p>

Class-wise Precision, Recall, and F1-score of the proposed Environmental Visibility Analysis Module.

---

### Road-Type Classification

<p align="center">
  <img src="./Comparison%20Between%20the%20Challenging%20and%20Clean%20Datasets%20for%201%20way%20and%202%20way.png" width="600">
</p>

Comparison between challenging and clean datasets for one-way and two-way road classification.

---

### RT-DETR and Proposed System

<p align="center">
  <img src="./ground-truch-rtdetr-and%20proposed%20system%20graph..png" width="600">
</p>

Comparison of the evaluated RT-DETR results with the proposed system.

---

### Accuracy Comparison

<p align="center">
  <img src="./yolo%20seris%20and%20our%20system%20accuracy%20comparison.png" width="600">
</p>

Accuracy comparison between the evaluated YOLO-series models and the proposed system.

---

### Speed Comparison

<p align="center">
  <img src="./yolo%20seris%20and%20our%20system%20speed%20comparison.png" width="600">
</p>

Processing-speed comparison between the evaluated YOLO-series models and the proposed system.

---

## 📫 Contact

**Vighnesh Poojary**

📧 **Email:** [Vighneshpoojary49@gmail.com](mailto:Vighneshpoojary49@gmail.com)

💼 **LinkedIn:** https://www.linkedin.com/in/vighnesh-poojary-006b65329/

💻 **GitHub:** https://github.com/vighnesh1477
