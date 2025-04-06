
# Transient Startup Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Max. Supply Current Analog | 0.0 / 52.058 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,7.46776322675098,17,7.46776322675098,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="5.23388161337549,10.0,5.23388161337549,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.77526965640005,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.77526965640005" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9669.268 / 300.0 | uA | 45/97.7778%/2.2222%/0.0% |  |
| Max. Supply Current Digital | 0.0 / 1.821 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.87403824,10.0,6.92053232,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.87403824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.92053232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 4.001 / 300.0 | uA | 45/100.0%/0.0%/0.0% |  |
| LDO Output Voltage | 1.7 / -0.464309 | <svg height="20" width="150"><polyline points="85.6692244235365,3,85.6692244235365,17,93.30854250829582,17,93.30854250829582,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.48888346591616,10.0,89.48888346591616,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 3.305661 / 1.9 | V | 45/91.1111%/8.8889%/0.0% |  |
| LDO Output Overshoot | 0.0 / 19.366 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,15.05385057745478,17,15.05385057745478,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.02692528872739,10.0,9.02692528872739,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="4.167153859868964,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="4.167153859868964" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 2389.278 / 200.0 | mV | 45/91.1111%/8.8889%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Max. Supply Current Analog":<br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "LDO Output Voltage":<br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:0 <br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:1 <br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:2 <br>
> **FAIL:** group:tt file:work/sim/tt08/tt08_tb.1_tran/batch_0/tt/tran.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "LDO Output Overshoot":<br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:0 <br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:1 <br>
> **FAIL:** group:ff file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff/tran.csv Index:2 <br>
> **FAIL:** group:tt file:work/sim/tt08/tt08_tb.1_tran/batch_0/tt/tran.csv Index:0 <br>
</details><br>


# Transient Startup Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Max. Supply Current Analog | 0.0 / 217.763 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="107.52619200000001,10.0,117.316128,10.0" style="stroke:green;stroke-width:2" /><circle cx="107.52619200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.316128" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 238.159 / 300.0 | uA | 100/100.0%/0.0%/0.0% |  |
| Max. Supply Current Digital | 0.0 / 1.301 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.62453616,10.0,6.7888904000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.62453616" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.7888904000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.727 / 300.0 | uA | 100/100.0%/0.0%/0.0% |  |
| LDO Output Voltage | 1.7 / 1.656267 | <svg height="20" width="150"><polyline points="26.467505366086332,3,26.467505366086332,17,133.78923205342227,17,133.78923205342227,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.1283687097543,10.0,80.1283687097543,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.924619 / 1.9 | V | 100/93.0%/7.0%/0.0% |  |
| LDO Output Overshoot | 0.0 / 14.878 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.712232,10.0,69.7979784,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.712232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.7979784" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 92.775 / 200.0 | mV | 100/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "LDO Output Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.1_tran/batch_1/ff_mm/tran.csv Index:8 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran/batch_1/ss_mm/tran.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran/batch_1/hh_mm/tran.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.1_tran/batch_0/ff_mm/tran.csv Index:9 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran/batch_0/ss_mm/tran.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran/batch_0/hh_mm/tran.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran/batch_0/hh_mm/tran.csv Index:8 <br>
</details><br>


# Transient Oscillator Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| First High Pulse Duration | 30.0 / 33.786 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.543476000000006,10.0,123.76032000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="7.543476000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="123.76032000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 130.634 / 150.0 | nS | 15/100.0%/0.0%/0.0% |  |
| First Oscillator Period Duration | 60.0 / 66.635 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.981234000000002,10.0,88.01790000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.981234000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="88.01790000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 201.696 / 300.0 | nS | 15/100.0%/0.0%/0.0% |  |
| Duty-Cycle of First Oscillator Period | 30 / 35.19961 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,144.05436176329707,17,144.05436176329707,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.52718088164853,10.0,73.52718088164853,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.335691749201427,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="21.335691749201427" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 70.83532 / 70 | % | 15/93.3333%/6.6667%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Duty-Cycle of First Oscillator Period":<br>
> **FAIL:** group:hh file:work/sim/tt08/tt08_tb.2_tran/batch_0/hh/tran.csv Index:0 <br>
</details><br>


# Transient Oscillator Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| First High Pulse Duration | 30.0 / 36.532 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.83792,10.0,143.74272,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.83792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.74272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 147.286 / 150.0 | nS | 100/100.0%/0.0%/0.0% |  |
| First Oscillator Period Duration | 60.0 / 76.605 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.963012,10.0,104.16684000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.963012" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="104.16684000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 228.611 / 300.0 | nS | 100/100.0%/0.0%/0.0% |  |
| Duty-Cycle of First Oscillator Period | 30 / 31.70048 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,128.97645421335469,17,128.97645421335469,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="65.98822710667734,10.0,65.98822710667734,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.35551102151813,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="8.35551102151813" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 75.72283 / 70 | % | 100/94.0%/6.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Duty-Cycle of First Oscillator Period":<br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_1/ff_mm/tran.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_1/ff_mm/tran.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_1/ff_mm/tran.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_0/ff_mm/tran.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_0/ff_mm/tran.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.2_tran/batch_0/ff_mm/tran.csv Index:7 <br>
</details><br>


# Transient Startup Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Max. Supply Current Analog | 0.0 / 212.507 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="105.003168,10.0,122.23454400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="105.003168" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="122.23454400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 248.405 / 300.0 | uA | 45/100.0%/0.0%/0.0% |  |
| Max. Supply Current Digital | 0.0 / 1.822 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.8744510400000003,10.0,6.95242272,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.8744510400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.95242272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 8.234 / 300.0 | uA | 45/100.0%/0.0%/0.0% |  |
| LDO Output Voltage | 1.7 / 1.837729 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="102.16488000000001,10.0,119.6306400000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="102.16488000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="119.6306400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.861987 / 1.9 | V | 45/100.0%/0.0%/0.0% |  |
| LDO Output Overshoot | 0.0 / 19.734 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="17.2084944,10.0,84.245232,10.0" style="stroke:green;stroke-width:2" /><circle cx="17.2084944" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="84.245232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 112.841 / 200.0 | mV | 45/100.0%/0.0%/0.0% |  |

<br>


# Transient Startup Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Max. Supply Current Analog | 0.0 / 215.95 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="106.65585600000001,10.0,117.096624,10.0" style="stroke:green;stroke-width:2" /><circle cx="106.65585600000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.096624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 237.701 / 300.0 | uA | 100/100.0%/0.0%/0.0% |  |
| Max. Supply Current Digital | 0.0 / 1.35 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.6480849600000003,10.0,10.020004800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.6480849600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="10.020004800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 14.625 / 300.0 | uA | 100/100.0%/0.0%/0.0% |  |
| LDO Output Voltage | 1.7 / 1.755361 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,114.58076626541492,17,114.58076626541492,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="58.79038313270746,10.0,58.79038313270746,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.88611400609818,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="33.88611400609818" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 1.958109 / 1.9 | V | 100/81.0%/19.0%/0.0% |  |
| LDO Output Overshoot | 0.0 / 8.045 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.79226248,10.0,65.3369736,10.0" style="stroke:green;stroke-width:2" /><circle cx="8.79226248" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="65.3369736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.579 / 200.0 | mV | 100/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "LDO Output Voltage":<br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ff_mm/tran.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ff_mm/tran.csv Index:7 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ss_mm/tran.csv Index:0 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ss_mm/tran.csv Index:3 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ss_mm/tran.csv Index:5 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ss_mm/tran.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/hh_mm/tran.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/hh_mm/tran.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/tt_mm/tran.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_1/ll_mm/tran.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/ff_mm/tran.csv Index:6 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/ss_mm/tran.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/ss_mm/tran.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/hh_mm/tran.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/hh_mm/tran.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/tt_mm/tran.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/tt_mm/tran.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/ll_mm/tran.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/tt08/tt08_tb.1_tran_ext/batch_0/ll_mm/tran.csv Index:7 <br>
</details><br>


# Transient Oscillator Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| First High Pulse Duration | 30.0 / 0.0 | <svg height="20" width="150"><polyline points="31.799999999999997,3,31.799999999999997,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.4,10.0,89.4,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,70.16561279999999,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="70.16561279999999" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 69.964 / 150.0 | nS | 15/93.3333%/6.6667%/0.0% |  |
| First Oscillator Period Duration | 60.0 / 0.0 | <svg height="20" width="150"><polyline points="31.799999999999997,3,31.799999999999997,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.4,10.0,89.4,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,73.374768,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="73.374768" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 146.614 / 300.0 | nS | 15/93.3333%/6.6667%/0.0% |  |
| Duty-Cycle of First Oscillator Period | 30 / 0.0 | <svg height="20" width="150"><polyline points="64.71428571428571,3,64.71428571428571,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="105.85714285714286,10.0,105.85714285714286,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,106.41981257142855,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="106.41981257142855" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 50.27352 / 70 | % | 15/93.3333%/6.6667%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "First High Pulse Duration":<br>
> **FAIL:** group:ll file:work/sim/tt08/tt08_tb.2_tran_ext/batch_0/ll/tran.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "First Oscillator Period Duration":<br>
> **FAIL:** group:ll file:work/sim/tt08/tt08_tb.2_tran_ext/batch_0/ll/tran.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "Duty-Cycle of First Oscillator Period":<br>
> **FAIL:** group:ll file:work/sim/tt08/tt08_tb.2_tran_ext/batch_0/ll/tran.csv Index:0 <br>
</details><br>


# Transient Oscillator Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| First High Pulse Duration | 30.0 / 45.575 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="21.690588,10.0,67.982904,10.0" style="stroke:green;stroke-width:2" /><circle cx="21.690588" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="67.982904" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 84.152 / 150.0 | nS | 100/100.0%/0.0%/0.0% |  |
| First Oscillator Period Duration | 60.0 / 99.328 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.596704000000006,10.0,63.1263,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.596704000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="63.1263" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 160.21 / 300.0 | nS | 100/100.0%/0.0%/0.0% |  |
| Duty-Cycle of First Oscillator Period | 30 / 44.73777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.05597199999999,10.0,85.18443599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.05597199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="85.18443599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 52.82901 / 70 | % | 100/100.0%/0.0%/0.0% |  |

<br>

