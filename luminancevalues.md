---
layout: default
title: Luminance values
nav_order: 6
nav_exclude: false
---
## Luminance measurements


<img src="https://github.com/ZeissVisionScienceLab/HMD-FOV//blob/main/assets/images/luminancefig.svg?raw=true" alt="Luminance values Figure" width="400" align="left"/>
In some psychophysical experiments, the stimulus's luminance and contrast have to be carefully controlled. However, this is not usually the case in virtual reality, where each headset has different display panels (even different display panel technologies).

To provide a better replicability across studies using different headsets, the luminance at different values that each headset is capable of producing is measured.

### Methodology
The virtual environment's skybox in Unity was fixed at Hue and Saturation, while "Value" was increased from 0 to 100 (in steps of 10). At each step, three luminance measurements were taken using the luminance-meter (Konica Minolta LS-110, Konica Minolta, Inc., Tokyo, Japan) with the close-up lens in a dark room.

<br><br><br><br><br>
## Luminance Table

<br>
<div id="tableTex">
<div class="scroll-wrapper">
    <table>
    <caption> Results of "Value" in HSV Color space for the different stimulus luminance in the Goldmann. "o.o.r." stands for out of range.
    </caption>
    <thead>
      <tr>
        <th  rowspan="2">HMD / Values</th>
        <th  colspan="2" rowspan="2">Background</th>
        <th  colspan="2">Stimulus</th>
        <th >Max</th>
        <th >Min</th>
      </tr>
      <tr>
        <th >(2)</th>
        <th >(3)</th>
        <th  colspan="2">(cd m-²)</th>
      </tr>
    </thead>
    <tbody>
    <tr>
      <td text-align="left">Goldmann<br>(Luminance)</td>
      <td  colspan="2">10 cd m-²<br>31.5 asb</td>
      <td >32</td>
      <td >100</td>
      <td >-</td>
      <td >-</td>
    </tr>
    <tr>
      <td text-align="left">HTC Vive</td>
      <td  colspan="2">28.8</td>
      <td >46.5</td>
      <td >76.81</td>
      <td >178.7</td>
      <td >0.0</td>
    </tr>
    <tr>
      <td text-align="left">HTC Vive Pro</td>
      <td  colspan="2">33.8</td>
      <td >55.6</td>
      <td >93.4</td>
      <td >116.1</td>
      <td >0.0</td>
    </tr>
    <tr>
      <td text-align="left">Star VR One</td>
      <td  colspan="2">42.6</td>
      <td >70.08</td>
      <td >o.o.r.</td>
      <td >68.4</td>
      <td >0.0</td>
    </tr>
    <tr>
      <td text-align="left">Oculus Rift DK2</td>
      <td  colspan="2">39.9</td>
      <td >71.9</td>
      <td >o.o.r.</td>
      <td >62.4</td>
      <td >0.0</td>
    </tr>
    <tr>
      <td text-align="left">Pico Neo 2</td>
      <td  colspan="2">43.5</td>
      <td >74.0</td>
      <td >o.o.r.</td>
      <td >60.5</td>
      <td >0.1</td>
    </tr>
    <tr>
      <td text-align="left">Fove 0</td>
      <td  colspan="2">29.1</td>
      <td >55.3</td>
      <td >o.o.r.</td>
      <td >97.2</td>
      <td >0.1</td>
    </tr>
    </tbody>
    </table>
</div>
</div>

### > [Back to main page](https://zeissvisionsciencelab.github.io/HMD-FOV/)