# Statistical Natural Language Processing: Project
This repository contains the project for the course ELEC-E5550 - Statistical Natural Language Processing at Aalto University, Finland.
The file `report.pdf` contains the project report which presents the problem and the project results.

## Introduction

Our proposal for the project of the SNLP course is that of a two-part movie generator. On one
hand, we will be using a pre-trained GPT-2 architecture to fine-tune it using datasets containing movie
plot descriptions in order to obtain newly generated movie descriptions depending on word input into
the model. On the other hand, we will go one step further by using an additional architecture trained
for text summarizing to obtain movie titles based on what our description generator architecture
outputs.


## Examples of generations

**Title: Moonwalkers**

```
It is the year 2077 and space exploration has revived human interest in the moon. While
mankind is busy building domed cities on the moon, a small mining colony is discovered
on the other side of the galaxy.
```

---

**Title: Dead Zone**
```
After a zombie outbreak in Las Vegas, a group of survivors must cross the desert in
an attempt to stay alive. Their only other contact is a mysterious radio tower that
broadcasts a constant stream of cryptic messages.
```

---
**Title: Zentraedi**
```

Humanity has mastered interplanetary spaceflight and begun to explore the galaxy.
However, humanity’s technological prowess has also brought new threats into the solar
system, including a dangerous race of giant bugs. To combat these dangerous creatures,
the government constructs the giant "Zentraedi" robots.
```
---
**Title: The Halsey Murders**
```
After a series of harrowing murders in which a gang leader is savagely murdered and
a local beauty is abducted, Inspector Jim Halsey finds evidence that points to a Mafia
boss who has infiltrated his department - but he risks his own life by falling under the
Mafia’s tyrannical influence.
```



## Use
Moreover, the following Google Colab notebook is available where you can use the fine-tuned models
to generate new descriptions and titles (it must be noted that the models can take a while to load):
https://colab.research.google.com/drive/1M5ffWIso0FAnHlbqRvW0ow5aZAq091fn?usp=sharing.

If you want to try it locally, the repository contains the code `MovieGen.ipynb`