# Sampling Theorem

In this project, we have done **Sampling** of a signal bandlimited to 40 Hz, with sampling rate of 800 Hz.

Then we have done **Sampling** of the signal with a sampling rate of 80Hz, using **Nyquist rate**.

We made an observation that if we take frequency lesser, as per Nyquist rate, this is called **aliasing** in which we are not able to recover the full signal and there will be loss.

We have also sampled the signal with a sampling rate of 30Hz, where we have "not" used the Nyquist rate.

We can finally see the loss (in the notebook) in the 30Hz, it can't capture proper cycle. We can't recover the signal properly below Nyquist level.
