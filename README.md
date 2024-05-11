In signal processing, a filter is a device or algorithm that is used to selectively modify or remove 
certain frequency components of a signal. Filters are commonly used in audio and video processing, 
image processing, and communication systems to eliminate unwanted noise or interference, improve 
signal quality, or extract useful information from the data. Filters are classified according to the 
functions that they perform, in terms of ranges of frequencies. In this project under the module 
EE5308 Electronic Circuit Design we are focusing on designing a 9th order Butterworth low pass 
filter with a 6 kHz cut off frequency. 
A low-pass filter is a type of filter that allows low-frequency signals to pass through while attenuating 
or blocking high-frequency signals. In other words, it removes or reduces high-frequency components 
from a signal, while preserving or passing through low-frequency components. Low-pass filters are 
commonly used in electronic circuits, audio systems, and communication systems to remove noise or 
unwanted signals that are above a certain frequency. They are also used to prevent aliasing, which is 
a type of distortion that can occur when a signal is sampled at a rate that is too low to capture all of 
its frequency components. The range of low frequencies, which are passed, is called the pass band or 
the bandwidth of the filter.
The cutoff frequency of a filter is the frequency at which the filter's output signal is attenuated or 
reduced by a specified amount (usually -3 decibels) relative to its maximum amplitude or gain. In 
other words, the cutoff frequency is the frequency above which the filter starts to filter out or attenuate 
the input signal. The highest frequency to be transmitted which is the cut off frequency of the filter is 
6 kHz for our project.
The Butterworth filter is a type of filter used in signal processing that provides a smooth and gradual 
attenuation of frequencies outside the passband. It is characterized by a maximally flat magnitude 
response in the passband and a monotonic roll-off in the stopband. When implementing the filter 
Sallen-key topology has been used. The Sallen–Key topology is an electronic filter topology used to 
implement second-order active filters that is particularly valued for its simplicity.
