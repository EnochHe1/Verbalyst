# Verbalyst

Created with Pancraes and sai3000pro for Ignition Hacks v.3 (2023), where we won the "Best Web Award" for our project. <br /> 
Big shoutout to my awesome teammates 🥳 !

## Inspiration

When the quarantine was introduced, many individuals, including us, were starved of social interactions. It was difficult transitioning from text-only interactions to fully-fledged conversations after the pandemic, let alone public speeches and presentations. Although enough time has passed to mend our abilities to speak to others and have fruitful conversations, speeches in front of large groups still stand as challenges that we'd rather not face. Knowing that the prevalence of social anxiety is increasing drastically in our society, we decided to tackle the issue that we and many others face with our app, Verbalyst.

## What It Does

Verbalyst allows users to rehearse and record their speeches with both audio and camera an unlimited amount of times. It analyzes the recording to determine how many stutters the user has stated in the duration of their speech. This project encourages more practice and familiarity with speaking, aiding those of all ages as speaking skills are universal; they're needed in the industry, in classrooms, in friend groups, you name it. Users can track their speaking skill progress through the STATS page and see their growth right in front of their eyes, and for individuals who are already confident in their speaking capabilities, Verbalyst offers a fun challenge in the form of a tongue twister generator. Individuals can record their tongue twisters and catch themselves saying filler words and other stutters, which can help eliminate poor habits.

## How It's Built

- HTML
- CSS
- TailwindCSS
- JavaScript
- Python
- Flask
- AssemblyAI
-Google Vertex AI

We used TailwindCSS, vanilla HTML and vanilla CSS to create all of the website pages. We used JavasSript for our recording software and used Flask to connect our front end to our back end. Our back end was created through Python and we used the Google vertexai API to have an AI-generated analysis of the speech that the user inputted, and we used the assemblyai API to have an AI do speech to text on the inputted mp4 file from the user.

## Challenges Faced During Hackathon

Starting 26 hours (8 pm EST) behind due to scheduling issues and personal conflicts posed a great challenge. Despite this major setback, we adapted swiftly, optimizing our time to make up for lost hours. <br />

Although the end product of our code had been less than we anticipated, we were able to have both of our AI components working individually through our console. It was creating a cohesive web application with proper functionality within our severe time crunch that proved to be the problem. Despite this, we still tried our best to implement all of the components we envisioned yesterday, and we believe that we did the best we could with our time.

## What we learned

The entire project was essentially a learning journey for us; we learned so many things for it to have the functionality it has now. For starters, creating the recording feature and being able to receive and store user audio input so that it could be used for the AssemblyAI speech-to-text transcription model was completely new. Although we were unable to put the user audio input and the AssemblyAI speech-to-text model together with Flask, we still learned how to use AssemblyAI and convert premade audio input into text. Even the markup framework we utilized for this project was new (TailwindCSS), so it's safe to say we put a lot of time and effort into learning new things.




