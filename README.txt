## This is README for CSRBMcovariant.lib 1.0 Jul_2019

## Author
	
	Yuki Nishida
        ynishida.cyjc1901[at]gmail.com


## Description 

	This is the SINGULAR library for computing the fundamental set of covariants via 
        Cyclically Standrad Regular Bracket Monomials.



## Requirement

	qmatrix.lib


## Initial setting for binary form of degree n

	make_root_ring (n);
	setring root_ring


## Compute the set M_d = {(m_1, ..., m_n) | m_1 + ... + m_n = m, m_i <= d }

	multicombination (n, d, m)


## Compute the set of cyclically standard bracket monimials with degree d (CS_d)

	multitranslation (int n, int d)

   Output "m(i)(j)" means [i j], "m(i)(n+1)" means [i u].


## Compute the basis of regular symmetric bracket polynomials with degree d

	sym_brac_basis (int n, int d)


## Compute the basis of covariants with degree d of binary form of degree n
 	
	covariant_deg_fixed (int n,int d)