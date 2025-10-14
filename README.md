# Human Machine Interaction Beyond Screens

There have been many recent advances in the field of **Human Machine Interaction (HMI)**, with most solutions for computer output to humans being centered around *Displays* and *Screens* of various sizes and types.  
These solutions rely on intuitive user interfaces with text and graphics to render large volumes of information to users.  

In our lab, we pursued an alternative approach — to explore methods of outputting information to human users *beyond screens*, that is, without using any display or screen.

---

## Project Overview

With this goal in mind, we developed a project from scratch that senses ambient sounds and noises in an environment and employs **machine learning–based classification** to detect their type (with a certain level of accuracy).  

This information is then conveyed to nearby users through a **wireless channel**.

For this purpose, we used a **Raspberry Pi 4–based Base Station** for sound capture and processing, along with enabling a **Wi-Fi hotspot** for wireless connectivity.

![Figure 1: System Architecture Overview](images/system_overview.png)

---

## Wearable Band System

The user receives the classified signal (corresponding to the type of noise or sound) through a **wearable band–type gadget**, with the signal being rendered through specific **sensations on the skin**.

There are **three types of sensations** delivered through the wearable band:

- **Rubbing**
- **Poking**
- **Pressing**

Different combinations of these sensations are used to convey specific types of environmental sounds, such as a doorbell, a baby crying, etc.

Up to **five wearable bands** can be connected to a receiving station via individual cables.  
These can be integrated into clothing apparel through multiple wearable gadgets that we call the **_SoundSense Suit_**.

The system can be powered by a **5V–12V external battery or power supply**, and uses a **Raspberry Pi Pico 2W** microcontroller with a servo motor control system.

![Figure 2: Wearable Band Prototype](images/wearable_band.png)

---

## Design & Wearability

For flexibility and user comfort, the wearable bands can be conveniently adjusted to different parts of the body, including:

- Wrists  
- Biceps  
- Thighs  
- Calves  
- Head (inside a cap or helmet)  
- Stomach or chest  
- Even underarms  

To prevent dangling wires between the receiver station and wearable bands, we recommend **stitching the thin cables directly into clothing apparel** such as jackets, pants, or jumpsuits.

![Figure 3: Suggested Wearable Configuration](images/soundsense_suit.png)

---

## Features & Future Potential

With our developed solution, a user can conveniently discern **more than 8 classified audio signals per wearable band**.  
Thus, with five wearable bands, the system can deliver **over 40 distinct tactile signals**.

These skin sensations can be **memorized through user training** for various applications.

Additionally, with Wi-Fi hotspot connectivity, our product can be extended to connect and interact with **multiple receiver devices** — such as LED panels or other actuation-based accessories.

This opens the door to creating a **business ecosystem** of compatible product accessories for prospective customers.

![Figure 4: System Connectivity Diagram](images/connectivity.png)

---

## Business and Fashion Integration

With its wearability aspect, our product has potential for **collaboration with clothing and fashion brands** — allowing it to be marketed both as a **fashion trend** and a **personal utility gadget**.

![Figure 5: Concept Illustration – Fashion Integration](images/fashion_integration.png)

---

### Summary of Key Features

| Feature | Description |
|----------|--------------|
| **Core Concept** | Output of ambient sound information without screens |
| **Processing Unit** | Raspberry Pi 4 (Base Station) |
| **Wearable Unit** | Raspberry Pi Pico 2W with servo control |
| **Communication** | Wi-Fi hotspot connectivity |
| **Sensations Used** | Rubbing, Poking, Pressing |
| **Supported Bands** | Up to 5 simultaneous wearable bands |
| **Total Signals** | Over 40 distinguishable tactile patterns |
| **Power Supply** | 5V–12V battery or external adapter |
| **Expansion** | Multiple receiver types and accessories |
| **Potential Partners** | Clothing and fashion brands |
