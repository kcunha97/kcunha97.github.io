flowchart TD
    A[Start Game] --> B[Player makes a guess]
    B --> C{Is the guess correct?}
    C -->|Yes| D[Player wins!]
    C -->|No| E{Is the guess too high or too low?}
    E -->|Too High| F[Give hint: Try a lower number]
    E -->|Too Low| G[Give hint: Try a higher number]
    F --> B
    G --> B
    D --> H[End Game]
