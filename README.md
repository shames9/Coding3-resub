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


### Adjust only the number of times the VGG19 model is trained

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/03.png).

Results of training completion

![Final-project](https://github.com/shames9/Coding3-resub/blob/main/Experimental%20data%20and%20screenshots%20of%20results/3.png).

#### Comparative conclusions
The more you train, the more the style of the style image is reflected in the content image.

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
In this study, two adjustments were made to the VGG19 model: one is to modify the framework parameters of the model, including the number of layers, the number of channels, etc.; and the other is to adjust the number of training iterations of the model. The experimental results show that simply adjusting the framework parameters of the model does not significantly affect the effect of image style migration, however, increasing the number of training iterations can significantly improve the migration results, indicating that the number of training sessions has a more significant effect on the migration effect. This finding is important for further optimising image style migration algorithms and deep learning model training strategies.

## Reference

https://www.kaggle.com/code/imoore/generate-paintings-by-image-style-transfer

https://www.kaggle.com/datasets/balraj98/monet2photo
