Hi! I'm José María Jiménez-Coronado, but you can call me Chema.
I'm an Electronics Engineer graduated from the Costa Rica Institute of Technology and devoted to space and plasma science.

Currently I'm working as a the Electronics Engineer Leader for the R&D department of an RF communications company based in the US, where I'm in
charge of tasks regarding FPGA, embedded systems, radiofrequency, DSP, electronic design, product design, product compliace and SDR.

You can contact me via email at josemarijc2010@hotmail.com 

```mermaid
  flowchart TD
    A[Inicio] --> B(Inicializar sum=0.0f)
    B --> C{i < 100?}
    C -->|Sí| D[Calcular exp_i]
    D --> E[sum = sum + exp_i]
    E --> F[i = i + 1]
    F --> C
    
    C -->|No| G[i = 0]
    
    G --> H{i < 100?}
    H -->|Sí| I[Calcular exp_i]
    I --> J[out_i = exp_i / sum]
    J --> K[i = i + 1]
    K --> H
    
    H -->|No| L([Fin])
```

this is test, only a test
