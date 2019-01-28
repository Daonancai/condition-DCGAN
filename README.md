# condition-DCGAN
## Dependencies
* opencv
* python2.7
* tensorflow1.2
## How to run
This works for gray images,if RGB iamges are used,c_dim should be 3 instead of 1.You need to put the the image flies under obj path.The size of the images should be gray 100*100,or you can fix it with your own size by setting input_height=your own size, input_width=your own size,output_height=your own size, output_width=your own size, what's more,the size to be resized in preproposor.py needs to be changed with your own size.
inputed images like this:
<br>
![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/obj/1/1.jpg) ![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/obj/2/1.jpg)
<br>
the image(64 images) from the generator after 200 iterations :
<br>
![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/samples/train_201_0201.png)
<br>
the image from the generator after 4600 iterations :
<br>
![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/samples/train_4601_4601.png)
<br>
the image from the generator after 23600 iterations :
<br>
![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/samples/train_23601_23601.png)
<br>
the image from the generator after 33000 iterations :
<br>
![label image](https://github.com/Daonancai/condition-DCGAN/blob/master/samples/train_33001_33001.png)
