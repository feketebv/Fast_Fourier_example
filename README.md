# Fast_Fourier_example

I found a very straightforward explanation of recursive FFT outlined in the PDF, whose credentials I don't recall anymore, but it is not mine(!) except for the correction that I commented in the PNG.

So this version of FFT is not yet that effective, because it calculates every single value of X(f) separately, and as such has to calculate the necessary twiddle factors a lot more, than if a straighforward matrix multiplication would be used, which however is not so easy to follow, how that works.


