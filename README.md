graph LR
  subgraph Participants
    A[Participants]
  end
  subgraph Applications
    B[DePIN Applications]
  end
  subgraph Network Layer
    C1[Consensus Mechanism]
    C2[Blockchain]
    C3[Smart Contracts]
  end
  subgraph Incentive Layer
    D1[Token]
    D2[Token Distribution]
  end
  subgraph Physical Infrastructure
    E[Physical Infrastructure]
  end
  A --> B
  B --> C1
  B --> C2
  B --> C3
  B --> D1
  C3 --> D1
  C3 --> D2
  D1 --> E
  D2 --> E
  C2 --> D1
  C2 --> D2
  C1 --> C2
  C1 --> C3
  C2 --> C3
  D1 --> B (dashed)
  D2 --> B (dashed)
  E --> B (dashed)
