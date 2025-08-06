PL below
<!-- TABLE OF CONTENTS -->
<a id="readme-top"></a>

<details> <summary>Table of Contents</summary> 
  <ol> 
    <li><a href="#introduction">Introduction</a></li> 
    <li><a href="#final-parameters">Final Parameters</a></li> 
    <li><a href="#measurements">Measurements</a></li> 
  </ol> 
</details>
<img src="https://github.com/Loczekk/hydrogen-line-LNA/images/gotowy.jpg" alt="PCB top view" width="600"/>
<!-- INTRODUCTION -->
## Introduction
The aim of the project was to design, build and test a low noise amplifier operating in the L-band. The amplifier was to meet strict requirements for gain (> 30 dB) and noise figure less than 1 dB.
A two-stage amplifier was implemented as a PCB on RF4 laminate and then subjected to detailed measurements to verify its performance. Scattering parameters, noise figure, 1 dB compression point, harmonic and third-order intermodulation distortion were measured.
Based on the results, it was concluded that the amplifier meets most of the design requirements: gain of 35.15 dB, output matching of 12.68 dB and 1-dB compression point at 3.02 dBm. Only the noise figure exceeded the assumed value and reached 1.39 dB, which, however, does not disqualify it from applications in radio astronomy.
Additionally, an automatic biasing circuit for the LNA was designed to ensure the correct power-up voltage sequence.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Final Parameters
<h3>Key Parameters (for <strong>f = 1420 MHz</strong>)</h3>

<table>
  <thead>
    <tr>
      <th>Parameter</th>
      <th>Value</th>
      <th>Requirement</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Gain</td>
      <td>35.15 dB</td>
      <td>&gt; 30 dB</td>
    </tr>
    <tr>
      <td>Noise figure</td>
      <td>1.39 dB</td>
      <td>&lt; 1 dB</td>
    </tr>
    <tr>
      <td>Output matching (<i>S<sub>22</sub></i>)</td>
      <td>12.68 dB</td>
      <td>&gt; 10 dB</td>
    </tr>
    <tr>
      <td>Compression point (<i>P<sub>1dB</sub></i>)</td>
      <td>3.02 dBm</td>
      <td>&gt; 0 dBm</td>
    </tr>
    <tr>
      <td>THD (for <i>P<sub>IN</sub></i> = –40 dBm)</td>
      <td>–47.21 dB</td>
      <td>–</td>
    </tr>
    <tr>
      <td>IP3 (for <i>P<sub>IN</sub></i> = –40 dBm)</td>
      <td>19.09 dBm</td>
      <td>–</td>
    </tr>
  </tbody>
</table>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Measurements

<p align="right">(<a href="#readme-top">back to top</a>)</p>
