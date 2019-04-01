# backprojection-tomography
CT scan simulation using Radon transform and backprojection algorithm with additional convolutional filter and gamma correction.
### Prerequisites:
Use conda's spec file in order to create identical environment on your local machine:

```
conda create --name myenv --file spec-file.txt
conda activate myenv
```
Then run 
```
jupyter notebook final.ipynb
``` 
in order for the widgets to work properly.

### Project description:
1. Original image:

![original](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/original2.PNG?raw=true)

2. Radon transform:

![radon](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/sinogram2.PNG?raw=true)

3. Backprojection (without filtering):

![backprojection](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/without-filtering2.PNG?raw=true)

4. Convolution kernel:

![kernel](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/kernel.PNG?raw=true)

5. Sinogram after convolution:

![convolved-sinogram](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/convolved-sinogram2.PNG?raw=true)

6. Backprojection with filters:

![filtered](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/simple-filter.PNG?raw=true)

7. Gamma correction and final result:

![gamma](https://raw.githubusercontent.com/damian-horna/backprojection-tomography/master/charts/results/final-result.PNG?raw=true)
