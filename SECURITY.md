# Security Considerations

Our IoT Environment Monitor can face several security risks.

## Security Risks

### 1. Default Credentials
Default usernames and passwords can allow unauthorized access.

### 2. Unencrypted Communication
Using HTTP or unsecured MQTT can expose sensor data.

### 3. Exposed Network Ports
Unnecessary open ports can increase the attack surface.

### 4. Hard-coded API Keys
Putting API keys directly into source code can expose cloud services.

### 5. Weak Authentication
An IoT device without proper authentication may be accessed by unauthorized users.

### 6. Sensor Data Manipulation
Attackers could potentially modify or inject false sensor readings.

## Security Mitigation

- Use strong and unique credentials.
- Use HTTPS or secure MQTT.
- Protect API keys and passwords.
- Avoid unnecessary open network ports.
- Implement device authentication.
- Keep ESP32 firmware and libraries updated.
- Use secure cloud communication.

## Project Security Goal

Security should be considered throughout the IoT system, from the sensor and ESP32 to the cloud dashboard.
