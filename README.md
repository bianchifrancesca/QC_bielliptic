# QC_bielliptic
SageMath code for Quadratic Chabauty for rank 2, genus 2 bielliptic curves over Q.
This is used in [BP22]: "Rational points on rank 2 genus 2 bielliptic curves in the LMFDB" by F. Bianchi and O. Padurariu.

The main file is `qc_g2_bielliptic.sage` which does quadratic Chabauty on any genus 2 bielliptic curve given by an equation of the form `y^2 = a_6*x^6 + a_4*x^4 + a_2*x^2 + a_0`, with `a_i\in \ZZ`, such that the corresponding elliptic curves each have rank 1. The prime should be of good ordinary reduction.
This code is based on an earlier version by F. Bianchi, available at: https://github.com/bianchifrancesca/quadratic_chabauty/blob/master/quadratic_chabauty_bielliptic.sage

The file also contains code for turning the output of the quadratic Chabauty computation into an input for a Mordell--Weil sieve (as described in [BP22, S.4.2]).

NB: For the prime 3, the code relies on the following repository by Jennifer Balakrishnan: https://github.com/jbalakrishnan/AWS

The folder LMFDB contains some files for the computations of the rational points on the curves considered in [BP22], which we ran on CoCalc.

If you have questions or comments, please send an email to: francesca.bianchi.maths@gmail.com
