# NLP-Corpora
---

This is a list of NLP corpora. You can report a new corpus at the Issue page.

- 🤖🤖 Machine-toMachine conversations which were synthetically generated.
- 👦🧒 Human-to-Human conversations. (including dialogs by crowd sourcing workers).
- 👦🤖 Human-to-Machine (dialog systems) conversations.
- 🧙‍♂️ The data was collected using a Wizard-of-Oz scheme.

### Dialog (Task-oriented)
- [The (6) dialog bAbI tasks, facebook, 2016.](https://research.fb.com/downloads/babi/) 👦🤖		
The set of six tasks for testing e2e task-oriented dialogs systems for restaurant reservation. Task1-5 are synthetically generated data while Task6 is created from human-to-computer dialogs (DSTC2).		
For each task, there are 1000 dialogs for training, 1000 for development and 1000 for testing. 

	```:Task 6 example
	U: <SILENCE>	Hello , welcome to the Cambridge restaurant system?
	S; You can ask for restaurants by area , price range or food type . How may I help you?
	U: cheap restaurant that serves german food
	S: 	I'm sorry but there is no restaurant serving german food
	U: what about asian oriental foo
	S: You are looking for a german restaurant right?
	U: asian
	S: Let me confirm , You are looking for a restaurant in the cheap price range right?
	```

- [babi plus, 2017.](https://arxiv.org/abs/1709.07840) 🤖🤖    
Synthetically added disfluency to bAbI-Task 1. And [their code](https://github.com/ishalyminov/memn2n) is also available.

	```:example
	sys: hello what can I help you with today?
	usr: I’d like to book a uhm yeah I’d like to book a
		 table in a expensive price range no sorry in a
		 cheap price range
	sys: I’m on it. Any preference on a type of cuisine?
	usr: with indian food no sorry with spanish food
	```

- [A New Multi-Turn, Multi-Domain, Task-Oriented Dialogue Dataset, Stanford, 2017.](https://nlp.stanford.edu/blog/a-new-multi-turn-multi-domain-task-oriented-dialogue-dataset/)👦👦🧙‍♂️		
Three domains (weather/calendar/poi) dialogs of a car assistant.	
3,031 multi-turn dialogues are created in manner of Wizard-of-Oz.

	```:example
		DRIVER:	I need to find the time and parties attending my optometrist appointment. 
		CAR	:	I have 3 appointments scheduled, with Alex, your sister, and Jeff. Which are you referring to?
		DRIVER:	I want to know about the one that Alex is joining me at.
		CAR	:	That optometrist appointment is at 4 pm.
		DRIVER:	Thanks.
		CAR	:	No problem.
	```

- [DSTC 1-6](https://www.microsoft.com/en-us/research/event/dialog-state-tracking-challenge/)👦🤖	
  Dialog State Tracking Challenge is research community tasks. The link presents each DSTC task.

### Dialog (Others)

- [The Ubuntu Dialogue Corpus, 2015. [Human2Human]](https://github.com/rkadlec/ubuntu-ranking-dataset-creator)🧒🧒    
 Human to Human dialogs in Ubuntu boards.    
1 million multi-turn dialogues, with a total of over 7 million utterances and 100 million words. 

- [DailyDialog: A Manually Labelled Multi-turn Dialogue Dataset, 2017. [Human2Human]](http://yanran.li/dailydialog)👦🧒    
The dialogs are our daily communication way and cover various topics about our daily life. The dataset contains 13,118 multi-turn dialogs.    

	```:example
	A: I’m worried about something.
	B: What’s that?
	A: Well, I have to drive to school for a meeting this morning, 
	   and I’m going to end up getting stuck in rush-hour traffic.
	B: That’s annoying, but nothing to worry about.
	   Just breathe deeply when you feel yourself getting upset.
	```

### Question Answering

- [SQuAD 2.0, 2018](https://rajpurkar.github.io/SQuAD-explorer/)     

	> SQuAD2.0 combines the 100,000 questions in SQuAD1.1 with over 50,000 new, unanswerable questions written adversarially by crowdworkers to look similar to answerable ones. 


### Translation

🚧

### Sentiment Analysis

🚧

## References
- [A Survey of Available Corpora for Building Data-Driven Dialogue Systems](https://breakend.github.io/DialogDatasets/)
- [Natural Language Processing Corpora, NLP for Hackers](https://nlpforhackers.io/corpora/)
