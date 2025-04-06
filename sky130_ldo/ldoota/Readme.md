# LDO OP

OpAmp used in LDO.

![ldoota](resources/ldoota.png "ldoota")

<br>

[🔗 Schematics](ldoota_sch.pdf)<br>

# SPECIFICATIONS

## AC Open-Loop Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.315 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.33302799999999,10.0,56.527752,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.33302799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.527752" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.869 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 91.777 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.51859519999998,10.0,121.336608,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.51859519999998" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="121.336608" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 101.089 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 10.323 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.646016,10.0,90.995376,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.646016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="90.995376" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.111 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.218 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.268261818181816,10.0,26.03656727272727,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.268261818181816" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.03656727272727" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.684 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.167 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.80274799999999,10.0,56.967168000000015,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.80274799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.967168000000015" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.991 / 100 | dB | 500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 90.15 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.83110720000002,10.0,124.332672,10.0" style="stroke:green;stroke-width:2" /><circle cx="89.83110720000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="124.332672" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 102.129 / 110 | deg | 500/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 9.004 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.658607999999994,10.0,129.12139200000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.658607999999994" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="129.12139200000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 13.758 / 15.0 | MHz | 500/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.154 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.330865454545453,10.0,27.498254545454547,10.0" style="stroke:green;stroke-width:2" /><circle cx="18.330865454545453" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.498254545454547" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.784 / 10.0 | kHz | 500/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.708 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.618799999999993,10.0,27.7513088,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.618799999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.7513088" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.8 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.732 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="94.66816800000001,10.0,100.41304799999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="94.66816800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="100.41304799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 43.53 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.105 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.168016,10.0,6.982255999999995,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.168016" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.982255999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.239 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.236 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="73.3029312,10.0,75.68119423200001,10.0" style="stroke:green;stroke-width:2" /><circle cx="73.3029312" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="75.68119423200001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.095 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.801 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.76604800000001,10.0,89.13287999999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.76604800000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.13287999999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.963 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 28.016 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="60.716928,10.0,71.80536000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="60.716928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.80536000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.556 / 40 | dB | 5/100.0%/0.0%/0.0% |  |

<br>


## CMRR/PSRR Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 62.372 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.8154928,10.0,31.684814400000008,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.8154928" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="31.684814400000008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 69.92 / 150 | dB | 500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 42.395 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="92.244072,10.0,111.720792,10.0" style="stroke:green;stroke-width:2" /><circle cx="92.244072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="111.720792" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 45.1 / 50 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 39.98 | <svg height="20" width="150"><polyline points="3.03224877627411,3,3.03224877627411,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.01612438813706,10.0,75.01612438813706,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,5.151374092203344,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="5.151374092203344" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 41.325 / 130 | dB | 500/96.0%/4.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -0.479 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="71.55373440000001,10.0,78.35446056,10.0" style="stroke:green;stroke-width:2" /><circle cx="71.55373440000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="78.35446056" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.466 / 10 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.687 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.947408,10.0,91.89141599999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.947408" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="91.89141599999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.346 / 50 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 27.879 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="59.727143999999996,10.0,74.5914,10.0" style="stroke:green;stroke-width:2" /><circle cx="59.727143999999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="74.5914" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 29.943 / 40 | dB | 500/100.0%/0.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR+ at 10Hz":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota/batch_0/ff_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
</details><br>


## Output Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.856 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.847039999999993,10.0,107.71296,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.847039999999993" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="107.71296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.909 / -1.5 | V | 5/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.67139199999997,10.0,146.73302400000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.67139199999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.73302400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 5/100.0%/0.0%/0.0% |  |

<br>


## Output Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative Output Bound | -3 / -2.862 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="16.29024000000001,10.0,127.16640000000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="16.29024000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="127.16640000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -1.707 / -1.5 | V | 500/100.0%/0.0%/0.0% |  |
| Positive Output Bound | 2.5 / 2.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="144.66160000000002,10.0,146.738208,10.0" style="stroke:green;stroke-width:2" /><circle cx="144.66160000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="146.738208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 2.999 / 3 | V | 500/100.0%/0.0%/0.0% |  |

<br>


## Input Range Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.114 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="88.08768,10.0,95.27424000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="88.08768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.27424000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.039 / -1.5 | V | 5/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Input Range Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Negative CM Input Bound | -3 / -2.12 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.44352,10.0,95.856,10.0" style="stroke:green;stroke-width:2" /><circle cx="87.44352" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="95.856" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.033 / -1.5 | V | 500/100.0%/0.0%/0.0% | Input transistor sat. |

<br>


## Slew-Rate/Offset Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.999 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.99600400000003,10.0,137.271684,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.99600400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.271684" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.298 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.293 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.032384,10.0,38.062152,10.0" style="stroke:green;stroke-width:2" /><circle cx="10.032384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="38.062152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.461 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.182 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="125.72472,10.0,137.13258,10.0" style="stroke:green;stroke-width:2" /><circle cx="125.72472" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.13258" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.548 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 11.38 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="115.969728,10.0,143.055984,10.0" style="stroke:green;stroke-width:2" /><circle cx="115.969728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.055984" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.904 / 20.0 | mV | 500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.132 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.168048000000001,10.0,41.301336,10.0" style="stroke:green;stroke-width:2" /><circle cx="6.168048000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.301336" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.596 / 10.0 | MV/s | 500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.237 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="124.74174000000001,10.0,137.52552,10.0" style="stroke:green;stroke-width:2" /><circle cx="124.74174000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.52552" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.526 / -2.0 | MV/s | 500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.6334976,10.0,22.653622399999996,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.6334976" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.653622399999996" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.226 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.4958776,10.0,13.941119839999999,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.4958776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.941119839999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.2846096,10.0,17.6246448,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.2846096" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="17.6246448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.03 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) <br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.02 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.4063824,10.0,19.5471072,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.4063824" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="19.5471072" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.034 / 0.3 | % | 500/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.303 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="47.29015199999999,10.0,56.49862800000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="47.29015199999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.49862800000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.861 / 100 | dB | 5/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / 78.486 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="56.23872959999999,10.0,79.68146880000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="56.23872959999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="79.68146880000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 86.626 / 110 | deg | 5/100.0%/0.0%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 10.179 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="77.575296,10.0,87.313008,10.0" style="stroke:green;stroke-width:2" /><circle cx="77.575296" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="87.313008" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 10.855 / 15.0 | MHz | 5/100.0%/0.0%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.217 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.243563636363636,10.0,26.00768,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.243563636363636" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="26.00768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.682 / 10.0 | kHz | 5/100.0%/0.0%/0.0% |  |

<br>


## AC Open-Loop Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Open-Loop Gain | 60 / 72.19 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="46.88432399999999,10.0,56.958096000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="46.88432399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="56.958096000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 74.988 / 100 | dB | 500/100.0%/0.0%/0.0% | Gain at 1Hz |
| Phase Margin | 60 / -102.738 | <svg height="20" width="150"><polyline points="113.15555283964314,3,113.15555283964314,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="130.07777641982156,10.0,130.07777641982156,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,132.82455790690898,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="132.82455790690898" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 89.058 / 110 | deg | 500/99.6%/0.4%/0.0% | Open-Loop |
| Unity-Gain Bandwidth | 5.0 / 8.923 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,34.499239096505576,17,34.499239096505576,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="18.749619548252788,10.0,18.749619548252788,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="15.355919877310464,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="15.355919877310464" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 50.715 / 15.0 | MHz | 500/99.6%/0.4%/0.0% |  |
| 3-dB Bandwidth | 0.1 / 1.152 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,10.780321615006153,17,10.780321615006153,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="6.890160807503077,10.0,6.890160807503077,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.8268847223321316,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.8268847223321316" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 183.332 / 10.0 | kHz | 500/99.6%/0.4%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Phase Margin":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_4/ff_mm/ldoota_ac_ol.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_2/ff_mm/ldoota_ac_ol.csv Index:8 <br>

> **FAIL:** Specification violation for parameter "Unity-Gain Bandwidth":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_4/ff_mm/ldoota_ac_ol.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_2/ff_mm/ldoota_ac_ol.csv Index:8 <br>

> **FAIL:** Specification violation for parameter "3-dB Bandwidth":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_4/ff_mm/ldoota_ac_ol.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.1_ldoota_ext/batch_2/ff_mm/ldoota_ac_ol.csv Index:8 <br>
</details><br>


## CMRR/PSRR Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 65.721 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.637534400000007,10.0,27.780526400000007,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.637534400000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="27.780526400000007" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 65.82 / 150 | dB | 5/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 38.948 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="67.42416000000001,10.0,70.18318400000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="67.42416000000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="70.18318400000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 39.053 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.095 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.152639999999997,10.0,6.974832000000004,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.152639999999997" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="6.974832000000004" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.234 / 130 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.13 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="66.865872,10.0,69.6789912,10.0" style="stroke:green;stroke-width:2" /><circle cx="66.865872" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="69.6789912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.739 / 10 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.79 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="80.688,10.0,89.08852800000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="80.688" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="89.08852800000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.957 / 50 | dB | 5/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 15.995 | <svg height="20" width="150"><polyline points="27.024794875725686,3,27.024794875725686,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="87.01239743786284,10.0,87.01239743786284,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,7.598829575221116,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="7.598829575221116" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 16.762 / 40 | dB | 5/0.0%/100.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR- at 10MHz":<br>
> **FAIL:** group:ff file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ff/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:hh file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/hh/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:tt file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/tt/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ll file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ll/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ss file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_0/ss/ldoota_ac_cmrr_psrr.csv Index:0 <br>
</details><br>


## CMRR/PSRR Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| CMRR at 10Hz | 50 / 61.862 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.081121600000003,10.0,34.2318288,10.0" style="stroke:green;stroke-width:2" /><circle cx="20.081121600000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="34.2318288" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 71.689 / 150 | dB | 500/100.0%/0.0%/0.0% |  |
| CMRR at 10MHz | 30 / 37.222 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="54.99494399999999,10.0,73.66555200000003,10.0" style="stroke:green;stroke-width:2" /><circle cx="54.99494399999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="73.66555200000003" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 39.815 / 50 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10Hz | 40 / 40.012 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0186079999999946,10.0,5.130640000000005,10.0" style="stroke:green;stroke-width:2" /><circle cx="3.0186079999999946" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="5.130640000000005" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 41.332 / 130 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR+ at 10MHz | -10 / -1.536 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="63.941232,10.0,71.71232160000001,10.0" style="stroke:green;stroke-width:2" /><circle cx="63.941232" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="71.71232160000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -0.457 / 10 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR- at 10Hz | 30 / 40.685 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="79.93300799999999,10.0,92.37597600000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="79.93300799999999" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="92.37597600000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 42.413 / 50 | dB | 500/100.0%/0.0%/0.0% |  |
| PSRR- at 10MHz | 20 / 14.93 | <svg height="20" width="150"><polyline points="32.11982640329323,3,32.11982640329323,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="89.55991320164662,10.0,89.55991320164662,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,15.96037910457287,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="15.96037910457287" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 17.187 / 40 | dB | 500/0.0%/100.0%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "PSRR- at 10MHz":<br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ff_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ff_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ss_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ss_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:hh_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/hh_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:tt_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/tt_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:0 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:1 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:2 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:3 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:4 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:5 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:6 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:7 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:8 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:9 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:10 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:11 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:12 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:13 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:14 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:15 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:16 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:17 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:18 <br>
> **FAIL:** group:ll_mm file:work/sim/ldoota/ldoota_tb.2_ldoota_ext/batch_4/ll_mm/ldoota_ac_cmrr_psrr.csv Index:19 <br>
</details><br>


## Slew-Rate/Offset Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 14.984 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.941968,10.0,137.278848,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.941968" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.278848" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.3 / 20.0 | mV | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.291 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.991152,10.0,37.941576,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.991152" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="37.941576" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.456 / 10.0 | MV/s | 5/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -2.983 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="129.30438,10.0,139.45422,10.0" style="stroke:green;stroke-width:2" /><circle cx="129.30438" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="139.45422" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.419 / -2.0 | MV/s | 5/100.0%/0.0%/0.0% |  |

<br>


## Slew-Rate/Offset Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Offset | -20.0 / 10.083 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="111.298908,10.0,141.266388,10.0" style="stroke:green;stroke-width:2" /><circle cx="111.298908" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="141.266388" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 18.407 / 20.0 | mV | 500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Positive) | 4.0 / 4.27 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.482568,10.0,41.337024,10.0" style="stroke:green;stroke-width:2" /><circle cx="9.482568" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="41.337024" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 5.597 / 10.0 | MV/s | 500/100.0%/0.0%/0.0% |  |
| Slew-Rate (Negative) | -10.0 / -3.03 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="128.46738,10.0,139.64430000000002,10.0" style="stroke:green;stroke-width:2" /><circle cx="128.46738" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="139.64430000000002" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | -2.409 / -2.0 | MV/s | 500/100.0%/0.0%/0.0% |  |

<br>


## Noise Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Input Noise at 10Hz | 0.0 / 1.155 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="19.62876,10.0,22.6628384,10.0" style="stroke:green;stroke-width:2" /><circle cx="19.62876" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="22.6628384" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.227 / 10.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |
| Input Noise at 10MHz | 0.0 / 0.059 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.49693888,10.0,13.94750624,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.49693888" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="13.94750624" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.062 / 1.0 | uV/sqrt(Hz) | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.023 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="13.931030400000001,10.0,18.7432512,10.0" style="stroke:green;stroke-width:2" /><circle cx="13.931030400000001" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="18.7432512" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.033 / 0.3 | % | 5/100.0%/0.0%/0.0% |  |

<br>


## THD Specification (Monte Carlo) [PEX]<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| THD | 0 / 0.021 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.8924208,10.0,20.455728,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.8924208" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="20.455728" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 0.036 / 0.3 | % | 498/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## AC Open-Loop Performance<br>

| ![xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e](xyplot_frequencyvec_ampdbgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__fa85d0e9390d57bbdc389bd17fc02e0e.png "") |
| :-- |
|  |
<br>

## AC Open-Loop Performance (Monte Carlo)<br>

| ![histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1](histplot_olgain_1hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1.png "") |
| :-- |
|  |
<br>

| ![histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1](histplot_pmgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1.png "") |
| :-- |
|  |
<br>

| ![histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1](histplot_ugbwgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1.png "") |
| :-- |
|  |
<br>

| ![histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1](histplot_f2_3dbgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__c25c530d14ee36ac14e95326ab443ef1.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance<br>

| ![xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencycmrrgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencypsrr_pgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

| ![xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35](xyplot_frequencypsrr_ngroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__1da4491da2a63bc6f3bdca22c884fe35.png "") |
| :-- |
|  |
<br>

## CMRR/PSRR Performance (Monte Carlo)<br>

| ![histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_cmrr_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

| ![histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_cmrr_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_psrr_p_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_psrr_p_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_psrr_n_10hzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

| ![histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902](histplot_psrr_n_10mhzgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__6e11446105651d74954e3eeafee05902.png "") |
| :-- |
|  |
<br>

## Output Range Performance (Monte Carlo)<br>

| ![histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__99f7eef75cf3de6b9726abd5cd450aff](histplot_neg_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__99f7eef75cf3de6b9726abd5cd450aff.png "") |
| :-- |
|  |
<br>

| ![histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__99f7eef75cf3de6b9726abd5cd450aff](histplot_pos_out_compgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__99f7eef75cf3de6b9726abd5cd450aff.png "") |
| :-- |
|  |
<br>

## Input Range Performance (Monte Carlo)<br>

| ![histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f48005cd7c62d27b98829d05c5bce662](histplot_neg_cm_boundgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__f48005cd7c62d27b98829d05c5bce662.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance<br>

| ![xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6](xyplot_timev(opout_10f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6.png "") |
| :-- |
|  |
<br>

| ![xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6](xyplot_timev(opout_500f)group_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__7ac8ac6694ffa6dd8e854fb95dac80b6.png "") |
| :-- |
|  |
<br>

## Slew-Rate/Offset Performance (Monte Carlo)<br>

| ![histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc](histplot_inp_offsetgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc](histplot_slew_posgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc.png "") |
| :-- |
|  |
<br>

| ![histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc](histplot_slew_neggroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__9d1c4389b39df90bcacb3973cc2139bc.png "") |
| :-- |
|  |
<br>

## Noise Performance<br>

| ![xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae](xyplot_frequencyinoise_spectrumgroup_('ff',_-2),_('hh',_-2),_('tt',_-2),_('ll',_-2),_('ss',_-2)__452d3dc177265d4ca87b7a218428cdae.png "") |
| :-- |
|  |
<br>

## THD Performance (Monte Carlo)<br>

| ![histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__559d5617bd3336f65d76abebe03f6c4d](histplot_thdgroup_('ff_mm',_-2),_('hh_mm',_-2),_('tt_mm',_-2),_('ll_mm',_-2),_('ss_mm',_-2)__559d5617bd3336f65d76abebe03f6c4d.png "") |
| :-- |
|  |
<br>
