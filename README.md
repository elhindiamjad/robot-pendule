# Self-Balancing Inverted Pendulum Robot

Two-wheeled self-balancing robot, built as a personal project alongside myengineering studies at ENSEEIHT.


## Goals
- Estimate the tilt angle (complementary filter, then Kalman filter)
- Stabilize the robot with a PID controller, then with an LQR controller
- Real-time control loop on ESP32 (FreeRTOS)

## Hardware
ESP32, MPU6050 IMU, TB6612FNG motor driver, 2 DC motors with encoders


## Progress
- [x] Repository setup
- [ ] Order parts
- [ ] Test each module (IMU, motors, encoders)
- [ ] Complementary filter + PID
- [ ] Modeling and system identification
- [ ] Kalman filter + LQR
