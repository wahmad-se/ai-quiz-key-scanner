# Automated Intelligent Quiz Scanner & Live Grading Engine

An automated, hands-free web application designed to instantly classify, process, and evaluate academic quiz sheets in real time using background frame dispatcher capture streams.

## Live Deployment Link
🚀 **Try the live application here:** [https://wahmad-se-quiz-ocr-scanner.hf.space/](https://wahmad-se-quiz-ocr-scanner.hf.space/)

## Founders
* **Waleed Ahmad** (FA24-BSE-094)
* **Taqi Haider**  (FA24-BSE-063)
* **Dawood Mumtaz** (FA24-BSE-131)

---

## Tasks Completed

1. **Automated Hands-Free Frame Dispatcher Loop**: Implemented a background runtime process that uses web browser media tracks to automatically capture camera frames at a 1.5-second interval without requiring manual capture inputs.
2. **Dynamic Split-Column UI Presentation Dashboard**: Built a responsive horizontal interface that presents grading details symmetrically split into *Answers Part-I* on the left column and *Answers Part-II* on the right column.
3. **Dual-Intercept Processing Strategy**: Configured a backend router capable of identifying standalone question assets via QR decoding and full-page multi-question sheets using text anchors.
4. **Explicit Multi-Question Grading Evaluation Logic**: Added backend comparison matrices that map student checkmark submissions, validate row items line-by-line, calculate scores, and display passing or failing markers (✔/✘) dynamically on the dashboard.
5. **Excel/CSV Export Schema Simulation**: Established an output structure to record graded evaluations locally for university grading ledger updates.

---

## Libraries & Frameworks Used

* **Backend**: Python 3, Flask (Micro-web application context router)
* **Computer Vision & Processing**: OpenCV (`opencv-python` for frame decoding and QR analysis)
* **OCR Text Localization Engine**: EasyOCR & PyTorch (For processing sheet variant textual anchor keywords)
* **Frontend**: HTML5, CSS3 (Flexbox Layout Grid Architecture), JavaScript (Background asynchronous fetch stream API)

---

## How to Install and Run Locally


If you want to run it on your pc or phone then visit this link (https://wahmad-se-quiz-ocr-scanner.hf.space/)
If you want to clone this repository and run it on your local machine, follow these steps:

### 1. Prerequisites
Ensure you have Python 3.8 or a newer version installed on your operating system.

### 2. Dependency Installation
Open your terminal or command prompt inside the root project folder and run the following command to install the required external modules:
```bash
pip install flask opencv-python easyocr torch torchvision