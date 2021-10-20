[→ Open in Slid](https://slid.cc/docs/7fccbeb779f14db8a000dcd28bedbc03)


---





\-> Fitting a straight line (called **Hypothesis**) to the data for prediction

[![Linear Regression image](https://slid-capture.s3.ap-northeast-2.amazonaws.com/public/image_upload/7fccbeb779f14db8a000dcd28bedbc03/4d3b923c-7653-49f9-9a9a-59b0348277e8.jpg)](undefined)




---

### Hypothesis Function




![f\left ( x \right ) = \Theta_{0}.x_{0} + \Theta_{1}.x_{1} + \Theta_{2}.x_{2} \hspace{0.2cm} ...... \hspace{0.2cm}\Theta_{n}.x_{n}](https://latex.codecogs.com/svg.latex?%5Cdpi%7B300%7Df%5Cleft%20(%20x%20%5Cright%20)%20=%20%5CTheta_%7B0%7D.x_%7B0%7D%20+%20%5CTheta_%7B1%7D.x_%7B1%7D%20+%20%5CTheta_%7B2%7D.x_%7B2%7D%20%5Chspace%7B0.2cm%7D%20......%20%5Chspace%7B0.2cm%7D%5CTheta_%7Bn%7D.x_%7Bn%7D)





**Vectorised Form**




[![Linear Regression image](https://slid-capture.s3.ap-northeast-2.amazonaws.com/public/capture_images/7fccbeb779f14db8a000dcd28bedbc03/7ee5c5be-b804-4871-9099-3e9f3732de5a.jpg)](https://slid.cc/vdocs/7fccbeb779f14db8a000dcd28bedbc03?v=c8c618a8305c44a89810cf1f3284d48a&start=2834.566733)




![\therefore \hspace{0.3cm} f(x) = \Theta.x](https://latex.codecogs.com/svg.latex?%5Cdpi%7B300%7D%5Ctherefore%20%5Chspace%7B0.3cm%7D%20f(x)%20=%20%5CTheta.x)




---




### Cost Function





\-> Used to evaluate the performance of a model.




![J(\theta_0, \theta_1) = \frac{1}{2m} \sum_{i=1}^m \left(h_\theta(x_i) - y_i \right)^2](https://latex.codecogs.com/svg.latex?%5Cdpi%7B300%7DJ(%5Ctheta_0,%20%5Ctheta_1)%20=%20%5Cfrac%7B1%7D%7B2m%7D%20%5Csum_%7Bi=1%7D%5Em%20%5Cleft(h_%5Ctheta(x_i)%20-%20y_i%20%5Cright)%5E2)




---




### Gradient Descent





\-> Optimization algorithm that decreases the cost function





**How it works**

- Checks the value of θ at every step

- If it's lower than the previous value, it edits the valuw to the new one

- Continiues till the deepest point in the slope is reached

[![Linear Regression image](https://slid-capture.s3.ap-northeast-2.amazonaws.com/public/capture_images/7fccbeb779f14db8a000dcd28bedbc03/dddf144a-dc43-42ff-a120-feae99d8dad3.jpg)](https://slid.cc/vdocs/7fccbeb779f14db8a000dcd28bedbc03?v=c8c618a8305c44a89810cf1f3284d48a&start=3374.932794)




---




### Where to use Linear Regression





\-> The data should have a linear relationship


\-> There should be no/little multicollinearity




---



