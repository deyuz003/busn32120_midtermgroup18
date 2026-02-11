# Open Payments Analysis

This repository contains analysis of CMS Open Payments data for BUSN 32120 Midterm.

- Team Midterm 18: Quinn Gan, Ravi Reddy, Deyu Zhang
- Midterm_Project_Group_18.ipynb: the code used for midterm project is in this file.

We used generative AI as a coding and debugging assistant, consistent with the course policy allowing AI support for programming tasks. Specifically, we relied on AI to help translate analytical ideas into working Python code, diagnose errors, and refactor code when our initial implementations caused performance or kernel stability issues.

In particular, AI assistance was used to (1) suggest pandas patterns for aggregation and visualization (e.g., appropriate uses of groupby, agg, and sorting operations), (2) debug kernel crashes related to loading a very large CSV file by proposing a streaming-based workaround using the requests library, and (3) help structure exploratory analyses such as concentration metrics and log-scaled visualizations. All AI-suggested code was reviewed, modified where necessary, and fully explained by team members to ensure we understood how it worked and why it was appropriate for the task.

Importantly, all analytical decisions — including variable selection, aggregation logic, thresholds (e.g., the 90% manufacturer concentration cutoff), and interpretation of results — were made by the team. The final notebook reflects our own understanding of the code and methods, as demonstrated in the accompanying video explanation where each team member explains a substantial portion of the implementation.

Video Link: https://drive.google.com/file/d/1SFoMTdTRI_dRG5WtMwG9-BIgJ6beyAK6/view?usp=sharing