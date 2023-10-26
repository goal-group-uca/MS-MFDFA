# MS-MFDFA
In the literature, there are few studies that address low-level directives.
These directives consider the underlying architecture to create green programs. One of the main challenges is the strong knowledge required. Another
challenge is the high level of uncertainty in consumption measurements. These measurements can be affected by existing software services, hardware,
and ambient temperature, among other factors. In our work, titled MULTI-SIGNAL MULTIFRACTAL DETRENDED FLUCTUATION ANALYSIS FOR UNCERTAIN SYSTEMS. 
APPLICATION TO THE ENERGY CONSUMPTION OF SOFTWARE PROGRAMS IN MICROCONTROLLERS, we introduce a new approach. For the first time, we propose the 
characterization of software consumption using the Multi-fractal approach. This generates a signature of the software consumption profile. This 
signature is independent of the runtime, consumption levels, and uncertainty.
To achieve this, we construct a consumption signal. This signal, or time series, is derived from high-frequency sampling. It captures the 
instantaneous input current during the program’s operation. This signal is then analyzed using MF-DFA.
There’s a challenge with the uncertainty present in the energy consumption measurements. Analyzing a single time series doesn’t provide significant
conclusions. As a result, many experiments are required. To address this, we propose a novel methodology. This methodology can handle a large number
of time series simultaneously during the multifractal analysis.
Additionally, we propose eight programs for analysis. These can serve as a reference for others. We have developed software that can automatically
perform this analysis. This software has been made freely available to the scientific community.

The MS-MFDFA software achieves four main objectives:

Preprocessing. Allows for trimming signals and addressing potential anomalous data (outliers).

Decomposition. Enables the decomposition of signals into their trend, seasonality, and residue components, storing the residue of each signal
for subsequent analysis.

Multianalysis. Facilitates the MF-DFA analysis of the set of signals, producing the Assembled fluctuation function, which represents the set
of fluctuation functions resulting from applying the MF-DFA algorithm to each signal.
Multianalysis Quality. Allows for the generation of a summary table of the quality of the fit performed on the Assembled fluctuation function
in relation to all fluctuation functions. The summary is provided in table form and is available in both .xlsx and .tex formats.

This software has been implemented in Matlab R2022b and is optimized for a screen resolution of 2560 x 1440 pixels. The self-installation version is
available for use on Windows 10 or later.

Please, cite us as:
Awaiting the publication of the research paper.
