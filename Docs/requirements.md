# Requirements Analysis

In-depth consideration of needs from the perspective of BLV (Blind and Low Vision) population:

## Main Challenges for BLV Population:

### I. Physical Environment Interaction Challenges

#### 1. Navigation and Mobility

- **Dynamic Obstacles**
  - Temporarily parked shared bikes
  - Uncollected trash bins
  - Suddenly appearing children's toys
  - Pedestrian flow

- **Complex Terrain**
  - Irregularly distributed construction site barriers
  - Steps without warning signs
  - Revolving doors/turnstiles
  - Fixed facilities like doors, elevators, and stairs

- **Spatial Cognition**
  - 3D navigation in large malls/hospitals (e.g., "Room 5 in northwest corner of 3rd floor")
  - Seamless indoor-outdoor navigation
  - Understanding building layouts
  - Spatial positioning and memory

- **Transportation Systems**
  - Bus number recognition and station location
  - Subway transfer channel directions
  - Precise ride-hailing vehicle positioning
  - Traffic light recognition
  - Real-time traffic alerts

- **Environmental Perception**
  - Auditory signal attenuation in rainy/windy weather
  - Residual vision interference from strong light/reflections
  - Sense of direction in complex environments
  - Adaptation to weather changes

**Function Design Directions**:
- Fusion perception of millimeter-wave radar + LiDAR (penetrating rain and fog)
- 3D sound field navigation (different height layers distinguished by pitch)
- Real-time scene modeling based on edge computing (predicting moving obstacle trajectories)

#### 2. Daily Object Manipulation

- **Object Recognition**
  - Distinguishing similar packaged medicines
  - Banknote denomination recognition
  - Tactile feedback for appliance buttons
  - Food expiration date judgment
  - Clothing color and pattern identification

- **Spatial Positioning**
  - Memory of object positions on dining tables
  - Tactile search for clothes deep in wardrobes
  - Positioning and handling of daily items
  - Adaptation to indoor item layouts

- **Precision Operations**
  - USB port alignment
  - Threading needles
  - Touchscreen operation of electronic devices
  - Cooking and household chores
  - Precise positioning and control

**Function Design Directions**:
- Macro camera + tactile feedback gloves (object texture recognition)
- Sonar spatial mapping (building object position database)
- Augmented reality vibration guidance (indicating operation angles through bone conduction)

### II. Social Participation Barriers

#### 1. Non-Visual Social Interaction

- **Person Recognition**
  - Recognizing the same person in different outfits
  - Locating speakers in multi-person conversations
  - Understanding facial expressions and body language
  - Social distance perception

- **Context Understanding**
  - Accessing whiteboard content in meetings
  - Understanding visual content presented by others
  - Sensing group activity atmosphere
  - Grasping non-verbal cues

- **Self-Expression**
  - Confirming clothing coordination
  - Managing facial expressions
  - Adjusting social postures
  - Participating in visual interactions

**Function Design Directions**:
- Thermal imaging-assisted crowd counting and positioning
- Real-time voice transcription + semantic enhancement (annotating non-verbal information like laughter/applause)
- AI clothing coordination suggestions (identifying clothing tags via RFID)

#### 2. Information Access and Processing

- **Digital Content Access**
  - Quick browsing of web content
  - Graphical interface operation
  - Multimedia content understanding
  - Document format conversion

- **Educational Resource Usage**
  - Understanding textbook content
  - Interpreting chart data
  - Participating in online courses
  - Tracking learning progress

- **Vocational Skill Adaptation**
  - Using office software
  - Participating in remote meetings
  - Document processing and management
  - Professional skill training

**Function Design Directions**:
- Edge computing privacy protection (local processing of biometric features)
- Ultrasonic positioning guidance (millimeter-level operation guidance)
- Augmented reality overlay (projecting virtual operation interfaces on real objects)

#### 3. Health and Medical Care

- **Medical Service Access**
  - Understanding medical information
  - Viewing test reports
  - Navigating medical procedures
  - Emergency assistance

- **Health Management**
  - Medication guidance and reminders
  - Rehabilitation training assistance
  - Health status monitoring
  - Exercise posture correction

### III. Cognitive and Information Gap

#### 1. Graphical Information Black Hole

- **Data Visualization**: Stock K-line charts, weather forecast cloud maps, mathematical geometry diagrams
- **Cultural Symbols**: Icon metaphors in religious places, abstract expressions of traffic signs
- **Art Appreciation**: Light and shadow layers in paintings, brush stroke strength in calligraphy works

**Function Design Directions**:
- Topological structure description algorithm (converting graphics into touchable vibration codes)
- Multi-modal rendering engine (using temperature changes to represent color brightness)
- Cultural symbol knowledge graph (semantic interpretation combined with scenes)

#### 2. Real-time Information Delay

- **Instant Prompts**: Traffic light countdowns, time-limited discount QR codes, temporary road closure notices
- **Dynamic Information**: Live sports scores, stock market fluctuations, shared screens in online meetings

**Function Design Directions**:
- 5G edge computing node deployment (100ms level response)
- Differential information extraction technology (only transmitting changed data)
- Context-aware priority sorting (automatically filtering irrelevant information)

---

### IV. Special Scenario Dilemmas

#### 1. Medical Health

- **Vital Sign Monitoring**: Unable to view glucometer values, self-checking skin lesion locations
- **Medication Safety**: Confusing similar pills, reading injection dose scales
- **Rehabilitation Training**: Yoga posture correction, physiotherapy equipment operation guidance

**Function Design Directions**:
- Subcutaneous implant sensors + epidermal vibration feedback
- Drug molecule spectrum recognition
- Sports mechanics modeling and real-time correction

#### 2. Emergency Avoidance

- **Sudden Disasters**: Earthquake escape route planning, direction identification in fire smoke
- **Human-made Dangers**: Robbery warnings, accident liability determination assistance
- **Health Crises**: Stroke symptom recognition, rapid allergen detection

**Function Design Directions**:
- Multi-sensor threat assessment matrix (integrating air quality/vibration/sound wave parameters)
- Emergency communication relay mode (device networking in disconnected environments)
- Legal fact chain automatic recording (encrypted storage of environmental data 3 minutes before and after events)

---