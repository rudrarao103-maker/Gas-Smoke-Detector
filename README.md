# Gas-Smoke-Detector
ESP32-based gas detector. It calibrates the MQ2 sensor (which detects gases like LPG, methane, etc.) in clean air, sets a threshold, and then monitors for gas levels. If gas is detected above the threshold, it activates a buzzer and sends alerts to a Telegram chat. The code uses WiFi for internet connectivity to send Telegram messages.
