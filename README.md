                                               V.S.Gopthreya_MinorProject
# Quantum-Inspired Digital Watermarking for Forensic Evidence Authentication Using BB84 QKD

### About the Project
This project proposes a quantum-inspired digital watermarking framework for forensic evidence authentication, leveraging principles from the BB84 Quantum Key Distribution (QKD) protocol. The primary objective is to ensure integrity, authenticity, and tamper detection of sensitive digital forensic evidence such as images, videos, or documents.
By integrating quantum cryptographic concepts with classical digital watermarking, the system introduces a novel, forward-looking approach to combating evidence manipulation, unauthorized access, and replay attacks in digital forensics.


### Why This Project?
Digital forensic evidence plays a critical role in legal investigations, cybercrime analysis, and judicial proceedings. However, existing systems face several limitations:
Vulnerability to tampering and forgery
Dependence on classical cryptographic keys, which are susceptible to future quantum attacks
Difficulty in detecting subtle modifications
Lack of strong key exchange guarantees
This project addresses these challenges by:
Introducing quantum-inspired security mechanisms
Applying BB84 QKD principles to watermark key generation
Enhancing trust, traceability, and legal admissibility of digital evidence



### About Digital Watermarking
Digital watermarking is a technique used to embed hidden information into digital media without significantly affecting perceptual quality.

#### Key Characteristics:
 1. **Imperceptibility:** The watermark does not degrade visual or audio quality
 2. **Robustness**: Resistant to compression, noise, cropping, and attacks
 3. **Security**: Difficult to detect, remove, or alter without authorization
 4. **Authentication**: Enables ownership verification and tamper detection
  
### Role in Digital Forensics:
 1. Ensures chain-of-custody
 2. Detects unauthorized modifications 
 3. Provides court-admissible integrity verification



#### In this project, watermarking is used as a forensic authentication layer, strengthened using quantum-inspired key management.



### About BB84 Quantum Key Distribution (QKD)
BB84 is the first and most widely known quantum key distribution protocol, proposed by Charles Bennett and Gilles Brassard (1984).

### Core Principles:
  Uses quantum states (polarization bases) to encode bits
  Any eavesdropping attempt introduces detectable disturbances
  Ensures unconditional security based on quantum mechanics
  
### Why BB84 in This Project?
Although real quantum hardware is not used, BB84 principles are simulated to:
  Generate high-entropy, unpredictable keys
  Prevent key interception and replay
  Introduce future-proof, quantum-resistant security
  
#### These keys are used for:
Watermark embedding
Watermark extraction and verification
Evidence authentication

```mermaid

flowchart TD
    A[(Digital Forensic Evidence Input)] --> B[BB84 QKD Key Simulation]
    B --> C([Quantum-Inspired Secure Key Generation])
    C --> D[Digital Watermark Embedding]
    D --> E[Watermarked Evidence Storage / Transmission]
    E --> F[Watermark Extraction]
    F --> G[Authentication & Integrity Verification]
    G --> H[Forensic Decision Output]

```

## BB84 Quantum Key Distribution (Simulated)

```mermaid

flowchart LR
    A[Alice Generates Random Bits] --> B[Selects Random Polarization Bases]
    B --> C[Encodes Bits into Quantum States]
    C --> D[Quantum Channel Transmission]
    D --> E[Bob Selects Random Measurement Bases]
    E --> F[Measures Incoming Qubits]
    F --> G[Public Basis Comparison]
    G --> H[Discard Mismatched Bits]
    H --> I[Final Secure Key Generation]
```

## Digital Watermark Embedding Process

```mermaid

flowchart LR
    A[Original Forensic Image] --> B[Preprocessing]
    B --> C[Transform Domain Conversion]
    C --> D[BB84-Derived Secure Key Input]
    D --> E[Watermark Generation]
    E --> F[Watermark Embedding]
    F --> G[Inverse Transform]
    G --> H[Watermarked Forensic Evidence]
```


## Credits:
Developed by: VATNALA SHIVA GOPTHREYA KUMAR (AM.SC.P2CSN24012)

Program: M.Tech Cybersecurity Systems & Networks

Institution: Amrita School of Computing

Guide: Ms.SREELAKSHMI 
