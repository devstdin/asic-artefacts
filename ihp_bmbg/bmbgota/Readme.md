15.09.2025, 20:08:13

# Beta-Multiplier Bandgap OTA

OTA for Beta-Multiplier Bandgap.

![bmbgota](resources/bmbgota.png "bmbgota")

<br>

[🔗 Schematics](bmbgota_sch.pdf)<br>
<details><summary>Show Tool Versions...</summary>

> xschem: 3.4.6<br>
> ngspice: 44.2<br>
> magic: 8.3.541<br>
> netgen: 1.5.293<br>
> ihpopenpdk: dev<br>
</details><br>


# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](bmbgota_bmbgota_netgen_comp.out)<br>

# SPECIFICATIONS

## AC Open-Loop Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 93.598 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.90646399999996,10.0,31.894536000000027,10.0" style="stroke:green;stroke-width:2" /><circle cx="28.90646399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="31.894536000000027" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.013 / 110 | dB | 65/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 45 / 51.936 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.398133333333332,10.0,59.859413333333336,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.398133333333332" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.859413333333336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 98.306 / 180 | deg | 65/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 37.499 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.611518967741935,10.0,124.42860387096773,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.611518967741935" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.42860387096773" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 155.704 / 180.0 | MHz | 65/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.553 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.592795636363636,10.0,12.206494545454545,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.592795636363636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.206494545454545" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.733 / 10.0 | kHz | 65/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 90 / 93.618 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="29.046143999999995,10.0,32.05603200000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="29.046143999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="32.05603200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 94.036 / 110 | dB | 400/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 45 / 60.122 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.130240000000004,10.0,58.927679999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.130240000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="58.927679999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.432 / 180 | deg | 400/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 25.0 / 50.767 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.93842064516129,10.0,108.53574193548387,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.93842064516129" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.53574193548387" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 138.598 / 180.0 | MHz | 400/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 0.586 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.067332363636364,10.0,13.486789818181819,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.067332363636364" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.486789818181819" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.683 / 10.0 | kHz | 400/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 86.064 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.93191519999999,10.0,58.13052799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.93191519999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="58.13052799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.896 / 150 | dB | 65/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 64.745 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.87695418181818,10.0,117.85913890909092,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.87695418181818" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.85913890909092" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 78.87 / 90 | dB | 65/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 88.125 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.00054399999999,10.0,81.171904,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.00054399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.171904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.857 / 130 | dB | 65/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.109 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.27694628571429,10.0,90.31481142857142,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.27694628571429" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.31481142857142" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 56.222 / 70 | dB | 65/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 40 / 90.306 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="91.55069200000001,10.0,93.876816,10.0" style="stroke:green;stroke-width:2" /><circle cx="91.55069200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.876816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 90.487 / 120 | dB | 65/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.193 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.2506016,10.0,71.085504,10.0" style="stroke:green;stroke-width:2" /><circle cx="43.2506016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.085504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.092 / 20 | dB | 65/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 83.518 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.265992000000004,10.0,72.6376368,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.265992000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.6376368" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 98.359 / 150 | dB | 400/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 35 / 63.678 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.08311854545454,10.0,102.71837672727271,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.08311854545454" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="102.71837672727271" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 73.087 / 90 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 77.015 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.22430400000001,10.0,105.86352,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.22430400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="105.86352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 104.29 / 130 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | 35 / 51.792 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.08585142857142,10.0,82.50713142857141,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.08585142857142" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.50713142857141" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 54.325 / 70 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 50 / 87.445 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.02973485714284,10.0,100.08938742857141,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.02973485714284" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.08938742857141" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 97.196 / 120 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 5 / 9.89 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.9447776,10.0,61.217376,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.9447776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.217376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.064 / 20 | dB | 400/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -1.5 / -1.402 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.157759999999975,10.0,34.256640000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.157759999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="34.256640000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.391 / -1 | V | 65/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 1 / 1.294 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.76300800000001,10.0,90.38927999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.76300800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.38927999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.303 / 1.5 | V | 65/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -1.5 / -1.4 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.88927999999997,10.0,35.66336000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.88927999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="35.66336000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.394 / -1 | V | 400/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 1 / 1.296 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.2264,10.0,90.74524799999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.2264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.74524799999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.305 / 1.5 | V | 400/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.2 / 0.428 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="44.004342,10.0,67.030086,10.0" style="stroke:green;stroke-width:2" /><circle cx="44.004342" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.030086" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.556 / 1 | V | 65/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Positive CM Input Bound | 0.2 / 0.451 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.229842,10.0,64.414668,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.229842" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.414668" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.541 / 1 | V | 400/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -0.0 / 0.0 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.8098764,10.0,78.88596168000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.8098764" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.88596168000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.0 / 0.0 | mV | 65/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 14.275 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.778056,10.0,87.113208,10.0" style="stroke:green;stroke-width:2" /><circle cx="33.778056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.113208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 21.682 / 30.0 | MV/s | 65/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -100.0 / -97.634 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.7854399999999995,10.0,140.63103999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.7854399999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="140.63103999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -13.981 / -10.0 | MV/s | 65/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -10.0 / -2.731 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.335504,10.0,100.55534879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.335504" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.55534879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.549 / 10.0 | mV | 400/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 10.0 / 17.507 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="57.046872,10.0,71.73588,10.0" style="stroke:green;stroke-width:2" /><circle cx="57.046872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.73588" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 19.547 / 30.0 | MV/s | 400/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -100.0 / -76.838 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="40.05872,10.0,127.18704,10.0" style="stroke:green;stroke-width:2" /><circle cx="40.05872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.18704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -22.383 / -10.0 | MV/s | 400/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.684 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="27.247785599999997,10.0,30.051550399999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="27.247785599999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="30.051550399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.74 / 10.0 | uV/sqrt(Hz) | 65/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 1.288 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.636576,10.0,126.64243200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.636576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.64243200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.288 / 1.5 | uV/sqrt(Hz) | 65/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.289 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.777284799999997,10.0,76.480464,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.777284799999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.480464" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.021 / 2 | % | 65/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.391 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="31.1609496,10.0,58.3544784,10.0" style="stroke:green;stroke-width:2" /><circle cx="31.1609496" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="58.3544784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.769 / 2 | % | 400/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_404e9308425865f9fa51698b32f07f5c_10e01bd3dbdbb8640c77673fc5622103](xyplot_404e9308425865f9fa51698b32f07f5c_10e01bd3dbdbb8640c77673fc5622103.png "") |
| :-- |
|  |


## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89](histplot_olgain_1hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89.png "") |
| :-- |
|  |


| ![histplot_pmgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89](histplot_pmgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89.png "") |
| :-- |
|  |


| ![histplot_ugbwgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89](histplot_ugbwgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89.png "") |
| :-- |
|  |


| ![histplot_f2_3dbgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89](histplot_f2_3dbgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__26608f8b8d119360b4305fcdf2dd6a89.png "") |
| :-- |
|  |


## CMRR/PSRR Performance<br>

| ![xyplot_89ffe95c1f74ce31afa08d94a7c9576a_7b686de9473baa288c049bbced6e9df7](xyplot_89ffe95c1f74ce31afa08d94a7c9576a_7b686de9473baa288c049bbced6e9df7.png "") |
| :-- |
|  |


| ![xyplot_200adde2f605c3c0d8b68312b0e6e633_7b686de9473baa288c049bbced6e9df7](xyplot_200adde2f605c3c0d8b68312b0e6e633_7b686de9473baa288c049bbced6e9df7.png "") |
| :-- |
|  |


| ![xyplot_5b72395a42c5f4ad564dc243dc684e44_7b686de9473baa288c049bbced6e9df7](xyplot_5b72395a42c5f4ad564dc243dc684e44_7b686de9473baa288c049bbced6e9df7.png "") |
| :-- |
|  |


## CMRR/PSRR Performance (Monte Carlo)<br>

| ![histplot_cmrr_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_cmrr_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


| ![histplot_cmrr_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_cmrr_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


| ![histplot_psrr_p_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_psrr_p_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


| ![histplot_psrr_p_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_psrr_p_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


| ![histplot_psrr_n_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_psrr_n_10hzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


| ![histplot_psrr_n_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407](histplot_psrr_n_10mhzgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__cefdfae308b77e5d161e2ed50957b407.png "") |
| :-- |
|  |


## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__1caa2ca035209559d5481d84b0ef6ab4](histplot_neg_out_compgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__1caa2ca035209559d5481d84b0ef6ab4.png "") |
| :-- |
|  |


| ![histplot_pos_out_compgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__1caa2ca035209559d5481d84b0ef6ab4](histplot_pos_out_compgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__1caa2ca035209559d5481d84b0ef6ab4.png "") |
| :-- |
|  |


## Input Range Performance (Monte Carlo)<br>

| ![histplot_pos_cm_boundgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__822be2f28a46b74434b056b38fc4deb0](histplot_pos_cm_boundgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__822be2f28a46b74434b056b38fc4deb0.png "") |
| :-- |
|  |


## Slew-Rate/Offset Performance<br>

| ![xyplot_3f45e1515b2d0d4f4b44e4c2c22c7b3b_e3781566bddf33db64a1194827e58034](xyplot_3f45e1515b2d0d4f4b44e4c2c22c7b3b_e3781566bddf33db64a1194827e58034.png "") |
| :-- |
|  |


| ![xyplot_8a14f0cd438d63a55a8c144623da0dda_e3781566bddf33db64a1194827e58034](xyplot_8a14f0cd438d63a55a8c144623da0dda_e3781566bddf33db64a1194827e58034.png "") |
| :-- |
|  |


## Slew-Rate/Offset Performance (Monte Carlo)<br>

| ![histplot_inp_offsetgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8](histplot_inp_offsetgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8.png "") |
| :-- |
|  |


| ![histplot_slew_posgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8](histplot_slew_posgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8.png "") |
| :-- |
|  |


| ![histplot_slew_neggroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8](histplot_slew_neggroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__d896591e5420b398e61253096aa48ab8.png "") |
| :-- |
|  |


## Noise Performance<br>

| ![xyplot_9047406afdbe3bea6e4c0cd5dc77d6d8_fe52b15c7e52d0a16e46dfc2759b1de6](xyplot_9047406afdbe3bea6e4c0cd5dc77d6d8_fe52b15c7e52d0a16e46dfc2759b1de6.png "") |
| :-- |
|  |


## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__fca0bc36e68017a09aa56a6785620c30](histplot_thdgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__fca0bc36e68017a09aa56a6785620c30.png "") |
| :-- |
|  |

