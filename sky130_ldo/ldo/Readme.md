# 1.8 V LDO

1.8 V linear regulator.

![ldo](resources/ldo.png "ldo")

<br>

[🔗 Schematics](ldo_sch.pdf)<br>

# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](ldo_lvs_ldo_netgen_comp.out)<br>

# SPECIFICATIONS

## LDO Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.88967999999996,10.0,63.38136000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.88967999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.38136000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.837 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.785977216,10.0,8.604164352,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.785977216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.604164352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.729 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.27480000000003,10.0,62.155920000000116,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.27480000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.155920000000116" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.8332984,10.0,110.9534232,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.8332984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.9534232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.935 / 100.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.761 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.83431999999998,10.0,66.15624000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.83431999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.15624000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 499/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.872 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.5025545856,10.0,8.028630912,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.5025545856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.028630912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.73 / 250.0 | mV | 499/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.761 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.73280000000002,10.0,65.44056000000009,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.73280000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.44056000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.787 / 1.9 | V | 400/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 2.032 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.46271744,10.0,108.2911656,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.46271744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.2911656" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 46.238 / 100.0 | uV/°C | 499/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.59736000000003,10.0,59.97216000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.59736000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.97216000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.387 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.3511936,10.0,108.92519039999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.3511936" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.92519039999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.39 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.10776000000002,10.0,59.05632000000011,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.10776000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.05632000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.803 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.6925532,10.0,93.082458,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.6925532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.082458" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.023 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.083520000000014,10.0,64.30080000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.083520000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.30080000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.785 / 1.9 | V | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.683 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.8116608,10.0,88.2942528,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.8116608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.2942528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.808 / 25.0 | mV | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.762 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.48592000000009,10.0,63.64704000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.48592000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.64704000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.098 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.7544308,10.0,90.62351400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.7544308" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.62351400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.34 / 20.0 | mV/V | 500/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.766160000000006,10.0,66.37008000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.766160000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.37008000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.788 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.822 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.735257984,10.0,18.3239328,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.735257984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.3239328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.66 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.905840000000026,10.0,66.79631999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="58.905840000000026" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="66.79631999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.789 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -7.274 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="22.626407999999998,10.0,59.262816,10.0" style="stroke:green;stroke-width:2" /><circle cx="22.626407999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.262816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.186 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.99672000000007,10.0,69.79008000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.99672000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.79008000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 490/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.138 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.552288,10.0,12.663697280000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.552288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.663697280000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.331 / 25.0 | mV | 490/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="52.20191999999997,10.0,69.99456000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="52.20191999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.99456000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.793 / 1.9 | V | 490/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.592 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="49.135944,10.0,53.12892,10.0" style="stroke:green;stroke-width:2" /><circle cx="49.135944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="53.12892" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.038 / 10 | V/A | 490/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.576443680000001,10.0,7.76334704,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.576443680000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76334704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.919 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2639068704,10.0,5.2809036224,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2639068704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2809036224" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.785 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.37544000000003,10.0,137.65404,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.37544000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.65404" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 1.687 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.0980944,10.0,62.45923679999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.0980944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.45923679999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.387 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.902 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.29283692307693,10.0,88.84881230769231,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.29283692307693" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.84881230769231" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.498 / 10 | dB | 497/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 1.513 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="122.81511280000001,10.0,126.0735,10.0" style="stroke:green;stroke-width:2" /><circle cx="122.81511280000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="126.0735" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.561 / 20 | dB | 497/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 20.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.0326784,10.0,75.6149664,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.0326784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.6149664" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 25.214 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 19.96 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.4845696,10.0,80.8868928,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.4845696" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.8868928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.044 / 50.0 | mV | 492/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.938 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.581146239999999,10.0,11.97325184,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.581146239999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="11.97325184" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.421 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.328 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.8233152,10.0,10.27583616,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.8233152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.27583616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.526 / 50.0 | mV | 498/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 48.689 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.935146666666666,10.0,19.930133333333334,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.935146666666666" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.930133333333334" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 60.872 / 180 | deg | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Loopgain PM Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 47.593 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.766293333333336,10.0,20.45525333333333,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.766293333333336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.45525333333333" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 61.364 / 180 | deg | 480/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.877440000000014,10.0,63.374159999999975,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.877440000000014" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.374159999999975" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 4.83 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.781883007999999,10.0,8.591756736,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.781883007999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.591756736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.708 / 250.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.26400000000012,10.0,62.14872000000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.26400000000012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.14872000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 24.738 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.81157599999999,10.0,110.9537904,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.81157599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.9537904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 49.936 / 100.0 | uV/°C | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.759 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="45.75648000000008,10.0,62.40360000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="45.75648000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="62.40360000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.783 / 1.9 | V | 498/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.206 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.694585152,10.0,8.54589792,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.694585152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="8.54589792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.628 / 250.0 | mV | 498/100.0%/0.0%/0.0% |  |
| LDO Voltage at 20°C | 1.7 / 1.76 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.53695999999998,10.0,61.921200000000084,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.53695999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="61.921200000000084" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.782 / 1.9 | V | 399/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 20°C | -100.0 / 4.395 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.16430928000001,10.0,111.9806472,10.0" style="stroke:green;stroke-width:2" /><circle cx="78.16430928000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.9806472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 51.362 / 100.0 | uV/°C | 498/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.772 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.58584000000002,10.0,59.96424000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.58584000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.96424000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.779 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 12.369 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.247744,10.0,108.91142400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.247744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="108.91142400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.387 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.771 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.09696000000011,10.0,59.049120000000066,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.09696000000011" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="59.049120000000066" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.778 / 1.9 | V | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 3.797 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.67098560000001,10.0,93.0793764,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.67098560000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="93.0793764" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.022 / 20.0 | mV/V | 15/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.40968000000004,10.0,65.47800000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.40968000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.47800000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.787 / 1.9 | V | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 13.682 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="81.8058432,10.0,87.93638399999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="81.8058432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.93638399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.746 / 25.0 | mV | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage at 3.3V | 1.7 / 1.762 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.84448000000001,10.0,64.89552,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.84448000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="64.89552" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.786 / 1.9 | V | 500/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 3.3V | -20.0 / 4.099 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.757498,10.0,90.5509344,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.757498" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.5509344" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.32 / 20.0 | mV/V | 500/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Curvature vs Load [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,6.808399424931686,17,6.808399424931686,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.904199712465843,10.0,4.904199712465843,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.474212375393934,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="4.474212375393934" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9.262 / 1.9 | V | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 0.845 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.866829632,10.0,26.21589312,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.866829632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.21589312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.031 / 25.0 | mV | 15/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.778 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,6.807790660362128,17,6.807790660362128,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.903895330181064,10.0,4.903895330181064,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.477803555286543,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="4.477803555286543" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9.263 / 1.9 | V | 15/93.3333%/6.6667%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -8.061 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.959935999999995,10.0,58.930104,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.959935999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="58.930104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.232 / 10 | V/A | 15/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean LDO Voltage":<br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.3_ldo_ext/batch_0/ll/ldo_tran_iload.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "LDO Voltage at 100uA":<br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.3_ldo_ext/batch_0/ll/ldo_tran_iload.csv Index:0 <br>
</details><br>


## LDO Voltage Curvature vs Load (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean LDO Voltage | 1.7 / 1.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.67848000000003,10.0,72.47424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.67848000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.47424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.796 / 1.9 | V | 498/100.0%/0.0%/0.0% |  |
| LDO Voltage Curvature | 0.0 / 1.16 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.681749759999999,10.0,12.83638784,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.681749759999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.83638784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.36 / 25.0 | mV | 498/100.0%/0.0%/0.0% |  |
| LDO Voltage at 100uA | 1.7 / 1.768 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.87792000000009,10.0,72.68736000000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.87792000000009" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.68736000000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.797 / 1.9 | V | 498/100.0%/0.0%/0.0% |  |
| LDO Voltage Sensitivity at 100uA | -10 / -3.655 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.684864,10.0,52.8204,10.0" style="stroke:green;stroke-width:2" /><circle cx="48.684864" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="52.8204" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -3.08 / 10 | V/A | 498/100.0%/0.0%/0.0% |  |

<br>


## LDO Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 1.789 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.5755984000000005,10.0,7.76488928,10.0" style="stroke:green;stroke-width:2" /><circle cx="5.5755984000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.76488928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.92 / 100.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2639286432,10.0,5.2811105216000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2639286432" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.2811105216000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.098 / 50.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -80 / -43.793 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="133.34592,10.0,137.65548,10.0" style="stroke:green;stroke-width:2" /><circle cx="133.34592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.65548" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.596 / -40 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 5.562 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.697288,10.0,80.338488,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.697288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.338488" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.112 / 20 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -43.894 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="85.30236307692309,10.0,88.88304000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="85.30236307692309" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.88304000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -42.467 / 10 | dB | 498/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -100 / 5.342 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="127.4103268,10.0,130.7060844,10.0" style="stroke:green;stroke-width:2" /><circle cx="127.4103268" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="130.7060844" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 6.422 / 20 | dB | 498/100.0%/0.0%/0.0% |  |

<br>


## Line Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 22.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.420912,10.0,79.01820479999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.420912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.01820479999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 26.395 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Line Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 21.082 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.7153824,10.0,82.825104,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.7153824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.825104" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 27.717 / 50.0 | mV | 500/100.0%/0.0%/0.0% | Ripple from 1V Input Voltage Step |

<br>


## Load Transient Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 2.209 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.363293760000001,10.0,12.61013216,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.363293760000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.61013216" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.642 / 50.0 | mV | 5/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## Load Transient Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Ripple | 0.0 / 1.64 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.7238048,10.0,10.97442048,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.7238048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.97442048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.769 / 50.0 | mV | 500/100.0%/0.0%/0.0% | Ripple from 50->250 uA Load Step |

<br>


## AC Loopgain PM Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 38.864 | <svg height="20" width="150"><polyline points="9.26022189991618,3,9.26022189991618,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.13011094995808,10.0,78.13011094995808,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,15.685629504087204,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="15.685629504087204" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 51.298 / 180 | deg | 5/80.0%/20.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Loopgain PM":<br>
> **FAIL:** group:ll file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_0/ll/ldo_ac_loop.csv Index:0 <br>
</details><br>


## AC Loopgain PM Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Loopgain PM | 45 / 38.312 | <svg height="20" width="150"><polyline points="9.797519062957873,3,9.797519062957873,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="78.39875953147894,10.0,78.39875953147894,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,16.959082042002027,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="16.959082042002027" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 52.047 / 180 | deg | 500/64.0%/36.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Loopgain PM":<br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/tt_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_4/ll_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ff_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ss_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ss_mm/ldo_ac_loop.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldo/ldo_tb.8_ldo_ext/batch_1/ll_mm/ldo_ac_loop.csv Index:19 <br>
</details><br>


# PERFORMANCE CHARACTERISTICS

## LDO Output Voltage vs Temperature<br>

| ![xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b](xyplot_temp-sweepv(vldo)v(vdd)_('tt',_-2)__744781268f63d499334ec11aa5b1bf9b.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Temperature (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5](histplot_vldo_t20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5](histplot_vldo_tc20group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77a6f9ffbaae0c36f9d4f7a926eec6b5.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD<br>

| ![xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003](xyplot_v(v-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__4a17ff07c51788f19fb3341308999003.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs VDD (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa](histplot_vldo_3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa](histplot_vldo_tc3v3group_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__5cd2f1d25c91f5294677a6ef5dabe2aa.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current<br>

| ![xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03](xyplot_i(i-sweep)v(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__d136f91180b00a3b70cbdba575b1ae03.png "") |
| :-- |
|  |
<br>

## LDO Output Voltage vs Load Current (Monte Carlo)<br>

| ![histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d](histplot_vldo_meangroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d](histplot_vldo_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d](histplot_vldo_100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d.png "") |
| :-- |
|  |
<br>

| ![histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d](histplot_vldo_tc100ugroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__636d0f72c10ab35bab2e8af2bcd5c61d.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__520cd1a858bc5d1a4c1e1d95f8ef7de5](xyplot_frequencyonoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__520cd1a858bc5d1a4c1e1d95f8ef7de5.png "") |
| :-- |
|  |
<br>

## PSRR+ Performance<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__277b066cc3d6ff8a4a7d32220f2eff36](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__277b066cc3d6ff8a4a7d32220f2eff36.png "") |
| :-- |
|  |
<br>

## PSRR+ Performance (Monte Carlo)<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0e3d9af6f82b5589de22ed9ff81f69a8](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0e3d9af6f82b5589de22ed9ff81f69a8.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0e3d9af6f82b5589de22ed9ff81f69a8](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__0e3d9af6f82b5589de22ed9ff81f69a8.png "") |
| :-- |
|  |
<br>

## Line Transient Performance<br>

| ![xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef](xyplot_timev(vout)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__c6f1621216fbf421e184df6be2d356ef.png "1V Line Transient") |
| :-- |
| 1V Line Transient |
<br>

## Line Transient Performance (Monte Carlo)<br>

| ![histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a34d1f938e10ffd2848a430b6d198282](histplot_line_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__a34d1f938e10ffd2848a430b6d198282.png "") |
| :-- |
|  |
<br>

## Load Transient Performance<br>

| ![xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52](xyplot_timev(vldo)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__03f831caf24373c04bd4aea9b49bca52.png "200uA Load Transient") |
| :-- |
| 200uA Load Transient |
<br>

## Load Transient Performance (Monte Carlo)<br>

| ![histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__338688c165618838860906e4c55bdf86](histplot_load_tran_ppgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__338688c165618838860906e4c55bdf86.png "") |
| :-- |
|  |
<br>

## AC Loopgain PM (Monte Carlo)<br>

| ![histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77965deb46de4493edb6d9f80a1da658](histplot_loop_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__77965deb46de4493edb6d9f80a1da658.png "") |
| :-- |
|  |
<br>
