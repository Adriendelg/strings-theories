---
tags:
  - 🪴
  - musictheory
  - rhythm
  - basics
---
The time signature of a piece is found at the beginning of the staff right along the [[key signature]]. It is composed of two numbers on top of each other. The top number tells us the number of [[the beat|beats]] per [[bars|bar]] while the lower tells us the [[basic rhythm notation|value]] of said beats.


```mermaid
graph TD
    A[Time Signature] --> B[Top Number]
    A --> C[Bottom Number]
    
    B --> D[Beats per Measure]
    C --> E[Note Value per Beat]
    
    E --> F1[1 = Whole Note]
    E --> F2[2 = Half Note]
    E --> F3[4 = Quarter Note]
    E --> F4[8 = Eighth Note]
    E --> F5[16 = Sixteenth Note]
    
    D --> G1[Simple Time]
    D --> G2[Compound Time]
    
    G1 --> H1[2/4<br/>2 beats per measure]
    G1 --> H2[3/4<br/>3 beats per measure]
    G1 --> H3[4/4<br/>4 beats per measure]
    
    G2 --> I1[6/8<br/>2 groups of 3]
    G2 --> I2[9/8<br/>3 groups of 3]
    G2 --> I3[12/8<br/>4 groups of 3]
    
    %% Styling
    style A fill:#81A1C1,color:#ECEFF4
    style B fill:#88C0D0,color:#2E3440
    style C fill:#88C0D0,color:#2E3440
    
    style D fill:#8FBCBB,color:#2E3440
    style E fill:#8FBCBB,color:#2E3440
    
    %% Note values styling
    style F1 fill:#A3BE8C,color:#2E3440
    style F2 fill:#A3BE8C,color:#2E3440
    style F3 fill:#A3BE8C,color:#2E3440
    style F4 fill:#A3BE8C,color:#2E3440
    style F5 fill:#A3BE8C,color:#2E3440
    
    %% Time types styling
    style G1 fill:#B48EAD,color:#ECEFF4
    style G2 fill:#B48EAD,color:#ECEFF4
    
    %% Examples styling
    style H1 fill:#5E81AC,color:#ECEFF4
    style H2 fill:#5E81AC,color:#ECEFF4
    style H3 fill:#5E81AC,color:#ECEFF4
    style I1 fill:#5E81AC,color:#ECEFF4
    style I2 fill:#5E81AC,color:#ECEFF4
    style I3 fill:#5E81AC,color:#ECEFF4
    
    %% Link styling
    linkStyle default stroke:#4C566A,stroke-width:2px
``` 
The most common time signature you will encounter in western music is 4/4 meaning four quarter notes per bar.

# three types of time signature
There are three big families of time signatures. One where we divide each beat in 2 called [[simple time]] or [[simple time|binary]], one where we divide the beat in three [[compound time]] or [[compound time|ternary]] and finally [[odd meters]] or [[odd meters|asymmetric meters]] where we have an odd number of beats per bar.

# [[simple time]]
This is the most common type of time signature and makes use of [[basic rhythm notation]]. 4/4, 2/2, 3/4 all fall under this category.

## [[compound time]]
While present in western music it is less common than simple time. Every quarter note is now a [[dotted note]] and is divided in three eighth notes. 6/8, 12/8 are compound time signatures.

## [[odd meters]]
Another animal altogether – usually found in [[progressive metal]], Balkan folk music or contemporary classical music – it features an odd number of beats per bar and can be decomposed in a variety of subdivisions. For example 5/8, 11/16, 7/8 are all odd meters.
