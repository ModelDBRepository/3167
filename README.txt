NEURON model files from the paper 
M. Migliore, L. Messineo, M. Cardaci, G.F. Ayala, 
Quantitative modeling of perception and production of time intervals,
J.Neurophysiol. 86, 2754-2760 (2001). 

Using a basic biophysical model of a timekeeping system, 
and experimental data on time intervals produced or estimated under 
different conditions, the paper shows that experimental values, variability, and distributions, 
can be quantitatively explained in terms of a background synaptic activity such 
as that generated by attention. The paper suggests a possible
link between behavioral data and neural mechanisms at the single neuron level.

The mod files include a POINT_PROCESS that generates synaptic pulses
according to a Poissonian distribution, modified in such a way that its mean ISI 
could be drawn from a normal distribution. 
We used this mechanism to model intervals produced or estimated by different subjects,
whereas different cognitive loads were modeled by the strength of inhibition.
See the paper for more details on the underlying assumptions.

Under unix systems:
compile the mod files using the command 
nrnivmodl 
and run the simulation hoc file with the command 
nrngui timing_db.hoc

This will open a window from which a simulation of 5 subjects producing a 0.5 sec interval
can be run. Change "inhibition" to model different experimental conditions and cognitive loads.

Under Windows:
to compile the mod files use the "mknrndll DOS box" and 
follow on-screen instructions.
A double click on the simulation file
timing_db.hoc 
will open the simulation window.

Questions on how to use this model should be directed to
michele.migliore@pa.ibf.cnr.it

