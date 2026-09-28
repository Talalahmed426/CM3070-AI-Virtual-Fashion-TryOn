# CM3070 AI Virtual Fashion Try-On

Final-year project code evidence for an AI-powered virtual fashion assistant that orchestrates:

- **IDM-VTON** for virtual clothing try-on
- **Florence-2** for garment understanding and OCR
- **Qwen2.5-1.5B-Instruct** for styling recommendations

## Included submission archive

`CM3070_AI_Virtual_Fashion_Project_Code.zip` contains the two executed notebook HTML exports used for the project:

1. `fyp-midterm-ai-model.html` — IDM-VTON implementation and GPU inference notebook
2. `Florence_2_&_Qwen.html` — Florence-2, Qwen, orchestration, evaluation, and visualisation notebook

## Project architecture

The final system uses Google Colab as the orchestration environment for Florence-2 and Qwen, while IDM-VTON runs as a GPU-backed Gradio service. The models communicate through the Gradio API to form one end-to-end workflow.

## Evaluation

The final evaluation used 10 end-to-end test cases. All 10 completed successfully. The measured mean end-to-end processing time was approximately 112.98 seconds, with an overall manual quality score of 4.26/5.

## Academic project

University of London BSc Computer Science — CM3070 Final Project.
