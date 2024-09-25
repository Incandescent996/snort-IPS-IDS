# snort-training

# Main Components of Snort

### 1. **Packet Decoder**  
Packet collector component of Snort. It collects and prepares the packets for pre-processing.

### 2. **Pre-processors**  
A component that arranges and modifies the packets for the detection engine.

### 3. **Detection Engine**  
The primary component that processes, dissects, and analyses the packets by applying the rules.

### 4. **Logging and Alerting**  
Log and alert generation component.

### 5. **Outputs and Plugins**  
Output integration modules (e.g., alerts to syslog/mysql) and additional plugin (rule management detection plugins) support are handled by this component.

---

## Types of Rules Available for Snort

### 1. **Community Rules**  
- Free rules

