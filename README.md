# Shannon Entropy Calculator

Named after Boltzmann's Η-theorem, Shannon defined the entropy Η (Greek capital letter eta) of a discrete random variable X with possible values {x1, ..., xn} and probability mass function P(X) as:

<a href="https://www.codecogs.com/eqnedit.php?latex={\displaystyle&space;\mathrm&space;{H}&space;(X)=\mathbb&space;{E}&space;[\mathrm&space;{I}&space;(X)]=\mathbb&space;{E}&space;[-\ln(\mathrm&space;{P}&space;(X))].}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{\displaystyle&space;\mathrm&space;{H}&space;(X)=\mathbb&space;{E}&space;[\mathrm&space;{I}&space;(X)]=\mathbb&space;{E}&space;[-\ln(\mathrm&space;{P}&space;(X))].}" title="{\displaystyle \mathrm {H} (X)=\mathbb {E} [\mathrm {I} (X)]=\mathbb {E} [-\ln(\mathrm {P} (X))].}" /></a>

Here E is the expected value operator, and I is the information content of X. I(X) is itself a random variable. The entropy can explicitly be written as:

<a href="https://www.codecogs.com/eqnedit.php?latex={\displaystyle&space;\mathrm&space;{H}&space;(X)=\sum&space;_{i=1}^{n}{\mathrm&space;{P}&space;(x_{i})\,\mathrm&space;{I}&space;(x_{i})}=-\sum&space;_{i=1}^{n}{\mathrm&space;{P}&space;(x_{i})\log&space;_{b}\mathrm&space;{P}&space;(x_{i})},}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{\displaystyle&space;\mathrm&space;{H}&space;(X)=\sum&space;_{i=1}^{n}{\mathrm&space;{P}&space;(x_{i})\,\mathrm&space;{I}&space;(x_{i})}=-\sum&space;_{i=1}^{n}{\mathrm&space;{P}&space;(x_{i})\log&space;_{b}\mathrm&space;{P}&space;(x_{i})},}" title="{\displaystyle \mathrm {H} (X)=\sum _{i=1}^{n}{\mathrm {P} (x_{i})\,\mathrm {I} (x_{i})}=-\sum _{i=1}^{n}{\mathrm {P} (x_{i})\log _{b}\mathrm {P} (x_{i})},}" /></a>

where b is the base of the logarithm used. Common values of b are 2, Euler's number e, and 10, and the corresponding units of entropy are the bits for b = 2, nats for b = e, and bans for b = 10.

One may also define the conditional entropy of two events X and Y taking values xi and yj respectively, as:

<a href="https://www.codecogs.com/eqnedit.php?latex={\displaystyle&space;\mathrm&space;{H}&space;(X|Y)=-\sum&space;_{i,j}p(x_{i},y_{j})\log&space;{\frac&space;{p(x_{i},y_{j})}{p(y_{j})}}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?{\displaystyle&space;\mathrm&space;{H}&space;(X|Y)=-\sum&space;_{i,j}p(x_{i},y_{j})\log&space;{\frac&space;{p(x_{i},y_{j})}{p(y_{j})}}}" title="{\displaystyle \mathrm {H} (X|Y)=-\sum _{i,j}p(x_{i},y_{j})\log {\frac {p(x_{i},y_{j})}{p(y_{j})}}}" /></a>

where p(xi, yj) is the probability that X = xi and Y = yj. This quantity should be understood as the amount of randomness in the random variable X given the event Y [[SOURCE]](https://en.wikipedia.org/wiki/Entropy_(information_theory)#Definition).


