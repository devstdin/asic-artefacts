
# Reference Voltage Curvature vs Temperature <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.199 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,94.33144116574434,17,94.33144116574434,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.66572058287217,10.0,48.66572058287217,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.4942458020835,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="48.4942458020835" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.631 / 1.4 | V | 387/98.9664%/1.0336%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 2.08 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.198213056,10.0,54.23026944,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.198213056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="54.23026944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 88.941 / 250.0 | mV | 387/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.2 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,115.7724158670789,17,115.7724158670789,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.38620793353945,10.0,59.38620793353945,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="48.198507645030006,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="48.198507645030006" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.638 / 1.5 | V | 387/98.9664%/1.0336%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -703.423 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="32.794619999999995,10.0,77.5752186,10.0" style="stroke:green;stroke-width:2" /><circle cx="32.794619999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.5752186" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.92 / 1200.0 | uV/°C | 387/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -154.842 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.25280000000001,10.0,127.92096000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.25280000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.92096000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -81.924 / -70.0 | uA | 387/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 20°C":<br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.1_bmbg/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-wcs/dc.csv Index:2 vsup:3.3 <br>
</details><br>


# Reference Voltage Curvature vs Temperature (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.147 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="55.93728000000003,10.0,96.90924,10.0" style="stroke:green;stroke-width:2" /><circle cx="55.93728000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.90924" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.261 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.63 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.939096576,10.0,12.286381440000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.939096576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.286381440000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 16.122 / 250.0 | mV | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.15 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.87471999999997,10.0,96.89016000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.87471999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="96.89016000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.261 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -88.277 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="69.703356,10.0,81.267336,10.0" style="stroke:green;stroke-width:2" /><circle cx="69.703356" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.267336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 104.456 / 1200.0 | uV/°C | 400/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -106.992 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.81280000000001,10.0,110.09856,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.81280000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="110.09856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -93.063 / -70.0 | uA | 400/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Curvature vs VDD <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.196 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.58484000000003,10.0,87.95532,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.58484000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.95532" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.4 | V | 379/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.092 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.5277219264,10.0,7.633599744,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.5277219264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.633599744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.804 / 25.0 | mV | 387/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.196 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.46700800000002,10.0,70.954752,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.46700800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.954752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.5 | V | 379/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -0.147 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.472222,10.0,74.75432196,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.472222" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.75432196" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.068 / 20.0 | mV/V | 387/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -142.618 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="30.811200000000003,10.0,127.92096000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="30.811200000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.92096000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -81.924 / -70.0 | uA | 387/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Curvature vs VDD (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.166 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.71319999999999,10.0,100.14060000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.71319999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.14060000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.27 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.038 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.2193780096,10.0,13.05770304,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.2193780096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.05770304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.746 / 25.0 | mV | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.166 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="62.60304000000003,10.0,99.99551999999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="62.60304000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="99.99551999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.269 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -0.702 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.4741824,10.0,76.93516956,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.4741824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.93516956" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.538 / 20.0 | mV/V | 400/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -111.4 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.76000000000002,10.0,100.91632,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.76000000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.91632" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -98.802 / -70.0 | uA | 400/100.0%/0.0%/0.0% |  |

<br>


# Transient Startup Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 30.002 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.00288,17,5.00288,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.0014400000000006,10.0,4.0014400000000006,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.00144009648,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.00144009648" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3000000.0 / 60.0 | us | 516/75.0%/25.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Startup Time":<br>
> **FAIL:** group:h-tt_l-tt_b-typ_r-typ_c-typ file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-tt_l-tt_b-typ_r-typ_c-typ/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ss_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-ff_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-sf_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-fs_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-fs_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg/batch_0/h-fs_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
</details><br>


# Transient Startup Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 30.965 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.316264,10.0,81.29267999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.316264" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.29267999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 32.622 / 60.0 | us | 400/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 11.65 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.7756688,10.0,23.0854352,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.7756688" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="23.0854352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.559 / 100.0 | uV/sqrt(Hz) | 129/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.327 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.940923072,10.0,6.008736992,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.940923072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.008736992" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.35 / 50.0 | uV/sqrt(Hz) | 129/100.0%/0.0%/0.0% |  |

<br>


# PSRR+ Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -79.358 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.15469999999999,10.0,78.25746000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.15469999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.25746000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -78.19 / -40 | dB | 129/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.839 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.6279248,10.0,68.93930879999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.6279248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.93930879999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.737 / 20 | dB | 129/100.0%/0.0%/0.0% |  |

<br>


# PSRR+ Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -108.864 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.04479999999999,10.0,106.86324,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.04479999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="106.86324" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -62.298 / -40 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.702 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.9714336,10.0,69.99405599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.9714336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.99405599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.957 / 20 | dB | 400/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Curvature vs Temperature [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.202 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,31.052949943017442,17,31.052949943017442,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.02647497150872,10.0,17.02647497150872,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.194582274042254,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="17.194582274042254" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.053 / 1.4 | V | 387/99.2248%/0.7752%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.851 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.0663701119999995,10.0,68.6563968,10.0" style="stroke:green;stroke-width:2" /><circle cx="4.0663701119999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="68.6563968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 113.987 / 250.0 | mV | 387/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.203 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,37.782390255520134,17,37.782390255520134,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.391195127760067,10.0,20.391195127760067,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.14537203389544,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="17.14537203389544" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.07 / 1.5 | V | 387/99.2248%/0.7752%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -660.546 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="35.367239999999995,10.0,77.91761460000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="35.367239999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="77.91761460000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 48.627 / 1200.0 | uV/°C | 387/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -358.117 | <svg height="20" width="150"><polyline points="102.01827382625808,3,102.01827382625808,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.50913691312904,10.0,124.50913691312904,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,141.21430044044607,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="141.21430044044607" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | -81.576 / -70.0 | uA | 387/99.2248%/0.7752%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Mean Reference Voltage":<br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-bcs/dc.csv Index:1 vsup:2.5 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>

> **FAIL:** Specification violation for parameter "Reference Voltage at 20°C":<br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-bcs/dc.csv Index:1 vsup:2.5 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>

> **FAIL:** Specification violation for parameter "Max. Supply Current":<br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-bcs/dc.csv Index:1 vsup:2.5 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.1_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-bcs/dc.csv Index:2 vsup:3.3 <br>
</details><br>


# Reference Voltage Curvature vs Temperature (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.134 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.22416,10.0,89.99256000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.22416" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.99256000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.242 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 1.647 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.948621312,10.0,17.023244159999997,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.948621312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.023244159999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 24.346 / 250.0 | mV | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage at 20°C | 1 / 1.136 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="51.95964,10.0,89.63651999999998,10.0" style="stroke:green;stroke-width:2" /><circle cx="51.95964" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.63651999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.241 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 20°C | -1200.0 / -73.337 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="70.599804,10.0,80.542068,10.0" style="stroke:green;stroke-width:2" /><circle cx="70.599804" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="80.542068" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 92.368 / 1200.0 | uV/°C | 400/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -107.055 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.71200000000002,10.0,113.76064000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.71200000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="113.76064000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -90.775 / -70.0 | uA | 400/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Curvature vs VDD [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.199 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="74.81927999999999,10.0,87.88764000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="74.81927999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.88764000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.4 | V | 380/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.095 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.5447016,10.0,7.694643072,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.5447016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="7.694643072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.815 / 25.0 | mV | 380/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.199 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.45427200000002,10.0,70.89916800000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.45427200000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.89916800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.236 / 1.5 | V | 387/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -0.177 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.36442720000001,10.0,74.80905456,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.36442720000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.80905456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.053 / 20.0 | mV/V | 387/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -144.174 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="28.321600000000007,10.0,128.47824,10.0" style="stroke:green;stroke-width:2" /><circle cx="28.321600000000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="128.47824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -81.576 / -70.0 | uA | 387/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Curvature vs VDD (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Mean Reference Voltage | 1 / 1.156 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.17296000000003,10.0,91.69968000000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.17296000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.69968000000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.246 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Curvature | 0.0 / 0.067 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.3865507776,10.0,12.26424576,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.3865507776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="12.26424576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.608 / 25.0 | mV | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage at 3.3V | 1 / 1.156 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.20571999999997,10.0,91.64712000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.20571999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.64712000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.246 / 1.4 | V | 400/100.0%/0.0%/0.0% |  |
| Reference Voltage Sensitivity at 3.3V | -20.0 / -0.431 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.44822,10.0,76.09182564,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.44822" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="76.09182564" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.303 / 20.0 | mV/V | 400/100.0%/0.0%/0.0% |  |
| Max. Supply Current | -160.0 / -110.051 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.91840000000002,10.0,103.04048,10.0" style="stroke:green;stroke-width:2" /><circle cx="82.91840000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="103.04048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -97.475 / -70.0 | uA | 400/100.0%/0.0%/0.0% |  |

<br>


# Transient Startup Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 30.146 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,5.00288,17,5.00288,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.0014400000000006,10.0,4.0014400000000006,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.00144702528,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.00144702528" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3000000.0 / 60.0 | us | 516/75.0%/25.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Startup Time":<br>
> **FAIL:** group:h-tt_l-tt_b-typ_r-typ_c-typ file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-tt_l-tt_b-typ_r-typ_c-typ/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ss_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ss_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-ff_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-ff_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ss_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ss_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-ff_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-ff_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-sf_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-sf_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-wcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-wcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-bcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-bcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-bcs_r-bcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-sf_l-fs_b-bcs_r-bcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-sf_l-fs_b-bcs_r-bcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-wcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-fs_l-ss_b-wcs_r-wcs_c-wcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-wcs_c-bcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-fs_l-ss_b-wcs_r-wcs_c-bcs/tran.csv Index:3 <br>
> **FAIL:** group:h-fs_l-ss_b-wcs_r-bcs_c-wcs file:work/sim/bmbg/bmbg_tb.5_bmbg_ext/batch_0/h-fs_l-ss_b-wcs_r-bcs_c-wcs/tran.csv Index:3 <br>
</details><br>


# Transient Startup Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 30.742 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="76.781328,10.0,82.153056,10.0" style="stroke:green;stroke-width:2" /><circle cx="76.781328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="82.153056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 32.98 / 60.0 | us | 400/100.0%/0.0%/0.0% |  |

<br>


# Reference Voltage Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Noise at 10 Hz | 0.0 / 11.681 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.8208704,10.0,23.4310064,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.8208704" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="23.4310064" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.799 / 100.0 | uV/sqrt(Hz) | 129/100.0%/0.0%/0.0% |  |
| Output Noise at 10 kHz | 0.0 / 0.327 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.941192928,10.0,6.030451328,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.941192928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.030451328" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.358 / 50.0 | uV/sqrt(Hz) | 129/100.0%/0.0%/0.0% |  |

<br>


# PSRR+ Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -81.321 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="72.62202,10.0,81.27714000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="72.62202" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="81.27714000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -76.513 / -40 | dB | 129/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 3.254 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.6185088,10.0,71.09631359999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.6185088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.09631359999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.187 / 20 | dB | 129/100.0%/0.0%/0.0% |  |

<br>


# PSRR+ Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| PSRR+ at 10 Hz | -120 / -108.813 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="23.136599999999998,10.0,101.58006,10.0" style="stroke:green;stroke-width:2" /><circle cx="23.136599999999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="101.58006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -65.233 / -40 | dB | 400/100.0%/0.0%/0.0% |  |
| PSRR+ at 10 MHz | -10 / 2.859 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="64.7223888,10.0,72.3918816,10.0" style="stroke:green;stroke-width:2" /><circle cx="64.7223888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="72.3918816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.457 / 20 | dB | 400/100.0%/0.0%/0.0% |  |

<br>

