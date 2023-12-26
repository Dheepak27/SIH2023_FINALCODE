# SIH2023_FINALCODE


The main.py file encompasses the solution to the Smart India Hackathon problem statement 1417. This project addresses the critical issue of AI/ML image dehazing to facilitate rescue operations. The approach involves the utilization of Dark Channel Prior (DCP) for dehazing and YOLO for the detection of humans post-dehazing. Noteworthy is its versatility, supporting both image and video inputs, and successfully tested with live inputs from a mobile camera.

Dehazing Algorithm: Dark Channel Prior (DCP)
The project employs the powerful Dark Channel Prior for image dehazing, significantly enhancing visibility in hazy conditions.

![image](https://github.com/Dheepak27/SIH2023_FINALCODE/assets/89765006/42029306-4c5a-4f76-8561-24cb0342ba02)

Object Detection: YOLO (You Only Look Once)
YOLO, specifically the weights from best.pt, is utilized for accurate and real-time detection of people in dehazed images and videos.

![image](https://github.com/Dheepak27/SIH2023_FINALCODE/assets/89765006/2cc480e0-2a63-4e89-9fa6-6da1525ad7bc)

Platform Compatibility:
Rigorous testing across various operating systems ensures adaptability, making it suitable for both high-end and low-end systems.

Live Input Support:
Successfully tested with live inputs from mobile cameras, demonstrating the project's robustness in real-time scenarios.

Additional Feature: Heatmap for People Density
The project incorporates a heatmap feature, visually representing the intensity of people present in specific areas.

![image](https://github.com/Dheepak27/SIH2023_FINALCODE/assets/89765006/88f8cb2b-2d51-4780-bcaa-7efbd3e207ac)


Dependencies:
Open-CV(Contrib),YOLO-ultralytics(Version 8),OS,Numpy,Time,cv2.ximprog









