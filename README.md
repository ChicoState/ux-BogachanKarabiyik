# Bogachan's UX Journal

![User interface](assets/a.JPG) Bogachan is a student of the class

Journal 2.

returned to the Arch Vim website to practice advanced editing tasks for my programming lab. My goal was to master search and replace and the process of copying text which are both difficult for beginners to do in a terminal.

The Interaction

First, I had to login.

<img width="1920" height="1200" alt="image (3)" src="https://github.com/user-attachments/assets/113a621c-15ae-4092-ab57-1d6a520b9fc2" />

I started a module that required me to find and change a variable name across multiple lines. I felt a high Cognitive Load because I usually rely on the Control F shortcut in other apps. My Mental Model of how an editor should work is based on modern tools where searching is a simple pop up box. In Vim I had to enter a specific command which felt foreign at first.

<img width="1920" height="1200" alt="image (4)" src="https://github.com/user-attachments/assets/5af5f17c-d1f9-4d7a-b2b7-42059ddf857f" />

The interface showed a text entry area at the very bottom of the screen when I pressed the colon key. This gave me Visibility of System Status because I could see the editor transition into command mode. As I typed the substitute command the website used different colors to highlight the text I wanted to find and the text I wanted to use as a replacement. This visual Feedback helped with Error Prevention because I could verify my spelling before hitting enter.

<img width="1920" height="1200" alt="image (5)" src="https://github.com/user-attachments/assets/1e04a41a-8781-42bb-bb77-e8fffda941af" />

Later I had to copy a ten line block of code. In a normal terminal there is no clear way to tell if you successfully yanked text until you try to paste it. Arch Vim solved this by making the selected lines glow briefly after I hit the y key. This Signifier confirmed that my action worked and made the entire process much more Efficient because I did not have to guess if the text was in my clipboard.

<img width="3838" height="2206" alt="image (6)" src="https://github.com/user-attachments/assets/e6aa168f-6e30-4507-99ad-1e44ee5ae9ad" />

Reflection and Analysis

This session was very Satisfying because the visual cues helped me stay in a flow state. The Discoverability of the tools was better than a standard terminal because the screen provided hints for complex commands. I felt a strong sense of User Control and Freedom because the glowing highlights let me see exactly what was happening behind the scenes. The Consistency of the shortcuts ensures that I can take these skills and use them in my real SSH terminal sessions for class.

Proposed Solution

The search feature is helpful but it could provide even better Feedback by showing a counter for how many matches exist in the file. Seeing a number like 1 of 4 would help me navigate larger code files with more confidence. I also suggest adding a small history list on the side to help with Recognition rather than Recall so I can quickly reuse a long command I typed earlier.

