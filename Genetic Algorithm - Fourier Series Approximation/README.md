
# Genetic Algorithm — Fourier Series Approximation

_Intro to Artificial Intelligence — University of Tehran_

This project applies a **Genetic Algorithm (GA)** to approximate the first **20 terms** of the Fourier series of an unknown periodic function.  
The algorithm evolves candidate solutions (chromosomes of Fourier coefficients) and minimizes reconstruction error against sampled data.


## Tasks

1.  **Problem Modeling**
    -   Represent the Fourier approximation as:
	    $$
f(t) \approx \frac{a_0}{2} + \sum_{n=1}^{20} \big( a_n \cos(n \omega t) + b_n \sin(n \omega t) \big)
		$$
    -   Encode chromosomes as vectors of 41 coefficients (`a0...a20`, `b1...b20`).
    -   Restrict coefficients within [−10, 10].
        
2.  **Algorithm Design**
    
    -   Initialize a random population of candidate solutions.
    -   Define fitness based on error metrics (e.g., RMSE, R²).
    -   Apply **selection, crossover, mutation, and elitism** across generations.
        
3.  **Evaluation**
    -   Compare reconstructed vs. original function using plots.
    -   Track convergence of fitness scores.
    -   Analyze the effect of population size and parameters on accuracy and runtime.
        


## License

This project is licensed under the **MIT License**.


## Acknowledgements

Developed under the supervision of **Dr. Fadaei** and **Dr. Yaghoubzadeh**  
Designed by **Kourosh Sajadi, Shahriar Attar, Farbod Azim Mohseni**

