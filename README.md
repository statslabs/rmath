# Rmath - The R Standalone Math Library

## Mathematical Constants
Rmath has a set of commonly used mathematical constants encompassing constants defined by POSIX and usually
found in `math.h` (but maybe not in the C++ header `cmath`) and contains further ones that are used in statistical
computations. These are defined to (at least) 30 digits accuracy in `Rmath.h`. The following definitions use ln(x)
for the natural logarithm (log(x) in Rmath).

| Name           | Definition (ln = log) | round(value, 7) |
|----------------|-----------------------|-----------------|
| M_E            | e                     | 2.7182818       |
| M_LOG2E        | log2(e)               | 1.4426950       |
| M_LOG10E       | log10(e)              | 0.4342945       |
| M_LN2          | ln(2)                 | 0.6931472       |
| M_LN10         | ln(10)                | 2.3025851       |
| M_PI           | pi                    | 3.1415927       |
| M_PI_2         | pi/2                  | 1.5707963       |
| M_PI_4         | pi/4                  | 0.7853982       |
| M_1_PI         | 1/pi                  | 0.3183099       |
| M_2_PI         | 2/pi                  | 0.6366198       |
| M_2_SQRTPI     | 2/sqrt(pi)            | 1.1283792       |
| M_SQRT2        | sqrt(2)               | 1.4142136       |
| M_SQRT1_2      | 1/sqrt(2)             | 0.7071068       |
| M_SQRT_3       | sqrt(3)               | 1.7320508       |
| M_SQRT_32      | sqrt(32)              | 5.6568542       |
| M_LOG10_2      | log10(2)              | 0.3010300       |
| M_2PI          | 2*pi                  | 6.2831853       |
| M_SQRT_PI      | sqrt(pi)              | 1.7724539       |
| M_1_SQRT_2PI   | 1/sqrt(2*pi)	         | 0.3989423       |
| M_SQRT_2dPI	 | sqrt(2/pi)	         | 0.7978846       |
| M_LN_SQRT_PI   | ln(sqrt(pi))          | 0.5723649       |
| M_LN_SQRT_2PI  | ln(sqrt(2*pi))        | 0.9189385       |
| M_LN_SQRT_PId2 | ln(sqrt(pi/2))        | 0.2257914       |