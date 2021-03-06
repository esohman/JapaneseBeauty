# JapaneseBeauty

This is the repo for Instagram data from 20 beauty-related companies active in Japan.

The Instagram accounts are:

| Company name  | Instagram handle    |
|---------------|---------------------|
| Beauteen      | beauteen_offical    |
| Chifure       | chifure_official    |
| Curél         | curel_official_jp   |
| DHC           | dhc_official_jp     |
| Etude House   | etudejapan          |
| Ichikami      | ichikami_kracie     |
| Innisfree     | innisfreejapan      |
| Kanebo        | kaneboofficial      |
| Kireimo       | kireimo_official    |
| Kosé          | kose_official       |
| Liese         | liese_official_jp   |
| Maybelline    | maybellinejp        |
| Musée         | museeplatinum_insta |
| Palty         | paty_official       |
| Revlon        | revlonjapan         |
| Rimmel        | rimmellondon_jp     |
| Rize Clinic   | rizeclinic          |
| Sekkisei      | sekkisei.official   |
| Shiseido      | shiseido_japan      |
| TBC Aesthetic | tbc_aesthetic       |

The data is from between January 2016 and May 2021. 

The data is formatted as one json dataframe that has been split into multiple files using the split command (due to file size constraints on GitHub). The files can be easily merged again by typing ```cat x?? > beauty_json.csv``` in terminal.

To cite this data use:

```
@InProceedings{ohman2021japan,
  author        = {{\"O}hman, Emily and Amy Grace Metcalfe},
  title         = {{Japanese Beauty Marketing on Social Media: Critical Discourse Analysis Meets NLP}},
  booktitle     = {NLP4DH @ ICON'2021},
  year          = {2021},
  publisher     = {ACL}
}
```
