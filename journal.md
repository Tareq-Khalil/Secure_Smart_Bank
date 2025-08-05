# Project Journal

## Title: *Secure_Smart_Bank*  
**Author**: Mina Romany Mina Habib  
**Description**: A smart and sustainable banking system integrating eco-friendly construction materials with embedded systems for automation, environmental monitoring, and real-time security control.  
**Start Date**: 23/06/2025  
**Total Time Spent**: 72 hours

---

## Daily Development Log

### 23/06/2025  
Today marked the beginning of my work on the *Secure_Smart_Bank* project. I spent around six hours brainstorming the essential features I wanted the prototype to include. My primary goal was to merge sustainability with automation, so I began sketching rough architectural concepts and outlining the core ideas that would drive the system. I also took time to explore different smart building models and renewable energy implementations to draw inspiration. By the end of the day, I had a clear list of goals and a vision to guide the rest of my work.

---

### 24/06/2025  
With the conceptual foundation laid, I moved on to designing the initial 3D layout of the structure. I dedicated about six hours exploring different shapes that would promote energy efficiency—particularly dome shapes that support passive cooling. I also began researching natural insulation materials, focusing on clay-straw combinations known for their thermal retention. As I studied more, I jotted down potential sources for these eco-materials and compared their properties in terms of local availability and cost-effectiveness.

---

### 25/06/2025  
This day was more technically focused. I finalized the overall shape and structure of the bank and began performing basic calculations regarding wall thickness and foundation dimensions. I also simulated airflow patterns to ensure proper natural ventilation, trying to minimize the need for artificial cooling systems. Although it was a shorter session (around four hours), it helped solidify the practical dimensions I would need to follow in the next steps.

---

### 26/06/2025  
I shifted gears to the embedded system side of the project. My focus today was on designing the power distribution network for the ESP32 microcontroller. I identified which sensors I would be integrating and began sketching out how everything would connect. I spent about five hours experimenting with circuit layouts and exploring how to efficiently manage power across all modules.

---

### 27/06/2025  
Today I began prototyping the sensor logic on a breadboard. I started with the PIR motion sensor, successfully integrating it with the ESP32. I also connected a DHT11 sensor and spent some time debugging unstable temperature readings. This session took me five hours, but it was rewarding to see the system beginning to respond to real environmental input.

---

### 28/06/2025  
I turned my attention to the renewable energy inputs. I designed a dual-input system using both solar panels and a small water turbine. Using flow rate estimates, I calculated the RPM required for the turbine and simulated power outputs for both sources. Though the session only lasted four hours, it was an exciting step forward in ensuring the project’s energy autonomy.

---

### 29/06/2025  
Continuing with the power systems, I tested different load scenarios using a multimeter. I measured battery charge and discharge cycles and calculated how long the system could run on two 18650 lithium-ion cells. These tests gave me a clearer understanding of the power consumption profile and helped me plan for more realistic uptime expectations.

---

### 30/06/2025  
Integration between hardware and software began to take shape today. I connected my Firebase real-time database to an interface built in MIT App Inventor and tested communication with the ESP32. I managed to implement temperature notifications, allowing real-time alerts to be pushed to a mobile device. These six hours were intense but deeply satisfying—it finally started to feel like a working system.

---

### 01/07/2025  
My goal for today was to complete the smart door locking mechanism. I developed a trigger system that uses a PIR sensor and servo motor to automatically control access. I encountered issues with false motion detections and delays in servo response, but after debugging, I added a buzzer system to sound alerts during suspicious entries. It took the full six hours, but the result was functional and reliable.

---

### 02/07/2025  
This session was more about refinement. I documented the entire system architecture, ensuring that every module was properly recorded. I also finalized the placement of each sensor, calculating optimal positions based on detection angles, coverage range, and accessibility. It felt great to bring more structure to the project and move closer to the final build.

---

### 04/07/2025  
I returned to circuit design and spent five hours crafting a more detailed and accurate wiring diagram. I included a relay module to control peripheral devices like a pump and lighting. After assembling everything virtually, I tested voltages across all major pins to confirm safe operating levels. At this point, I felt confident in the system’s electrical integrity.

---

### 05/07/2025  
My main task today was integrating sound detection into the application. I simulated the behavior where the system could react to audio cues—for example, turning on lights when it hears a knock. I also added logic to the app that would allow data restoration in the event of a loss or sync failure. It was a long day, but the system now felt more dynamic and responsive to real-world conditions.

---

### 06/07/2025  
With most of the development complete, I turned my attention to wrapping things up. I organized all the documentation, gathered photos and screenshots of the system in action, and carefully reviewed the wiring and pinout plans. Although five hours wasn’t enough to perfect everything, it brought everything together in a way I was proud of.

---

### 07/07/2025  
On the final day, I went through the bill of materials (BOM), double-checking all components and sourcing information. I wrote the README file, finalized this journal, and sat with my mentor to verify all the major calculations—particularly those related to energy use and materials. Their feedback helped validate the project and close it on a confident note.

---

## Visual Documentation

### System Development Images
- ![](Pictures/picc.png)
- ![](Pictures/piic.jpg)
- ![](Pictures/piiic.jpg)

### Expected Results
- ![Expected Output](Pictures/image-1.png)

### System Analysis
- ![App Interface](Pictures/image.png)
- ![MIT App Inventor Blocks](Pictures/image-2.png)

### Theoretical Concepts Referenced
- ![Faraday’s Law and Power Generation](Pictures/image-3.png)
