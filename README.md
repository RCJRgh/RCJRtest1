flowchart TD
    A[Determine Eligibility] --> B{Are you eligible?}
    B -- No --> X[Cannot proceed]
    B -- Yes --> C[Enrol at a Driving Centre]
    C --> D[Pass the Basic Theory Test (BTT)]
    D --> E{Did you pass BTT?}
    E -- No --> D
    E -- Yes --> F[Apply for Provisional Driving Licence (PDL)]
    F --> G[Attend Practical Driving Lessons]
    G --> H[Complete 20-25 lessons with school instructor]
    H --> I[Learn: Basic Skills, Defensive Driving, Circuit, On-road]
