# Jupyter_Notebook

## Scientific analysis of physical layer communications:

### 1) TE_wave_frequency_graph:

Plot the dispersion diagrams of the first 3 modes (ω, cb). For the operating frequency ω_λ = (ω_1+ω_2)/2 and (ω_2+ω_3)/2, find the propagation constants. Finally, plot the curves of α_m.

### 2) wireless_links_1: 

#### 1)
Consider an electromagnetic wave with frequency 10α+2 Hz which propagates in free space and has electric field amplitude \( E_x = 0.5(b+1) \) V/m. Calculate:

(a) Its phase velocity, wavelength, and propagation constant.

(b) The characteristic impedance of the propagation medium.

(c) The amplitude of the magnetic field.

(d) Design the polarization of the wave.

(e) What polarization and what length should an antenna have to receive or transmit this signal?

(f) In which frequency band does this wave belong, what type of communications would you use it for, and why?

The calculations requested in the first three questions should also be done in the case where the wave propagates in a lossless medium with relative permittivity ε_r = 4 and relative permeability μ_r = 1.




#### 2)
Consider a telecommunication satellite system (point-to-point with passive reflectors and assuming that the propagation losses can be neglected) that uses a spherical passive satellite with effective cross-sectional area of \( (5+a) \) m\(^2\). The gain of the transmitting antenna is \( GT = 20b \) dB, the gain of the receiving antenna is \( GR = 2(a+1) \) dB, and the operating frequency is \( f = 5 \) GHz. The transmitted power is 100/(b+1) kW, and the temperature of the receiving antenna is 25 K. The distances of the transmitting and receiving antennas from the receiver are \( d1 = (2000+10a) \) m and \( d2 = (200+1000b) \) m, respectively. Calculate:

(a) The signal-to-noise ratio at the input of the receiver, if the receiver bandwidth is (a+1) kHz.

(b) At what distance should we position the receiver, without changing any other element of the system, in order to double the signal-to-noise ratio at the input of the receiver (in dB) compared to what was calculated in the previous step?

(c) For the \( d2 \) calculated in part b, if we don't change anything else in the system, what should be the minimum transmitting power to achieve a double signal-to-noise ratio at the input of the receiver (in dB) compared to what was calculated in part a?




#### 3) A RADAR operates at a frequency of 3 GHz with a transmitted power of 2.1 kW and a gain of 35 dB. What should be the sensitivity (in dBm) of the RADAR so that it can detect aircraft with a radar cross-section of \( \sigma = 40 \) square meters at distances ranging from 40 to 60 miles?


Create a sensitivity diagram for this specific RADAR system as a function of the distance of the aircraft. If the minimum sensitivity of the RADAR according to its manufacturer is -100 dBm, what is the maximum distance it can detect the aforementioned objects?

### 3) wireless_links_2:

#### 1)
In a radio system, there is a peaky obstacle at a distance \( d1 = (15+0.1a) \) km from the transmitting antenna. The optical axis of the system passes just below the top of the obstacle at a height \( h = (60+0.1a) \) m. The minimum distance of the system is \( d = (60+0.1a) \) km, the operating frequency is 500 MHz, and the gains of the transmitting and receiving antennas are \( GT = (15+0.1b) \) dB and \( GR = (18+0.1b) \) dB, respectively, and the received power is 1.5 nW. Calculate the transmitted power.

For the value of \( b \) corresponding to the last digit of our AM, graphically represent, on orthogonal coordinate axes, the variation of the transmitted power with \( a \). The values of \( a \) that should be displayed are from 0 to 10 with unit steps.

#### 2)
In a radio system, the transmitter is located at a height \( h_T = (50+0.1a) \) m and the receiver at a height \( h_R = (75-0.1a) \) m. The distance between them is \( d = (55+0.1a) \) km, and the operating frequency is 1 GHz. The transmitter emits with a power of 100W, and the transmitting and receiving antennas have gains \( GT = 150 \) and \( GR = 170 \) respectively. Between the transmitter and the receiver, at a distance of \( d1 = (25-0.1a) \) km from the transmitter, there is a peaky obstacle whose optical axis is at a height of \( (200-0.1a) \) m from the top. The prevailing meteorological conditions are either those of the standard atmosphere for 80% of the system's operating time or those of substandard atmosphere (K=1) for the remaining 20% of the system's operating time. Calculate the received power and its two cases, and the average received power for 100% of the system's operating time.

Graphically represent, on orthogonal coordinate axes, the variation of the received power with \( a \). The values of \( a \) to be displayed should range from 0 to 10 with unit steps.
