# Цировофой прорыв - сезон ЦФО: Окружной хакатон

---
### Case: Central Bank RF
*Description*: <br>
Purpose of this competition is creation of machine-learning nowcasting-model for anomalities, splashes and periodically breakdowns detection into the IT-sollutions, exploring interruptions regularities by the means of users requests dataset.

### GibData sollution:
*Teaser*: <br>
For solving this problem we present machine-learning model for predicting and supporting stable IT-sollutions work. Represented model let minimize system's errors by the means of raising quality requires classification with machine-learning model and statistical data processing. With this product, the Central Bank RF will be able to more accurately assess potential violations, which can be both obvious, disrupting the work of an entire department, and minor.

Used stack of technologies: `Python`, `CatBoost`, `SBERT`, `LaBSE`, `Streamlit`.

*The first task: Model developing*: <br>
1) File `hard_ml.ipynb` - high-required sollution with high quality of predictions (`CatBoost` + `SBERT` for extracing info (embeddings) from text) <br>
File `get_embeddings.ipynb` - `LaBSE` and `SBERT` for getting embeddings
2) Folder `web` - fast sollution for flexible embedding into bisness but a little worse than first sollution by classification quality (Open-Source model `CatBoost` by Yandex)

![color picker](https://s11.gifyu.com/images/outputvideo-cutter-js.com.gif) <br>
**Interface example**

Embeddings download: https://drive.google.com/drive/folders/1rjfXhDYRegHC_ix4pk0QjcbYis9uvb-Z?usp=share_link

*The second and third task: Statistical data processing*: <br>
In this part of work was held statisic data analysis and processing: anomality classification, exploring distinctive parts between anomalities and common requires. <br>
File `gibdata.ipynb` - exploring data analysis, feature generation, visual analysis.
