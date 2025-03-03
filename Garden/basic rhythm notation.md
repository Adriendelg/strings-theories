---
tags:
  - 🌲
  - musictheory
  - rhythm
  - basics
upstream:
  - "[[music theory]]"
  - "[[the beat]]"
  - "[[tempo markings]]"
downstream:
  - "[[how to practice reading rhythm]]"
aligned: 
contrasting:
  - "[[compound time]]"
aliases:
  - simple time
---
Rhythm notation is all about division. Rhythm is maths. All note lengths are expressed as a fraction of the whole note. 

Here is one way to visualise it:
# diagram

```mermaid
graph TD
    A{Whole Note
    4 beats} --> B1{Half Note
    2 beats}
    A --> B2{Half Note
    2 beats}
    
    B1 --> C1{Quarter Note
    1 beat}
    B1 --> C2{Quarter Note
    1 beat}
    
    B2 --> C3{Quarter Note
    1 beat}
    B2 --> C4{Quarter Note
    1 beat}
    
    C1 --> D1{8th Note
    1/2 beat}
    C1 --> D2{8th Note
    1/2 beat}
    
    C2 --> D3{8th Note
    1/2 beat}
    C2 --> D4{8th Note
    1/2 beat}
    
    C3 --> D5{8th Note
    1/2 beat}
    C3 --> D6{8th Note
    1/2 beat}
    
    C4 --> D7{8th Note
    1/2 beat}
    C4 --> D8{8th Note
    1/2 beat}
    
    D1 --> E1{16th Note
    1/4 beat}
    D1 --> E2{16th Note
    1/4 beat}
    
    D2 --> E3{16th Note
    1/4 beat}
    D2 --> E4{16th Note
    1/4 beat}
    
    D3 --> E5{16th Note
    1/4 beat}
    D3 --> E6{16th Note
    1/4 beat}
    
    D4 --> E7{16th Note
    1/4 beat}
    D4 --> E8{16th Note
    1/4 beat}
    
    D5 --> E9{16th Note
    1/4 beat}
    D5 --> E10{16th Note
    1/4 beat}
    
    D6 --> E11{16th Note
    1/4 beat}
    D6 --> E12{16th Note
    1/4 beat}
    
    D7 --> E13{16th Note
    1/4 beat}
    D7 --> E14{16th Note
    1/4 beat}
    
    D8 --> E15{16th Note
    1/4 beat}
    D8 --> E16{16th Note
    1/4 beat}

    %% Styling
    style A fill:#81A1C1,color:#ECEFF4
    
    style B1 fill:#88C0D0,color:#2E3440
    style B2 fill:#88C0D0,color:#2E3440
    
    style C1 fill:#8FBCBB,color:#2E3440
    style C2 fill:#8FBCBB,color:#2E3440
    style C3 fill:#8FBCBB,color:#2E3440
    style C4 fill:#8FBCBB,color:#2E3440
    
    style D1 fill:#A3BE8C,color:#2E3440
    style D2 fill:#A3BE8C,color:#2E3440
    style D3 fill:#A3BE8C,color:#2E3440
    style D4 fill:#A3BE8C,color:#2E3440
    style D5 fill:#A3BE8C,color:#2E3440
    style D6 fill:#A3BE8C,color:#2E3440
    style D7 fill:#A3BE8C,color:#2E3440
    style D8 fill:#A3BE8C,color:#2E3440
    
    %% Sixteenth notes styling
    style E1 fill:#B48EAD,color:#ECEFF4
    style E2 fill:#B48EAD,color:#ECEFF4
    style E3 fill:#B48EAD,color:#ECEFF4
    style E4 fill:#B48EAD,color:#ECEFF4
    style E5 fill:#B48EAD,color:#ECEFF4
    style E6 fill:#B48EAD,color:#ECEFF4
    style E7 fill:#B48EAD,color:#ECEFF4
    style E8 fill:#B48EAD,color:#ECEFF4
    style E9 fill:#B48EAD,color:#ECEFF4
    style E10 fill:#B48EAD,color:#ECEFF4
    style E11 fill:#B48EAD,color:#ECEFF4
    style E12 fill:#B48EAD,color:#ECEFF4
    style E13 fill:#B48EAD,color:#ECEFF4
    style E14 fill:#B48EAD,color:#ECEFF4
    style E15 fill:#B48EAD,color:#ECEFF4
    style E16 fill:#B48EAD,color:#ECEFF4

    %% Link styling
    linkStyle default stroke:#5E81AC,stroke-width:2px
```


# on a staff

```music-abc
X:1
T:Basic Rhythm Divisions
M:4/4
L:1/4
K:C
%%score (1)
V:1 clef=treble
%% Whole note
C4 ||
%% Half notes
C2 C2 ||
%% Quarter notes
C C C C ||
%% Eighth notes
c/2c/2 c/2c/2 c/2c/2 c/2c/2 ||
%% Sixteenth notes
c/4c/4c/4c/4 c/4c/4c/4c/4 c/4c/4c/4c/4 c/4c/4c/4c/4 ||
```


# US vs UK
There are two terminologies used by UK and US, for once the US is the most straight forward and easy to understand one.

| American Term  | British Term | Relative Duration |
| -------------- | ------------ | ----------------- |
| Whole note     | Semibreve    | 4 beats           |
| Half note      | Minim        | 2 beats           |
| Quarter note   | Crotchet     | 1 beat            |
| Eighth note    | Quaver       | ½ beat            |
| Sixteenth note | Semiquaver   | ¼ beat            |

# how about silence?
```music-abc
X:1
T:Basic Rest Divisions
M:4/4
L:1/4
K:C
%%score (1)
V:1 clef=treble
%% Whole rest
z4 ||
%% Half rests
z2 z2 ||
%% Quarter rests
z z z z ||
%% Eighth rests
z/2z/2 z/2z/2 z/2z/2 z/2z/2 ||
%% Sixteenth rests
z/4z/4z/4z/4 z/4z/4z/4z/4 z/4z/4z/4z/4 z/4z/4z/4z/4 ||

```
These are the symbols used to indicate rest, silence, of the same length as the previous table.
# [[how to practice reading rhythm]]

# how about [[dotted note|dotted notes]]?
