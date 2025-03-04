---
tags:
  - 🪴
  - musictheory
aliases:
  - seventh chords
---
Tetrads are a [[triads|triad]] on which we piled another third, it is a stack of 3 thirds. 

We can build bigger even bigger chords, every note added to a tetrad is called an [[chord extensions|extension]].

```mermaid
graph TD
    A[Tetrad Construction] --> B[Bottom Third]
    B --> C[Major Third]
    B --> D[Minor Third]
    
    C --> E[Major Third + Major Third]
    C --> F[Major Third + Minor Third]
    D --> G[Minor Third + Major Third]
    D --> H[Minor Third + Minor Third]
    
    E --> I[Aug triad + Major Third]
    E --> J[Aug triad + Minor Third]
    F --> K[Major triad + Major Third]
    F --> L[Major triad + Minor Third]
    G --> M[Minor triad + Major Third]
    G --> N[Minor triad + Minor Third]
    H --> O[Dim triad + Major Third]
    H --> P[Dim triad + Minor Third]
    
    I --> Q[Augmented Major 7]
    J --> R[Augmented 7]
    K --> S[Major 7]
    L --> T[Dominant 7]
    M --> U[Minor Major 7]
    N --> V[Minor 7]
    O --> W[Half Diminished 7]
    P --> X[Diminished 7]
    
    Q --> Y1[R M3 A5 M7]
    R --> Y2[R M3 A5 m7]
    S --> Y3[R M3 P5 M7]
    T --> Y4[R M3 P5 m7]
    U --> Y5[R m3 P5 M7]
    V --> Y6[R m3 P5 m7]
    W --> Y7[R m3 d5 m7]
    X --> Y8[R m3 d5 d7]
    
    %% Aurora colors for different tetrad types
    style Q fill:#BF616A,color:#ECEFF4
    style R fill:#D08770,color:#2E3440
    style S fill:#EBCB8B,color:#2E3440
    style T fill:#A3BE8C,color:#2E3440
    style U fill:#88C0D0,color:#2E3440
    style V fill:#81A1C1,color:#ECEFF4
    style W fill:#B48EAD,color:#ECEFF4
    style X fill:#5E81AC,color:#ECEFF4
    
    %% Linkstyle for connecting lines
    linkStyle default stroke:#81A1C1,stroke-width:2px
```

There are 8 possible tetrads, some of them only appear when harmonising particular scales. 

Tetrads have a more complex and rich sound than [[triads]] and thus are used more in [[jazz]] than in [[pop music]]. 

The most used tetrads are:
- [[Major 7]]
- [[dominant]]
- [[minor 7]]
- [[half diminished]]

They are the most used as they are naturally found in the [[major scale]].

# [[major scale harmonisation in tetrads]]
# [[harmonic minor scale harmonisation in tetrads]]
