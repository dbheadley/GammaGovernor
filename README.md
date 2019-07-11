---


---

<h1 id="gamma-governor">Gamma Governor</h1>
<p>Gamma Governor is a closed-loop controller for modulating gamma oscillations in the local field potential that is implemented in <strong>LabView</strong>. With this code, the appropriate hardware, and optrodes implanted in an opsin bearing brain, one can up- or down-regulate spontaneously occuring gamma oscillations. The application is flexible enough to work with most electrophysiological recording hardware (but the <a href="http://www.intantech.com/RHD2000_USB_interface_board.html">Intan Evalulation System</a> is preferred).</p>
<h1 id="getting-started">Getting Started</h1>
<p>Gamma Governor is a collection of virtual instruments (VIs) designed to work on National Instruments (NI) hardware. There are two principal sets of code. One runs on the <em>Target</em>, which is the multifunction DAQ with an FPGA. The others run on the <em>Host</em>, which is a PC that communicates with the DAQ via USB. Make sure you have installed LabView with the FPGA module. This code should work with most NI FPGA recently (after 2018) released NI FPGA hardware.</p>
<h1 id="credits">Credits</h1>
<p>This program was created by Drew B. Headley. If using it in a publication, please cite Kanta, Pare, and Headley 2019, Nature Communications.</p>

