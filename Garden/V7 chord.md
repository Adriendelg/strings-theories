---
tags:
  - 🌲
  - musictheory
aliases:
  - dominant 7
---
The chord found on the fifth degree of the major scale when harmonising it in tetrads is very important, it gives us our [[dominant]] chord. It is one of the most important chord in [[tonal music]], even in styles that don't commonly use [[chord extensions]] we will find V7 chords. Even the simplest nursery rimes make use of this chord for [[tension and release]]. It is also the chord we use to play the [[blues]].


# why it works as tension

```mermaid
graph LR
    %% G7 Chord Nodes
    G7[G7 Chord] --> G1[G - Root]
    G7 --> F[F - Seventh]
    G7 --> B[B - Third]
    G7 --> D[D - Fifth]
    
    %% C Chord Nodes
    C[C Major] --> G2[G - Fifth]
    C --> E1[E - Third]
    C --> C1[C - Root]
    C --> E2[E - Third]
    
    %% Voice Leading Connections
    G1 --> G2
    F -->|↓ half step| E1
    B -->|↑ half step| C1
    D --> E2
    
    %% Styling
    style G7 fill:#81A1C1,color:#2E3440
    style C fill:#88C0D0,color:#2E3440
    
    style G1 fill:#A3BE8C,color:#2E3440
    style F fill:#BF616A,color:#ECEFF4
    style B fill:#D08770,color:#2E3440
    style D fill:#EBCB8B,color:#2E3440
    
    style G2 fill:#A3BE8C,color:#2E3440
    style E1 fill:#81A1C1,color:#ECEFF4
    style C1 fill:#5E81AC,color:#ECEFF4
    style E2 fill:#81A1C1,color:#ECEFF4
    
    %% Notes
    classDef note text-align:center,font-weight:bold
    class G7,C,G1,F,B,D,G2,E1,C1,E2 note
```

The V7 chord is the perfect tension chord and the [[V - I]] cadence gives release thanks to the resolution of the double leading notes. Here G7 has two notes (B and F forming a [[Tritone]]) that are a [[the 12 semitones|half step]] away from a [[chord tone]] of the [[tonic]] creating a strong pull. 

# the most extensible chord
The dominant 7 is the type of chord that can feature the widest range of [[chord extensions]]. All [[scale degrees]] can be altered and used as extensions to make the chord more dissonant or tense.

[[V7 chord alterations]]