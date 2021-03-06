# A Kids Guide to Lobe.AI - From Scratch!

[Lobe.AI](https://www.lobe.ai/) is Microsoft's tool to _help you train machine learning models_ in a free, easy-to-use way. We often hear the words "so easy a child could do it!". And we believe Lobe.AI is just that easy. So we created an illustrated guide to Lobe.AI, along with kid-friendly project ideas and tutorials, as a **pAIr-ent programming** introduction to computer vision, image classification and other AI concepts and tools.

In the context of the [AI Kids Kit](https://aka.ms/ai-kids-kit), this project will demonstrate assets and templates to support _conversational_ learning, _pair_ programming, and _parent-child_ project ideas that can help kids see and explore AI concepts in a real world context at home and school.


---

## What can Lobe.AI do?

The current [Lobe.AI](https://www.lobe.ai/) site identifies the ability to train apps to"
 * SENSE colors - in paintings
 * CHECK safety - in mask wearing
 * IDENTIFY plants - detect poisonous ones
 * DETECT gestures - use as play inputs
 * COUNT reps - as your personal trainer
 * REACT to emotions - by detecting experessions

Other example projects include - whale watching (detect marine life in photos), beehive health (monitor hive entrances), baby monitor (detect sleep, crying), smart checkout (recognize produce), fire watch (detect smoke), scientific research (detect organisms in microsocopic images), wildlife behavior (track migrations), equipment analytics (analog gauges), telescopic imagery (celestial) and aerial imagery (earth) analysis to track changes.

---

## What can kids do to experiment?

What are ways in which we can motivate problem-solving and teach AI concepts to kids using Lobe.AI as a sandbox? Here are some sample questions for seeding our conversational transcripts:

 * What is machine learning? (Analogy)
 * What is artificial intelligence? (Examples)
 * What is computer vision? (Technology)
 * What is Lobe.AI? (Tool)
 * How does it work? (Capture - Train - Test - Iterate)
 * How do I capture images?
 * How do I train models?
    - Capturing *enough* images = setup for success (video, carousel, light, occlusion)
    - Capturing *diverse* images = different backgrounds, lighting, angles
    - Capturing *realistic* images = does it reflect user environment?
 * How do I test models?
    - Web App
    - Mobile App
    - Scratch App
 * What did I learn from training/testing?
    - Label selection
    - Classification accuracy
    - Real world usage (successes, failures)
 * How do I improve my project?
    - Labels: are they the right ones?
    - Images: do you need more diversity?
    - Accuracy: is your model trained sufficiently?
    - Usage: can you think of real-world applications that use it?

---

## Project Goals

 * Create an illustrated guide to Lobe.AI for kids and parents to use
 * Create conversational content that helps parents navigate discussions and brainstorm ideas
 * Show sample Lobe.AI projects with default sofware (train it, use Lobe starter web or mobile to test it)
 * Export Lobe.AI models and explore use with other environments (MIT Scratch, App Inventor, Microsoft MakeCode etc.)

This project was conceived during the Microsoft Fix-Hack-Learn event - while all goals may not be met in time for deadline, we hope to show sufficient proof of concept and resources to indicate viability, and continue to follow-up with this beyond the event.

---

## Project Assets

The plan is to provide some subset of these in time for the Fix-Hack-Learn deadline, but continue to add others over time to provide a meaningful template and learning resource for _pAIr-enting_ projects.

| File | Purpose  | 
|:---|:---|
| Transcript | Sample conversational transcript for discussion between parent and child |
| Visuals  | Illustrated tiles for conversation that can be repurposed in many different media |
| Fonts | Specifically, fonts created _by_ (or in collaboration with) kids in the K-8 range. |
| Stories | Some example assets that showcase the above in different contexts |
| Projects | Working projects - with tutorials (steps) and models (outcomes) for others to try |

---

## Project Collaborators

I was specifically interested in getting a _child's eye view_ of this project and am enlisting some help from kids to validate the transcript and help craft relevant stories and projects in a way other kids can relate to. 

The guide will feature two projects up front - both of them done by a 13yo (middle schooler) to showcase real-world ease of using Lobe.AI

 * `Don't Ask Me!` is a project for classifying coffee pods so I wouldn't have to ask him what coffee I was drinking.
 * `Is Candy Good For Me?` is a project for classifying Halloween Candy by name (if single) or as "multiple" (if many in image)

Project specific code and documentation will be kept in a separate folder and linked here for reference.

---

## Project Structure

The purpose is to explore the use of Lobe.AI models in Scratch projects, and create a template/tutorial that allows others to replicate this for new Lobe.AI-friendly use cases. The project structure is as follows:

| File | Purpose  | 
|:---|:---|
| README | This file. Describe what the project does, where things are located, how to run it. |
| docs/ | Folder containing documentation of steps, 1 file per step (with images) |
| docs/static | Folder for hosting static assets (e.g., images used in steps) |
| docs/stories | Completed artifacts that show examples of using project assets or models |
| models | Put assets from the completed Lobe.AI model here |
| training | Put images used to train the model here (if needed)|

## Resources
 * [MIT Scratch](https://scratch.mit.edu/)
 * [Microsoft Lobe.AI](https://www.lobe.ai/)
 * [Running Tensor Flow Models in Scratch](https://dalelane.co.uk/blog/?p=4201#:~:)
 * [Scratch AI Blocks](https://www.media.mit.edu/posts/ai-blocks/)
 * [PRG AI Blocks](https://npnlab-vn.github.io/scratch3/main/)
 * [PRG AI Boilerplate](https://github.com/mitmedialab/prg-extension-boilerplate)
