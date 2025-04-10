# 🎛️ RLB Device Control Web Interface

A browser-based UI to control and monitor **BrightSign** devices. Features include HDMI-CEC command execution, screenshot preview, user variable management, and custom UDP transmission.

---

## 🚀 Features

### 🔌 HDMI-CEC & Power Save Commands
- Send predefined HDMI-CEC commands (e.g., power ON/OFF, LG input source switch).
- Displays real-time command status with response codes and timestamps.

### 📷 Screenshot Preview
- Capture screenshots of current display output.
- Timestamped image preview with cache-busting updates.

### 📺 EDID & HDMI Status
- View connected display’s EDID information (manufacturer, model, etc).
- HDMI connection, audio, and power save status shown in real-time.

### 🧠 User Variables
- Display BrightAuthor user variables dynamically.
- Inline editing with Save per variable or Save All option.
- Rearrangement with ↑ / ↓ buttons.

### 🧾 Custom HDMI-CEC Commands
- Add, delete, or modify custom HDMI-CEC commands.
- Send them directly from the interface.
- Commands are saved and persist across sessions.
- Supports reordering.

### 📡 Custom UDP Commands
- Send raw UDP payloads to a specified port.
- Each command includes:
  - Name
  - Payload (message)
  - Target port
- Commands are persistent and reorderable.

---

