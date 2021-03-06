## Short Introduction
We assess the evaluation metric for video summarization.
Our analysis of video summarization datasets demonstrates the evaluation frameworks have some issues.

## Abstruct

Video summarization is a technique to create a short skim of the original video while preserving the main stories/content. There exists a substantial interest in automatizing this process due to the rapid growth of the available material. The recent progress has been facilitated by public benchmark datasets, which enable easy and fair comparison of methods. Currently the established evaluation protocol is to compare the generated summary with respect to a set of reference summaries provided by the dataset. In this paper, we will provide in-depth assessment of this pipeline using two popular benchmark datasets. Surprisingly, we observe that randomly generated summaries achieve comparable or better performance to the state-of-the-art. In some cases, the random summaries outperform even the human generated summaries in leave-one-out experiments. Moreover, it turns out that the video segmentation, which is often considered as a fixed pre-processing method, has the most significant impact on the performance measure. Based on our observations, we propose alternative approaches for assessing the importance scores as well as an intuitive visualization of correlation between the estimated scoring and human annotations.

## Paper
![paper]({{ site.url }}/rethinking-evaluation-of-video-summaries/images/paper/thums_small.jpg)

## Results

## Code

## Citation

```
@InProceedings{otani2018vsumeval,
    title={Rethinking the Evaluation of Video Summaries},
    author={Mayu Otani, Yuta Nakahima, Esa Rahtu, and Janne Heikkil{\"{a}}},
    booktitle={The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2019}
}
```

