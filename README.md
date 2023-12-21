# ControlWeb

![app](https://github.com/AdityaPartole/ControlWeb/assets/142674497/5268d496-9a3b-48c3-b0aa-ca7ef9da1fc9)


ControlWeb is a web app which lets Control Systems engineers design & experiment with LTI (linear time-invariant) dynamical systems online.

So far, functionality has been implemented for:

- the analytical computation of the overall transfer function (tf) of a system modeled by interconnected elements in the s-domain
- the generation of its Bode and Nyquist plots
- the numerical computation of its time response plot
- the numerical computation of its zeros/poles & some characteristic numbers, ex. bandwidth


## Motivation

The motivation behind ControlWeb is to create an open-source tool for studying Control Systems, which:

- runs on the browser without any installation, is fast and mobile-friendly
- is written in a widely-used programming language (vanilla Javascript), and can be easily extended

## Technical details


### Numerical algorithms

- Polynomial complex roots: Weierstrass / Durand-Kerner algorithm
- Laplace inversion: Talbot algorithm


### Ready-made components

- Utilities: integrator / step, exponential decay, sine, phase delay
- Controllers: PI, PD, PID

## Try it out

### Online

- The app is deployed [here](https://adityapartole.github.io/ControlWeb/)



