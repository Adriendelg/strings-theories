---
tags:
  - 🌱
  - musictheory
  - chord
  - "#structure"
function:
  - T
  - D
---
Major triads are a very common and useful building block of music. They are found on different degrees of most scales such as: 
- [[major scale]]
- [[melodic minor scale]]
- [[harmonic minor scale]]

They can be found in two configurations:
- [[closed position]]
- [[spread voicing]]

# in closed position
## composition
```mermaid
graph BT
    %% Basic Construction
    A[Root] --> B[Major Third]
    B --> C[Perfect Fifth]
    
    %% Example in C
    D[Root Position<br/>Example: C-E-G] --> E[First Inversion<br/>Example: E-G-C]
    E --> F[Second Inversion<br/>Example: G-C-E]
    
    %% Interval Structure for each inversion
    G[Bottom to Top:<br/>Major 3rd + Minor 3rd] --> D
    H[Bottom to Top:<br/>Minor 3rd + Perfect 4th] --> E
    I[Bottom to Top:<br/>Perfect 4th + Major 3rd] --> F
    
    style A fill:#88C0D0,color:#2E3440
    style B fill:#81A1C1,color:#ECEFF4
    style C fill:#5E81AC,color:#ECEFF4
    style D fill:#EBCB8B,color:#2E3440
    style E fill:#D08770,color:#2E3440
    style F fill:#BF616A,color:#ECEFF4
    style G fill:#A3BE8C,color:#2E3440
    style H fill:#A3BE8C,color:#2E3440
    style I fill:#A3BE8C,color:#2E3440
    
    linkStyle default stroke:#81A1C1,stroke-width:2px
```
## on a staff
```music-abc
X:1
T:C Major Triad and Inversions
M:4/4
L:1/4
K:C
[CEG]2 [EGc]2| [Gce]2 |]
```

# in spread position

## composition
```mermaid
graph BT
    %% Basic Construction
    A[Root] --> B[Perfect Fifth]
    B --> C[Major Tenth]
    
    %% Example in C
    D[Root Position<br/>Example: C-G-E] --> E[First Inversion<br/>Example: E-C-G]
    E --> F[Second Inversion<br/>Example: G-E-C]
    
    %% Interval Structure for each inversion
    G[Bottom to Top:<br/>Perfect 5th + Major 6th] --> D
    H[Bottom to Top:<br/>minor 6th + Perfect 5th] --> E
    I[Bottom to Top:<br/>Major 6th + minor 6th] --> F
    
    style A fill:#88C0D0,color:#2E3440
    style B fill:#81A1C1,color:#ECEFF4
    style C fill:#5E81AC,color:#ECEFF4
    style D fill:#EBCB8B,color:#2E3440
    style E fill:#D08770,color:#2E3440
    style F fill:#BF616A,color:#ECEFF4
    style G fill:#A3BE8C,color:#2E3440
    style H fill:#A3BE8C,color:#2E3440
    style I fill:#A3BE8C,color:#2E3440
    
    linkStyle default stroke:#81A1C1,stroke-width:2px
```
## on a staff
```music-abc
X:1
T:C Major Triad - Spread voicings
M:4/4
L:1/4
K:C
% Open voicings (spread)
[CGe]2 [Ecg]2|[Gec']2  |
```
# on the neck
[[major triads in standard tuning]]
[[major triads in P4]]