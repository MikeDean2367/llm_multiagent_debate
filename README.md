# Improving Factuality and Reasoning in Language Models through Multiagent Debate

### [Project Page](https://composable-models.github.io/llm_debate/) | [Paper](https://composable-models.github.io/llm_debate/llm_debate.pdf) 

[Yilun Du](https://yilundu.github.io/),
[Shuang Li](https://people.csail.mit.edu/lishuang/),
[Antonio Torralba](https://groups.csail.mit.edu/vision/torralbalab),
[Joshua B. Tenenbaum](https://scholar.google.com/citations?user=rRJ9wTJMUB8C&hl=en),
[Igor Mordatch](https://scholar.google.com/citations?user=Vzr1RukAAAAJ&hl=en)

This is a preliminary implementation of the paper "Improving Factuality and Reasoning in Language Models through Multiagent Debate". More tasks and settings will be released soon


## Running experiments

The code for running arithmetic, GSM, biographies, and MMLU tasks may be found in the following subfolders

* ./math/ contains code for running math
* ./gsm/ contains code for running gsm
* ./biography/ contains code for running biographies
* ./mmlu/ contains code for running mmlu results.

**Math:**

To generate and evaluated answer for Math problems through multiagent debate, cd into the math directory and run:
	`python gen_math.py`
	
**Grade School Math:**

To generate answers for Grade School Math problems through multiagent debate, cd into the gsm directory and run:
	`python gen_gsm.py`

To evaluate the generated results of Grade School Math problems:
	`python eval_gsm.py`


**Biography:**

To generate answers for Biography problems through multiagent debate, cd into the biography directory and run:
	`python gen_conversation.py`

To evaluate the generated results for Biography problems:
	`python /eval_conversation.py`
	
**MMLU:**

To generate answers for MMLU through multiagent debate, cd into the MMLU directory and run:
	`python gen_mmlu.py`

To evaluate the generated results of MMLU:
	`python eval_mmlu.py`
