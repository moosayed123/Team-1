# Team-1
intern DifAllah 


# Automated Attendance System

## Project Overview
This project aims to create a **complete school management system** that covers three main components:

### 1. Attendance and Access Control at the School Gate
Using AI and embedded systems, the system identifies attendance at the school gate. Recognized individuals are automatically logged, and the gate opens for them. If an **unrecognized person** is detected, a notification is sent to supervisors like **Mr. Mohamed Adly** or **Mr. Ahmed Fouad** to decide whether to allow entry.

![Attendance System](https://link_to_attendance_image)

### 2. Student Assistance System
This module helps students with school-related questions without needing to approach school supervisors, thus reducing interruptions in their workflow.

### 3. Substitute Class Management System
Mr. **Ahmed Fouad**, the scheduling expert, uses this system to manage substitute classes. Teachers are notified of substitute classes and reminded of their sessions to prevent delays. Additionally, the system automatically rings the school bell for each class and break.

![Class Management System](https://link_to_class_management_image)

---

## Sprint Breakdown

### Sprint 1: Camera System (2 Weeks)
**Goal:** Develop a camera-based attendance and access control system using AI and Raspberry Pi.

#### Tasks:
1. **Choose the AI Module** (1 day)
2. **Collect Data** (5 days)
3. **Create the AI Module** (3 days)
4. **Develop the Embedded System and Integrate with Raspberry Pi** (3 days)
5. **Design UI/UX** (2 days)

📅 **Deployment:** End of Sprint 1

![Raspberry Pi System](https://link_to_raspberry_pi_image)

---

### Sprint 2: Chatbot System (13 Days)
**Goal:** Develop an AI-powered chatbot to assist students with their questions.

#### Tasks:
1. **Choose the AI Module** (2 days)
2. **Collect Questions & Answers Data** (3 days)
3. **Develop the Chatbot Module** (7 days)
4. **Test the Chatbot** (1 day)

📅 **Deployment:** End of Sprint 2

![Chatbot System](https://link_to_chatbot_image)

---

### Sprint 3: Web-Based Substitute Class Management (15 Days)
**Goal:** Develop a system to manage substitute classes, notify teachers, and automate the school bell ringing.

#### Tasks:
1. **Develop Reminder System Using Python Libraries** (`Time` and `SMS`) (3 days)
2. **Design and Develop Web Interface for Class Distribution** (10 days)
3. **Implement Alarm System for Class and Break Times** (2 days)

📅 **Deployment:** End of Sprint 3

![Web Interface](https://link_to_web_interface_image)

---

## Requirements

### Python Libraries:
- OpenCV (`cv2`)
- TensorFlow
- Keras
- NumPy
- Pandas
- Time
- SMS
- Matplotlib
- UltraLatex
- Signal
- Base64
- Datetime
- RPi.GPIO
- Requests

### Hardware Components:
- **Raspberry Pi 3**
- **Arduino Mega**
- Wires
- Speakers
- Microphones
- Cameras
- Automatic Door (if available)

---

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/username/repo-name.git
    ```
2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main script:
    ```bash
    python main.py
    ```

---

## Contributors
- **Abdullah** (Lead Developer)
- **Mohamed Adly** (Supervisor)
- **Ahmed Fouad** (Scheduler)

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

