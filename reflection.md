# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

When I first ran the code, everything felt normal. However, when I was playing the game I notice there were somethings that were odd. 
1. The hint of the game keep saying the oppsite, like when it was lower, it suppose to be higher
2. After getting the correct response, and after clicking new game, the guess number button won't work.
3. After giving the wrong answer for all the attempt, the new game button won't work.

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
Claude
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
One sugesstion that was correct was that in the check_guess, it correctly fix the mistake of fixing the inequalities.
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).
For exxample in history, it sugges that invaild guess shouldn't be in history. It suggested something that is a bad idea for game itself although there was nothing wrong with the idea.
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
I let the AI design a pytest for me to test it.
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
I ran pytest that claude made and I also saw the code and see if it was right. I also tested on the app to see if it was correct.
- Did AI help you design or understand any tests? How?
Yes, it made it easier for me to run test cases and suggested idea on how it can be fixed.

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
I don't remember it kept changing or the secret number didn't change for me.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
If you change something in the code, it will have to restart the python script. It also contain the ability to have varibles that you choose to keep after reruns.
- What change did you make that finally gave the game a stable secret number?
I don't remember it kept changing or the secret number didn't change for me.
---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
Alway put the AI edit in plan mode just in case you don't want certain changes.
- What is one thing you would do differently next time you work with AI on a coding task?
Use context variables so the AI can spectify look at certain things.
- In one or two sentences, describe how this project changed the way you think about AI generated code.
This project changed the way you think about AI generated code by learning that you shouldn't let the AI change the whole code at once but to do it part by part.