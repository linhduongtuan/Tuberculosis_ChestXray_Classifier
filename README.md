# Tuberculosis_ChestXray_Classifier

* Tuberculosis (TB) is a communicable disease that is a major cause of ill health, one of the top 10 causes of death worldwide and the leading cause of death from a single infectious agent (ranking above HIV/AIDS). It is caused by the bacillus Mycobacterium tuberculosis, which is spread when people who are sick with TB expel bacteria into the air; for example, by coughing. It typically affects the lungs (pulmonary TB) but can also affect other sites (extrapulmonary TB). About a quarter of the world’s population is infected with M. tuberculosis and thus at risk of developing TB disease.
* Globally, an estimated 10.0 million (range, 9.0–11.1 million) people fell ill with TB in 2018, a number that has been relatively stable in recent years. The burden of disease varies enormously among countries, from fewer than five to more than 500 new cases per 100 000 population per year, with the global average being around 130. There were an estimated 1.2 million (range, 1.1–1.3 million) TB deaths among HIV-negative people in 2018 (a 27% reduction from 1.7 million in 2000), and an additional 251 000 deaths (range, 223 000–281 000) among HIVpositive people (a 60% reduction from 620 000 in 2000). 
* Geographically, most TB cases in 2018 were in the WHO regions of South-East Asia (44%), Africa (24%) and the Western Pacific (18%), with smaller percentages in the Eastern Mediterranean (8%), the Americas (3%) and Europe (3%). Eight countries accounted for two thirds of the global total: India (27%), China (9%), Indonesia (8%), the Philippines (6%), Pakistan (6%), Nigeria (4%), Bangladesh (4%) and South Africa (3%). These and 22 other countries in WHO’s list of 30 high TB burden countries accounted for 87% of the world’s cases.
* Drug-resistant TB continues to be a public health threat. In 2018, there were about half a million new cases of rifampicin-resistant TB (of which 78% had multidrugresistant TB). The three countries with the largest share of the global burden were India (27%), China (14%) and the Russian Federation (9%). Globally, 3.4% of new TB cases and 18% of previously treated cases had multidrugresistant TB or rifampicin-resistant TB (MDR/RR-TB), with the highest proportions (>50% in previously treated cases) in countries of the former Soviet Union. 
Citation Source: https://apps.who.int/iris/bitstream/handle/10665/329368/9789241565714-eng.pdf?ua=1

* The advent of new powerful hardware and software techniques has triggered attempts to develop computer-aided diagnostic systems for TB detection. Hence, we use three public datasets for building the AI approach. Montgomery County X-ray Set & Shenzhen Hospital X-ray Set / China data set can be found at here [https://openi.nlm.nih.gov/faq#faq-tb-coll] or at Kaggle site: [https://www.kaggle.com/kmader/pulmonary-chest-xray-abnormalities] and original paper is here [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4256233/]; and the third one can be downloaded from here [https://github.com/frapa/tbcnn/tree/master/belarus], and here are a paper [https://www.nature.com/articles/s41598-019-42557-4] and a source code [https://github.com/frapa/tbcnn].

#### Therefore, the aim of the project is to build convolutional neural networks for a classification task Chest X ray images of patients acquired Tuberculosis versus of healthy subjects.

#### In this study we used all mixed datasets, and then split them into training/validation/testing parts with ratio 80%:10%:10%

#### The models and hyperparameters are performed for the project which are referenced following our previous study: Deep Learning for Automated Recognition of Covid-19 from Chest X-ray Images at here [https://www.medrxiv.org/content/10.1101/2020.08.13.20173997v1] and github site at here: [https://github.com/linhduongtuan/Covid-19_Xray_Classifier]

#### The study results are shown using Confusion matrices and Receiver Operation Characteristic (ROC). These are calculated by inferencing on testing set. You can see on Confusion Matrices and ROC folders.

## Citing
### Please cite our paper: [Detection of tuberculosis from chest X-ray images: Boosting the performance with vision transformer and transfer learning](https://www.sciencedirect.com/science/article/pii/S0957417421009295?fbclid=IwAR3MK1Y-IQL2HD25E68fCUs3NxGsaHK3qJAtWzX_MVF9hRWe8ZcdX-5bOUQ#b0150)


### BibTeX

```bibtex
@article{duong2021detection,
  title={Detection of Tuberculosis from Chest X-ray Images: Boosting the Performance with Vision Transformer and Transfer Learning},
  author={Duong, Linh T and Le, Nhi H and Tran, Toan B and Ngo, Vuong M and Nguyen, Phuong T},
  journal={Expert Systems with Applications},
  pages={115519},
  year={2021},
  publisher={Elsevier}
}
```

### Latest DOI

[![DOI](https://doi.org/10.1016/j.eswa.2021.115519)
### @creator: Duong Tuan Linh
