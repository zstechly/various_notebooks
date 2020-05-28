# Some misc notebooks
A collection of my Juypter notebooks that I use to work various things out.


1: welch_method.ipynb:  Uses the welch method to average 1024-sized FFTs.  Original purpose was to figure out the mapping between Matlab's welch method and scipy's welch method

2: DC_Offet_Loop.ipynb: A DC offset removal loop

3: freq_inversion.ipynb:  Demonstrating frequency inversion by I/Q swapping and low side up-conversion

4: mapping_frequency_to_pins.ipynb: Someone asked me to figure out how to map an FFT bin to frequency, so I wrote a step by step guide

5: polyphase_test.ipynb: Taking an FIR filter, breaking it into an even/odd slice, demonstrating that we can get the original response back by adding / subtracting the results in a particular way

6: power_conservation.ipynb: Demonstrating Parseval's theorem

7: ddr_test_sig_gen.ipynb:  I had a DDR memory to fill with samples to be played out of a DAC.  Needed to create tones that would roll over correctly to not have spurs.

