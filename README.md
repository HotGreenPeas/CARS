# Tackling Parking Lot Congestion at the University at Buffalo’s North Campus with Car Automated Recognition System (CARS)

Parking at the University at Buffalo's North Campus can be extremely limited at times; students, faculty, and visitors often drive around aimlessly and hope to find parking. As a result, students are late for their classes, accidents are more likely to occur, and tensions arise between drivers over parking. Reducing parking lot congestion will alleviate these issues. The goal of our proposed system is real-time tracking of parking lot capacities so that drivers are informed and avoid full lots, thereby reducing congestion. The core of our solution is a machine-learning model that receives video input and detects the number of vehicles in the frame. The system's physical components are a USB camera, a Raspberry Pi 4, and an LCD display. The plan is to mount the system to light poles near parking lots for elevation and better camera coverage. For larger lots, additional cameras can be added. All processing is done locally, which protects the privacy of drivers and their vehicles. In addition, the parking data can be stored and analyzed for trends. Then, Parking and Transportation Services can use this data to improve the parking situation on North Campus further.

## Component List
|Part|Description|
|---|---|
|Raspberry Pi 4| A small [microprocessor](https://datasheets.raspberrypi.com/rpi4/raspberry-pi-4-product-brief.pdf?_gl=1*1nov031*_ga*MTkwOTQwNzA3LjE2OTU5NDc0ODY.*_ga_22FD70LWDS*MTY5NTk0NzQ4Ni4xLjAuMTY5NTk0NzQ4Ni4wLjAuMA..)|
|Logitech C310 Hs| A USB [webcam](https://www.logitech.com/assets/46734/5/hd-webcam-c310.pdf)|
|LCD1602| A LCD [display](http://wiki.sunfounder.cc/index.php?title=LCD1602_Module)|

## Software Flow Chart
![flow chart](phase1/CSE321%20Flowsheet%20and%20Architecture%20-%20Page%201%20(1).png)

## Architectural Block Diagram
![block diagram](phase1/CSE321%20Flowsheet%20and%20Architecture%20-%20Page%201%20(2).png)

## Software Block Diagram
## Setup and Execution
## References
[Working with model results](https://github.com/niconielsen32/YOLOv8-Class/blob/main/YOLOv8InferenceClass.py)

[Ultralytics](https://github.com/ultralytics/ultralytics/tree/main)

[LCD Display](https://medium.com/@thedyslexiccoder/how-to-set-up-a-raspberry-pi-4-with-lcd-display-using-i2c-backpack-189a0760ae15)

[RPLCD Docs](https://rplcd.readthedocs.io/en/stable/)
