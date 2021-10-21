# CovnertSMtoLOTOS
A java application for converting UML State machine to LOTOS and CSP for verifying 5 common properties

******************************************

How to use:
	1. First of all, you need to draw the statecharts in a tool like Visual Paradigm.
		- You can find Visual Paradigm via "https://www.visual-paradigm.com/"
	2. Create the XMI output by using the Visual Paradigm.
	3. Run CovnertSMtoLOTOS to convert the XMI file to LOTOS and CSP.
		- In the first windows, you must enter the XMI file address.
		- In the second, you need the XMI file name.
		- In two next windows, you approve the creation of LOTOS and CSP files.
	4. Use the CADP tool to check the deadlock, livelock, non-deterministic state and inaccessible state.
		- You can find CADP via "https://cadp.inria.fr/tools.html"
	5. Use FDR4 for checking divergence in the model.
		- You can find FDR4 via "https://www.cs.ox.ac.uk/projects/fdr/"
