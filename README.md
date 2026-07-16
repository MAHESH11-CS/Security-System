# Security-System
A smart Home Security System that detects unauthorized access using sensors, triggers alarms, and provides real-time alerts to enhance residential safety.
import random
import time

print("Home Security System Activated")

while True:
    # Simulate motion detection (True = Motion, False = No Motion)
    motion_detected = random.choice([True, False])

    if motion_detected:
        print("🚨 Motion Detected! Intruder Alert!")
        print("Alarm Activated!\n")
    else:
        print("✅ Area Secure. No Motion Detected.\n")

    time.sleep(2)
