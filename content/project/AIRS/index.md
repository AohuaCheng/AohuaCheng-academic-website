---
title: Autonomous Intubation Robot System

summary: An solution to avoid cross-infection in COVID-19.
tags:
  - Medical Robotics

date: “2021-12-03T07:22:00.826Z”
external_link: ""

image:
  caption: photo by our robot lab
  focal_point: Smart
  filename: featured.jpg
  alt_text: operating robot platform in experiments
links:
  - url: https://www.techrxiv.org/articles/preprint/Autonomous_Intubation_Robot_System_based_on_Visual_Servoing_and_Hybrid_Control/15087696
    name: preprint paper for our work
    icon_pack: ai
  - url: https://www.purdue.edu/crl/PandemicWorkshop/ICRA21_NoTouchCare.html
    name: A workshop in ICRA 2021 we gave a 30-min report

url_pdf: ""
url_code: ""
url_video: ""
url_slides: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: AIRS
---
During COVID-19 and other pandemics, endotracheal intubation is an effective and common method to save patients as the virus causes lung fibrosis and thus patients are unable to breathe spontaneously. Medical staff need to insert a tube close to the patient’s mouth, thereby leading to a high risk of cross-infection. To protect medical staff, we propose an autonomous intubation robot system (AIRS). With the developed visual servoing and hybrid control method, the entire system can simulate doctors for satisfying repeatability and safety of intubation operations. This system includes a self-driving/teleoperation platform, two co-robot arms, a new multi-functional laryngoscope, force sensors, and several cameras. In the visual servoing part, we realize recognition and location of the patient’s face, medical devices, and main physiological structures to provide real-time navigation. In the hybrid control part, we establish an oral model, propose an offline planning method and PID controllers by combining force, vision, and motion, and apply Virtual Fixture to insert safely. AIRS's validation is with a phantom model under a 2-min operation. Our proposed robot is original and promising in the area of emergent medical robots. We will further validate AIRS in clinical applications and extend the developed techniques in other general treatments.
