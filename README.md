# Hippo the AI Radiology Assistant

## Run index.htm file on localhost (see [StackOverflow](https://stackoverflow.com/questions/38497334/how-to-run-html-file-on-localhost))

You can run your file in http-server.
- Have Node.js installed in your system.
- In CMD, run the command `npm install http-server -g`
- Navigate to the specific path of your file folder in CMD and run the command http-server
- Go to your browser and type `localhost:8080`. 

---

This repo is based on [Chester the AI Radiology assistant](https://github.com/mlmed/chester-xray). Thank you to the authors for their great work!

In addition, this repo should include:
- **Upgraded website UI**
  - New website layout: scan with annotation + diagnosis on the right, chat interface on the left (with chat history ideally)
  - Upload button of image studies (in medical center analogy this would happen automatically)
  - Download button for generated radiology report 
- **Chatbot**
  - *Input:* Text assessment of medical scan (already implemented tool predicts 18 different radiological findings with the prediction confidence and risk)  + (optional user queries about diagnosis) 
  - *Output:* Non-expert explanation of the diagnosis + a follow-up recommendation (primarily whether patient needs to see a doctor or fix next appointment for check up)
  - *Models:* Meditron, LLama?
- **Radiology report generator**
  - Including annotated image, in universal format the findings found by algorithms + recommendation 

NOT FOR MEDICAL USE.
