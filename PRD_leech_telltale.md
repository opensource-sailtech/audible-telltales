# **Product Requirements Document (PRD)**

## **Product Name**: Audible/Taptic Leech Telltales

## **Author**: Kay VanValkenburgh

## **Date**: 2025-05-11

## **Version**: 3.0

---

### **1. Purpose**

The purpose of this product is to augment the visual information provided by telltales with **non-visual feedback**. Telltales inform sailors of airflow past a point on a sail based on their movement and behavior. The addition of non-visual feedback will allow sailors—novices and experts alike—to **trim sails more accurately** without needing to monitor the telltales visually , especially in low-visibility or high-concentration scenarios (e.g., racing, night sailing, close quarters with other vessels).

---

### **2. Background and Problem Statement**

Visual leech telltales are critical indicators of proper sail trim. However, they require **constant line-of-sight monitoring**, which is often impractical due to:

* Sailor's position limiting view of the leech, e.g. helm/trimmer unable to see jib leech due to mainsail, or unable to see mainsail leech while sitting to leeward in light air
* Poor visibility (including the sun in line with an overhead telltale, low lighting, low contrast colors) or nighttime sailing
* Helm and trimmer multitasking, and therefore unable to take more than a glance at telltales

A **non-visual system** that reflects telltale activity will help sailors **trim sails without visual cues**, increasing both performance and safety.

---

### **3. Goals and Objectives**

* Provide **real-time non-visual feedback** on leech telltale behavior
* Work for mainsail and headsail configurations
* Ensure **low power consumption** and **weather resistance**
* Be **removable or retrofit-friendly**
* Not interfere with sail shape or performance
* Allow **customization** of sound type or frequency

---

### **4. User Personas**

**Novice Sailor (Cruiser)**

* Focused on learning; benefits from coaching-style cues
* Needs intuitive sounds (e.g., flutter = warning tone)

**Experienced Racer**

* Wants minimal distraction
* Prefers adjustable settings for volume/sensitivity

**Sailing Instructor / Coach**

* Wants to teach proper trim through multiple modalities
* Needs a system that reinforces visual cues with audio

---

### **5. Product Scope**

#### **5.1 Features**

| Feature                               | Description                                                         |
| ------------------------------------- | ------------------------------------------------------------------- |
| **Sensor Integration**                | Lightweight sensor attached near each leech telltale                |
| **Sound Feedback**                    | Beeps, tones, or spoken cues that change based on flutter frequency |
| **Wireless Transmission**             | Option to transmit data to a central module or via Bluetooth        |
| **Smartphone Integration (Optional)** | Pairing with app for feedback history or real-time visualization    |
| **Adjustable Sensitivity**            | User can tune the sensitivity to telltale flutter amplitude         |
| **Volume Control / Mute**             | For racing or quiet-time usage                                      |
| **Battery Power**                     | Rechargeable battery with solar or USB backup                       |
| **Waterproof and UV-resistant**       | Designed for harsh marine environments                              |

---

#### **5.2 Out of Scope**

* Full sail trim automation
* Voice-controlled sail adjustments
* Non-leech telltale monitoring

---

### **6. Technical Requirements**

| Requirement         | Description                                                                 |
| ------------------- | --------------------------------------------------------------------------- |
| **Sensors**         | Must detect small amplitude flutter
| **Microcontroller** | Low-power, weatherproof unit for processing sensor data
| **Audio Output**    | Bluetooth audio (for earbuds or helm speaker)
| **Weight**          | minimize to avoid a flogging sail being damaged
| **Attachment**      | Adhesive, velcro, or sail-integrated pocket                                 |
| **Range**           | At least 10m wireless range from sensor to receiver                         |
| **Power**           | Min. 8-hour runtime per charge; solar assist preferred                      |

---

### **7. User Interface (if applicable)**

* **App or Device Display** (optional):

  * Battery status
  * Sensitivity calibration
  * Feedback signal selection (audio: tones, intensity; haptic: pattern, location, intensity)

---

### **8. Compliance and Safety**

* Must be waterproof to **IP68** minimum
* UV-resistant materials to avoid degradation
* Compliant with marine electronics safety standards
* Permits sailors to continue receiving other signals and to bring their focus to different concerns, including to spontaneous discussions, changes in the sound of water on the hull, sounds of nearby competitors, etc.
* Emits sound levels safe for hearing (max 85dB) and/or safe haptics (no tissue irritation for users after prolonged exposure)

---

### **9. Success Metrics**

* An independent observer confirms a trimmer adjusts sheet tension in keeping with changes in the behavior of a telltale
* > 90% of users report increased trim awareness
* Product and sail survive 500 hours of sun, salt spray, shallow immersion and sail movement (including occasional heavy flogging)
* Positive adoption by 3+ schools or teams

---

### **10. Open Questions**

* What is the best way to power the sensor module long-term, considering multiday passages?
* What form(s) of feedback are best suited when producing an MVP?
