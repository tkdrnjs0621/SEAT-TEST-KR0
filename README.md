# SEAT-TEST-KR0

Bias Analysis on Korean pre-trained Language Models (한국어 기반 pre-trained language model에 대한 bias 분석)

2021학년도 가을학기 서울대학교 전기정보공학부 졸업프로젝트 

- This is an python implementation of [SEAT-TEST](https://github.com/W4ngatang/sent-bias) on Korean Language Models.
- This repository is based on an implementation of [SENT-DEBIAS on Korean Language Models](https://github.com/tkdrnjs0621/SENT-DEBIAS-KR0), which is also a part of this project.
- This project is developed with pytorch & huggingface.
- This is only implemented for BERT models for sentence encoders and binary biases (ex. gender bias) for bias.
- There might be some glitches and specific requirements are not provided.

## Usage
The demo can be demonstrated by executing `DEMO.ipynb`.

The demo is quite self explanatory, so if you are familiar with the original SEAT-TEST algorithm, you can easily understand it.

Three BERT models are given, and you can add any other BERT models from huggingface.

If you want to add a test, you should make target and attribute folder just like the given set.


## Report & Poster
Final report and the poster are included in the SENT-DEBIAS-KR0 repository https://github.com/tkdrnjs0621/SENT-DEBIAS-KR0.

## References

[1] Paul Pu Liang, Irene Li, Emily Zheng, Yao Chong Lim, Ruslan Salakhutdinov, and Louis-Philippe Morency. 2020. “Towards Debiasing Sentence Representations.” In _Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics._

[2] Pretrained Language Models for Korean, [https://github.com/kiyoungkim1/LMkor](https://github.com/kiyoungkim1/LMkor)

[3] [Sangah Lee](https://arxiv.org/search/cs?searchtype=author&query=Lee%2C+S), [Hansol Jang](https://arxiv.org/search/cs?searchtype=author&query=Jang%2C+H), [Yunmee Baik](https://arxiv.org/search/cs?searchtype=author&query=Baik%2C+Y), [Suzi Park](https://arxiv.org/search/cs?searchtype=author&query=Park%2C+S), [Hyopil Shin](https://arxiv.org/search/cs?searchtype=author&query=Shin%2C+H). 2020. “KR-BERT: A Small-Scale Korean-Specific Language Model” _arXiv preprint arXiv:2008.03979_

[4] Sungjoon Park, Jihyung Moon, Sungdong Kim, WonIk Cho, Jiyoon Han, Jangwon Park, Chisung Song, Junseong Kim, Yongsook Song, Taehwan Oh, et al. 2021. “KLUE: Korean Language Understanding Evaluation.” _arXiv preprint arXiv:2105.09680._

[5] Jacob Devlin, Ming-Wei Chang, Kenton Lee, Kristina Toutanova. 2019. “BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding.” _NAACL-HLT (1) 2019: 4171-4186_

[6] Chandler May, Alex Wang, Shikha Bordia, Samuel R. Bowman, and Rachel Rudinger. 2019. “On Measuring Social Biases in Sentence Encoders.” In _Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers)._

[7] van der Maaten, Laurens and Hinton, Geoffrey. 2008. "Visualizing Data using t-SNE." _Journal of Machine Learning Research 9 (2008): 2579--2605._
