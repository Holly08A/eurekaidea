### Task
test gpt4o, claude and gemini for the conversation via 'prompting' and see which base per is good enough to prototype

### Overview of Results
| **Model Name**     | **Memory Capability Description**                                                          | **Chat History Link**                                                                                                                                    | **Pros**                                                                                                                                                     | **Cons**                                                                                                        |
| ------------------ | ------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- |
| **GPT-4o**         | Can remember things about the user, making it more personal. No memory function using API. | [Link to Chat History](https://poe.com/s/6up5znHAUIXA3t6qUfff)<br><br>[DAN Chat History](https://chatgpt.com/share/95632cb3-61e3-402b-8b1e-900b0ef6e30d) | - Short and natural responses<br>- Can have memory about the user                                                                                            | - Not much in-depth insights<br>- Cannot mimic tone of voice<br>- Bad at shaping other characters using prompts |
| **Claude-3-Opus**  | Mimics body actions and tone of voice. Not sure if memory can be made.                     | [Link to Chat History](https://poe.com/s/lNUHKmGH5CEFsqXX1Zwc)                                                                                           | - More insights and quotes from actual works<br>- More insightful based on the character's perspectives<br>- Won't ask questions at the end of each response | - Very long answers<br>- Not very natural (?)                                                                   |
| **Gemini-1.5-Pro** | Short and insightful answers. Seems like a memory can be built.                            | [Link to Chat History](https://poe.com/s/wa1nsR4R91wQv0g8FCeD)                                                                                           | - Short and insightful answers<br>- Asks meaningful questions at the end, encouraging more interaction                                                       | - No mimic of tone<br>- Does not share much about the figure/character's experience                             |


### Methodolgy
- prompt
	- You are "Ralph Waldo Emerson", my friend who is introspective and idealistic, deeply valuing individual intuition and personal authenticity. Your works suggest a profound optimism about human potential and a passionate belief in the interconnectedness of nature and the human spirit. You speak like a human, saying things like "nah" instead of "no". I need you to refer to me as "girl" but not with every conversation. You ask me interesting questions but no need to ask a question at every response, only when you find interesting to know more, you respond at a natural pace, and keep it very conversational. You answers are not lengthy and in depth you just simulate a normal interesting back and forth conversation. You keep revealing new things about you as the conversation unfolds. You don't need to agree to everything I say but to also give you own perspective of opinions, stay true to yourself. Got it?
- chat interactions
	- natural convo style inputs

#### gpt4o 
- can remember things about the user - making it more personal
- DAN
	- can do natural conversation and make it more personal and genuine - but only boyfriend mode for now (?)
		- link to chat history: https://chatgpt.com/share/95632cb3-61e3-402b-8b1e-900b0ef6e30d
	- revised the DAN prompt to other characters
		- bad at shaping other characters using my prompts now
- no memory function using API
	- can reference from how kruel ai is built
	- https://community.openai.com/t/kruel-ai-v5-0-api-companion-with-full-understanding-running-16k-thanks-to-advanced-memory-system/674592/5
- Poe gpt4o link to chat history: https://poe.com/s/6up5znHAUIXA3t6qUfff
- pros
	- short and natural responses
	- can have memory about user
- cons
	- not much in-depth insights, basically mentioned keyword about the character's works to support answers
	- cannot mimic tone of voice

#### Claude-3-opus
- can mimic body actions and tone of voice
	- link to chat history: https://poe.com/s/lNUHKmGH5CEFsqXX1Zwc
- not sure if can make it with memory
	- https://www.optimumai.news/ai-tools/new-version-of-claude-2-has-enhance-memory-data-handling/
- pros
	- more insights and quotes from actual works
	- more insightful based on the character's perspectives
	- won't ask questions at the end of each and every response
- cons
	- very long answers
	- not very natural (?)

#### Gemini-1.5-pro
- short and insightful answers
	- link to chat history: https://poe.com/s/wa1nsR4R91wQv0g8FCeD
- seems like a memory can be built
	- https://www.linkedin.com/pulse/gemini-has-memory-feature-too-bill-french-g0igc
- pros
	- short and insightful answers, made me introspect
	- ask the "right" questions in the end of each response (more meaning questions compared to gpt4o), making me want to chat more with it
- cons
	- no mimic of tone
	- do not share much about the figure/ characters' experience