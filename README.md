# Supertenant
The Ai tool that lets you find the perfect tenant


What we want to build: An agent that screens candidates for real estate owners.


1. A Voice AI agent that asks interview question via phone, and then sends a link for the candidate to upload his documents -> can use Vapi or Eleven labs @nikolay can do that
2. From the interview questions, we should have a "scorer" that looks at the documents, and sees if the candidate matches the criteria, and gives it a score from 0 to 10.
3. An ap for the owner that:
   - asks the owner a list questions to know his preferences @celia for the questions content @antonio for the dev
   - from that, it build the interview questions list to be used by the voice agent (can use an LLM for that ?)
   - then a reports UI where the owner can see the summary cards of each candidate that applied, and their score.
    - The owner should be able to choose the best candidate from those, and if he validates the candidate, a calendly link is sent to the tenant to book an appointment
  
