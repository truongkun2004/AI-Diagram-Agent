# AI Diagram Agent

AI Diagram Agent is an experimental feature built for the mobile note-taking application Noteen. The feature integrates a multi-agent architecture into the app, allowing users to interact with an AI assistant through natural language to generate, edit, and update diagrams directly on a collaborative whiteboard in real time.

The agent is capable of understanding user requests, answering questions, and continuously updating diagram structures based on ongoing interactions.

This feature has not been officially published in the production version of the app yet. It was initially developed as part of a graduation thesis project.

## Noteen App

- Google Play: https://play.google.com/store/apps/details?id=com.devkun.noteen&hl=en-US&ah=OlZPkTq5uYo8ZNTbk0T-LqD6kvc

## Demo Screenshots

<p align="center">
  <img src="./assets/screenshot-01.jpg" width="24%" />
  <img src="./assets/screenshot-02.jpg" width="24%" />
  <img src="./assets/screenshot-03.jpg" width="24%" />
  <img src="./assets/screenshot-04.jpg" width="24%" />
</p>

<p align="center">
  <img src="./assets/screenshot-05.jpg" width="24%" />
  <img src="./assets/screenshot-06.jpg" width="24%" />
  <img src="./assets/screenshot-07.jpg" width="24%" />
  <img src="./assets/screenshot-08.jpg" width="24%" />
</p>

## Video Demo

https://github.com/user-attachments/assets/56efc747-9c1c-4fa8-a15b-d1fdf1d28d32

## Benchmark

The evaluation pipeline was fully automated and internally developed for testing the multi-agent system behavior and diagram generation workflow.

- Total conversations tested: 50
- Total QA pairs: 141
- Candidate model: GPT-5.4 mini

| Metric                              | Result    |
| ----------------------------------- | --------- |
| Good Routing                        | 96.45%    |
| Good Answer                         | 91.49%    |
| Diagram Schema Validity             | 100.0%    |
| Tool Calling Correctness            | 93.24%    |
| Unexpected Tool Calling Rate        | 0.0%      |
| Average TTFT (Chat Profiles 0+3)    | 2113 ms   |
| Average TTFT (Diagram Profiles 1+2) | 3249 ms   |
| Structured Data Quality             | 8.74 / 10 |
