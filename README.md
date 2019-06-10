# CVPR-Paper-Statistics
Statistics and Visualization of acceptance rate, main keyword of CVPR 2019 accepted papers for the main Computer Vision conference [(CVPR 2019)](http://cvpr2019.thecvf.com/)

Inspired by [`ICLR2019-OpenReviewData`](https://github.com/shaohua0116/ICLR2019-OpenReviewData)

<p align="center">
  <img width="600" src="/2019_cvpr/keyword_cloud_title.PNG">
</p>

# CVPR 2019 Acceptance rate (2015~2019)

- The total number of papers is increasing every year and this year has increased significantly!
- The acceptance rate decreased from 30% to 25%.

<p align="center">
  <img width="500" src="/2019_cvpr/cvpr_acceptance_rate.PNG">
</p>

# CVPR 2019 simple paper review(20 papers)
- [Slide](https://www.slideshare.net/HoseongLee6/2019-cvpr-paperoverview)



# CVPR Paper Keywords statistics
- [Accepted Paper list](https://github.com/hoya012/CVPR-Paper-Statistics/blob/master/2019_cvpr/cvpr_2019_poster.csv)

- Most of the top keywords were maintained
   - Image, detection, 3d, object, video, segmentation, adversarial, recognition, visual …
- `graph`, `cloud`, `representation` are about twice as frequent
   - graph : 15 -> 45
   - representation: 25 -> 48
   - cloud: 16 -> 35

<p align="center">
  <img width="1000" src="/2019_cvpr/top_keywords_2019+2018.png">
</p>

# Analysis and Visualization Code (Jupyter Notebook)

- The above data can be obtained from a simple jupyter notebook script.
- I wrote two versions of the code.
   - [`CVPR_paper_statistics_using_csv.ipynb`](https://github.com/hoya012/CVPR-Paper-Statistics/blob/master/CVPR_paper_statistics_using_csv.ipynb) --> Use csv data format
   - [`CVPR_paper_statistics_using_chrome.ipynb`](https://github.com/hoya012/CVPR-Paper-Statistics/blob/master/CVPR_paper_statistics_using_chrome.ipynb) --> Use website data format

## Prerequisites
- python3.5
- [selenium](https://selenium-python.readthedocs.io/)
- [wordcloud](https://pypi.org/project/wordcloud/)
- [matplotlib](https://matplotlib.org/)

or 

**i highly recommend to use** [google colab](https://colab.research.google.com/)

Just **download jupyter notebook** and **move to your google drive** and **Open with Colaboratory**


