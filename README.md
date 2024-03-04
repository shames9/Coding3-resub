## Optimising deep learning model parameters and training strategies on the effect of image style migration

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/0001.png).

## Project Introduction
The aim of this project is to explore the effect on the image style migration effect by adjusting the frame parameters and training times of the VGG19 model, and by using a different style of CONTENT IMAGE and the same style of STYLE IMAGE as another set of control groups with the same frame parameter adjustments and training times adjustments. I design a series of experiments using different structural parameters and training times of the VGG19 model for the image style migration task, and compare the quality and effectiveness of the generated images between different combinations of experiments. The experimental results are analysed to provide insights into methods and techniques for optimising deep learning model parameters and training strategies.

**Video Presentation Link**
- [[https://youtu.be/IYVI5ZOX0R8](https://youtu.be/kODMLhI9QBI)]

## Experimental procedure
Select the appropriate content image and style image

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/1.png).

Framework parameters of the VGG19 model

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/001.png).

Number of times the VGG19 model was trained

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/01.png).

Results of training completion

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/0001.png).

### Adjusting only the frame parameters of the VGG19 model

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/02.png).

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/002.png).

Results of training completion

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/0002.png).

#### Comparative conclusions
Training was performed by adjusting only the frame parameters of the VGG19 model and the results were compared. The results show that the adjustments to the frame parameters of the VGG19 model had a small effect on the training results, with no significant significant change in the training results from the pre-adjustment period. This suggests that the VGG19 model's ability to fit the data with this modification was not significantly improved.

By analysing this result, the following are several possible scenarios. Firstly, the VGG19 model may have been sufficiently adapted to the training data with the original parameter settings and therefore the fine-tuning of the frame parameters did not have a significant impact. Secondly, the tuned frame parameters may have failed to introduce enough variation to have a significant impact on the model's performance. Finally, it may also indicate that the training data itself was not sufficient to show a more significant change in performance in the tuned model and that further tuning or the addition of more training data was required.


### Adjust only the number of times the VGG19 model is trained

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/03.png).

Results of training completion

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/3.png).

#### Comparative conclusions
By modifying the number of training times for the VGG19 model, I observed the relationship between the extent to which the style features of the content image are reflected in the style image and the number of training times. The results show that as the number of training times increases, the features of the style image reflected in the content image become more and more obvious.

Specifically, the degree of matching between the style features in the content image and the style image is lower at a smaller number of training times. However, as the number of training times increases, the content images gradually begin to exhibit style features that are more similar to the style images. This phenomenon may be due to the fact that in more training iterations, the model is better able to learn features such as texture, colour and shape in the style image and gradually apply them to the content image.


## Experimental procedure of Test
In order to ensure the rigour of the research on image style migration and to prevent surprises from the experimental study, an additional set of simulation experiments were conducted in this study.

Select the appropriate content image and style image

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/11.png).

Results of training completion

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/111.png).

### Adjusting only the frame parameters of the VGG19 model (Test1)

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/112.png).

### Adjust only the number of times the VGG19 model is trained (Test1)

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/113.png).

#### Comparative conclusions (Test1)
If only modifying the frame parameters of the VGG19 model and keeping the number of training times unchanged, there is no very obvious effect on the migration effect of image style.

If only modifying the number of training times of VGG19 model and keeping the frame parameters unchanged, the more times of training, the more obvious effect on the migration of image style.

## Conclusions
![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/2222.png).
![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/1111.png).
The VGG19 model is adjusted by two kinds of adjustments: one is to modify the framework parameters of the model, including the number of layers, the number of channels, etc.; the other is to adjust the number of training iterations of the model. The experimental results show that only adjusting the framework parameters of the model does not have a significant effect on the image style migration effect, however, increasing the number of training iterations can significantly improve the migration results, indicating that the number of training sessions has a more significant effect on the migration effect.

Specifically, adjusting the model's frame parameters did not result in significant improvements, either because the VGG19 model was sufficiently adapted to the task with the original parameter settings, or the magnitude of adjusting the parameters was not sufficient to cause significant changes. Instead, increasing the number of training iterations provided more opportunities for the model to learn the style features in the data, which significantly improved the migration. This suggests that a greater number of training iterations is critical to the model's performance when performing the image style migration task. This finding has important implications for further optimising image style migration algorithms and deep learning model training strategies.

## Reference

https://www.kaggle.com/code/imoore/generate-paintings-by-image-style-transfer

https://www.kaggle.com/datasets/balraj98/monet2photo
