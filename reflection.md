# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

1) Anytime I used the enter key to submit a value to guess, it would not work. 
2) If I guessed a number, it would tell me to go higher or lower, but for example, when i guessed 100, it said to go lower, so I guessed 98, it told me to go higher, I guessed 99, and it said to go higher. That was odd. 
3) Secret number kept changing. 
---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
I used a combination of Copilot and ChatGPT for this project. 
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
One example that was correct is when AI suggested to fix the enter button to use to submit a guess. 

- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

I would say that I did not really come across anything misleading. I was able to fix the bugs with the assistance of Ai. 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

One example that helped determine if a bug was really fixed was the one with being able to use the enter button on my keyboard. To test it, I ran the app once more and was successfully able to enter a guess using the enter key.  

Yes, AI did help me design and understand some tests. 
---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

I think the secret number kept changing in the original app because the script kept rerunning and generating a new random number. 

I would explain that streamlit runs a bit differently. It re runs the scriptevery time when a user interacts with it. 


---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

One habit thay i would resuse in the future is writing and running tests to verify that my code works and is running as it should be. 
