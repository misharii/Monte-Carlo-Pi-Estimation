# Monte Carlo Pi Estimation

This code implements Monte Carlo's method of estimation to estimate the value of Pi. The Monte Carlo method is a statistical technique that relies on random sampling and is often used for numerical integration and simulation. In the context of Pi estimation, this method utilizes the geometric probability of a point being inside a unit circle inscribed within a square.

## Description

The program generates random points within a square that bounds a unit circle and then determines whether each point falls inside the circle. The ratio of the points inside the circle to the total number of points is an estimate of the area of the circle, which can be related back to Pi.

## How It Works

1. Randomly scatter a large number of points over the square.
2. Count how many of these points fall inside the circle inscribed in the square.
3. The ratio of the number of points inside the circle to the total number of points, multiplied by 4, gives an approximation of Pi.

## Usage

To run the simulation, simply execute the script. The number of trials determines the accuracy of the Pi estimation. By default, the script runs 1,000,000 trials, which provides a good balance between accuracy and computational time.

## Customization
You can modify the "total_trials" variable to increase or decrease the number of trials and thus the precision of the Pi estimation.

## Disclaimer
Please note that the Monte Carlo method provides a statistical estimate and therefore each run can produce slightly different results. Additionally, the accuracy of the estimate improves with the number of trials.
