# 2.2. Vapnick-Chervonenskis Dimensions

Given N points, labelled (+) and (-), if we can shatter these points no matter which ones are labelled (+) or (-), we say that the VC dimensions of this problem
is N.

# 2.3. Probably Approximately Correct Learning

# 2.4. Noise

Noise can be explained by:

- Imprecise input,
- Teacher noise: mislabeled input,
- Neglected attributes,

Often, a simple model makes more sense to handle noise than a complex one:

- Easier to check,
- Easier to train,
- Easier to explain,
- Generalizes better (Occam’s razor).

# 2.5. Learning Multiple Classes

Given a labelled dataset X, each point should belong in a single class K:

<a href="https://www.codecogs.com/eqnedit.php?latex=X&space;=&space;\left&space;\{&space;x^t,&space;r^t&space;\right&space;\}_{t=1}^{N}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?X&space;=&space;\left&space;\{&space;x^t,&space;r^t&space;\right&space;\}_{t=1}^{N}" title="X = \left \{ x^t, r^t \right \}_{t=1}^{N}" /></a>
