# Irony-and-Sarcasm-detection-in-Arabic-tweets
This repo represents model developed for Irony and sentiment detection in Arabic tweets  in WANLP shared tasks on sarcasm and sentiment detection in Arabic

## Overview
This github is an implementation for accepted manuscript titled `WANLP 2021 Shared Task: Towards Irony and Sentiment detection in Arabic tweets using Multi-headed-LSTM-CNN-GRU and MARBERT`.

[Publised paper](https://aclanthology.org/2021.wanlp-1.37/).



If you find code/work useful, please consider citing
```
@inproceedings{abdel-salam-2021-wanlp,
    title = "{WANLP} 2021 Shared-Task: Towards Irony and Sentiment Detection in {A}rabic Tweets using Multi-headed-{LSTM}-{CNN}-{GRU} and {M}a{RBERT}",
    author = "Abdel-Salam, Reem",
    booktitle = "Proceedings of the Sixth Arabic Natural Language Processing Workshop",
    month = apr,
    year = "2021",
    address = "Kyiv, Ukraine (Virtual)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.wanlp-1.37",
    pages = "306--311",
    abstract = "Irony and Sentiment detection is important to understand people{'}s behavior and thoughts. Thus it has become a popular task in natural language processing (NLP). This paper presents results and main findings in WANLP 2021 shared tasks one and two. The task was based on the ArSarcasm-v2 dataset (Abu Farha et al., 2021). In this paper, we describe our system Multi-headed-LSTM-CNN-GRU and also MARBERT (Abdul-Mageed et al., 2021) submitted for the shared task, ranked 10 out of 27 in shared task one achieving 0.5662 F1-Sarcasm and ranked 3 out of 22 in shared task two achieving 0.7321 F1-PN under CodaLab username {``}rematchka{''}. We experimented with various models and the two best performing models are a Multi-headed CNN-LSTM-GRU in which we used prepossessed text and emoji presented from tweets and MARBERT.",
}
```


Irony and Sentiment detection is important to understand people's behavior and thoughts. Thus it has become a popular task in natural language processing (NLP). This paper presents results and main findings in WANLP 2021 shared tasks one and two. The task was based on the ArSarcasm-v2 dataset . In this paper, we describe our system Multi-headed-LSTM-CNN-GRU and also MARBERT  submitted for the shared task,  ranked ``10`` out of ``27`` in ``shared task`` one achieving ``0.5662`` F1-Sarcasm and ranked ``3`` out of ``22`` in ``shared task two`` achieving ``0.7321`` F1-PN under CodaLab username ``rematchka``. We experimented with various models and the two best performing models are a Multi-headed CNN-LSTM-GRU in which we used prepossessed text and emoji presented from tweets and MARBERT.


## Results
1. `Official Results from website shared task 1`
![Alt text](Results/shared-task-1-official-results.png?raw=true "Title")
2. `Non-Official Results from website shared task 1`
![Alt text](Results/shared-task-1-non-official.png?raw=true "Title")
3. `Official Results from website shared task 2`
![Alt text](Results/shared-task-2-official-results.png?raw=true "Title")
4. `Non-Official Results from website shared task 2`
![Alt text](Results/shared-task-2-non-official.png?raw=true "Title")
