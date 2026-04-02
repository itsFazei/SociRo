# SociRo - software overview

![unslpashhhhhh](https://images.unsplash.com/photo-1518933165971-611dbc9c412d?q=80&w=1332&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
Photo by <a href="https://unsplash.com/@mr_vero?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Irvan Smith</a> on <a href="https://unsplash.com/photos/turned-on-computer-monitor-displaying-coding-application-cwqG1N1AtI0?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>

> last updated 22th of march 2026

## What is it?

SociRo is the software related to project 1 of the OsloMet European Project Semester. The project is a participatory design to make a social robot for hospitalized children. This software will be tied to the electronics which will be provided by our electronical engineer.

## Planned Features

- [ ] Basic greetings and gestures

- [ ] An old soft voice of a famous storyteller (or norwegian storyteller)

- [ ] A way to control the arms so it can be used to hug the user

- [ ] A music player
    - [ ] Can be manipulated through dashboard with emotion buttons
    - [ ] Playlist so user can decide by themselves

- [ ] A way to mimic breathing for when the user desires to have a breathing exercise

> Possible features, influenced by design department

- [ ] A way to regulate warmth on the pads

## Technologies

Because we are planning on integrating LLM's for storytelling and basic gestures we will be using **Python** for the core of this project.

But if there is time we might replace the smaller code chunks in python that are in charge of minor movements with **Rust**. But this is meant as an extra challenge for the **Software Engineer**.

## Dependencies

- For general robotics like movement, we will be using <a href="https://robotframework.org/">Robot Framework</a>

- For an old voice we shall be using the <a href="https://pypi.org/project/transformers/">Transformers</a> to try out multiple voice models, if there are none we shall be using the same library to train a custom model

- We will be using <a href="https://pypi.org/project/playsound3/">Playsound3</a> to play music while testing the robot

## LLM's / other models

- <a href="https://huggingface.co/akhbar/F5_Norwegian">F5_Norwegian Text To Speech model</a>

- <a href="https://huggingface.co/boltuix/bert-emotion">Emotion detection models</a>
