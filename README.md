# F1-optimizations-with-Gradient-Descent

This was the final project for 24703 - Numerical Methods taught by Prof. Alan McGaughey at CMU in Spring '23.
Teammates: Niranjan Bhombe and Parth Malpathak

We attempted to optimize the raceline for a single 90° corner using numerical methods. We first discretize the domain as shown below
![problem_setup](https://github.com/sgodse16/F1-optimizations-with-Gradient-Descent/assets/109099769/6df06f6f-a092-4581-a5a8-79a2a75f871d)
For any path, the maximum possible speed with which the F1 car can traverse is limited by the coefficient of friction and radius of curvature. In order to minimize time, one needs to be at maximum possible speed. However, to maximize speed, one is constrained to move on a longer path with higher radius of curvature (less sharp turn). There is a sweet-spot in between which F1 drivers are expert at, which minimizes time. We found this sweet-spot using gradient descent optimization and compared it's variants - momentum and ADAM. We get the following result:
![image](https://github.com/sgodse16/F1-optimizations-with-Gradient-Descent/assets/109099769/d203090b-77c3-4a2c-9901-6ce2902aa3ae)
Pretty close right?
