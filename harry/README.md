**[1]** <br />
a] The requested PDF is nothing more than the PDF of a gaussian X(μ=98, σ^2=16), which, as the question states, is the distribution that models our prior belief. Hence, the requested PDF is the following: 1/(4 x sqrt(2π)) x e^(-(x-98)^2/32) <br />
b] We basically want to know P(reading=100|t) of the instrument's reading, which is approximated by a gaussian X(μ=t, σ^2=4) due to us knowing the true distance, so the expected value. Because of this, the PDF of such a probability is modelled as such: 1/(2 x sqrt(2π)) x e^(-(100-t)^2/8)  <br />
c] We are asked to calculate P(t|reading = 100), which, using Bayes' theorem, we know can be rewritten as P(t|reading = 100) = P(reading=100|t) x P(t) (in this case we can ignore the denominator). As we have already computed the two values in the above questions, we just need to substitute the values into the formula. Hence: P(t|reading=100) = (1/(2 x sqrt(2π)) x e^(-(100-t)^2/8)) x (1/(4 x sqrt(2π)) x e^(-(x-98)^2/32)) <br />
**[2]** <br />
All of the questions involve using a Poisson distribution, just with different arguments and knowing that, when we are changing the time measurement, we need to multiply the constant lambda with it in order to obtain a veritable result. For simplicity's sake, we are going to use some lines of code written in R to obtain those values: to verify them, simply paste them in a .r file or use an online compiler and launch the script. <br />
a] 1 - ppois(7,5.5) = 0.1905147  <br />
b] here lambda = 2 x 5.5 = 11, hence 1 - ppois(13,11) = 0.2187088 <br />
c] here lambda = 3 x 5.5 = 16.5, hence 1 - ppois(15,16.5) = 0.5819805 <br />
**[3]** <br />
a] We know the CDF of the uniform distribution is: F(x) = {0 if x < a; 1 if x > b; (x-a)/(b-a) if a <= x <= b}. Hence, in order to find the median, we set F(x) so that F(x) = 0.5, which means that x falls between a and b, so we get that F(x) = (x-a)/(b-a) = 0.5. We can resolve per x to obtain the value that would give us the median and we obtain: x = a + 0.5(b-a) = 1/2 x a + 1/2 x b = (a+b)/2   <br />
b] As above, we could calculate the CDF of the normal distribution for F(x) = 0.5 in order to obtain the values. However, due to the symmetric property of the gaussian, we know that such a property tells us that the mean is equal to the median, hence F(x) = 0.5 = μ. A proof of the normal distribution having such a property can be found here: https://statproofbook.github.io/P/norm-med.html <br />
**[4]** <br />
a] We want to compute P(X1 + X2 > 5000). Knowing that X1 and X2 are independent and that the sum of two gaussians is a gaussian with as arguments the sum of the two, we can sum them to give birth to the gaussian X3(μ=2200+2200=4400, σ^2=52900+52900=105800). We now want to calculate P(x > 5000), which we can do as P(x > 5000) = 1 - P(x <= 5000). Using R, we get this value as 1 - pnorm(5000, 4400, sqrt(105800)) = 0.03254595 <br />
b] <br />
**[5]** <br />
a] <br />
b] <br />
c] <br />
**[6]** <br />
a] <br />
b] <br />
c] <br />
d] <br />
**[7]** <br />
a] <br />
b] <br />
c] <br />
