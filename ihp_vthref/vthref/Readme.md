16.07.2025, 06:23:26

# Vth Current Reference

3 uA current reference with source- and sink-port.

![vthref](resources/vthref.png "vthref")

<br>

[🔗 Schematics](vthref_sch.pdf)<br>
<details><summary>Show Tool Versions...</summary>

> xschem: 3.4.6<br>
> ngspice: 44.2<br>
> magic: 8.3.530<br>
> netgen: 1.5.293<br>
> ihpopenpdk: dev<br>
</details><br>


# LVS
LVS-state: Netlists match uniquely.<br>

[🔗 LVS-report](vthref_vthref_netgen_comp.out)<br>

# SPECIFICATIONS

## Transient Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 9.732 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="26.3560032,10.0,45.390192000000006,10.0" style="stroke:green;stroke-width:2" /><circle cx="26.3560032" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="45.390192000000006" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.663 / 60.0 | us | 99/100.0%/0.0%/0.0% |  |

<br>


## DC Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.244 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,84.25001645688991,17,84.25001645688991,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.625008228444955,10.0,43.625008228444955,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.603226754125789,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="9.603226754125789" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.317 / 3.0 | uA | 99/97.9798%/2.0202%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.246 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,84.23709044847388,17,84.23709044847388,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="43.61854522423694,10.0,43.61854522423694,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.660794227954286,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="9.660794227954286" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 5.318 / 3.0 | uA | 99/97.9798%/2.0202%/0.0% |  |
| Max. Output Current (Source) | 1.0 / 3.915 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.16454254545455,10.0,143.06657454545456,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.16454254545455" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.06657454545456" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.7 / 12.0 | uA | 99/100.0%/0.0%/0.0% |  |
| Min. Output Current (Source) | 1.0 / -0.0 | <svg height="20" width="150"><polyline points="17.40000253233211,3,17.40000253233211,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.20000126616605,10.0,82.20000126616605,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,137.9479153768741,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="137.9479153768741" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9.371 / 10.0 | uA | 99/97.9798%/2.0202%/0.0% |  |
| Max. Output Current (Sink) | 1.0 / 3.917 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="41.18084072727273,10.0,143.7744,10.0" style="stroke:green;stroke-width:2" /><circle cx="41.18084072727273" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="143.7744" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 11.754 / 12.0 | uA | 99/100.0%/0.0%/0.0% |  |
| Min. Output Current (Sink) | 1.0 / -0.0 | <svg height="20" width="150"><polyline points="17.401740336149544,3,17.401740336149544,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="82.20087016807477,10.0,82.20087016807477,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.0,10.0,138.58545859635217,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="138.58545859635217" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 9.416 / 10.0 | uA | 99/97.9798%/2.0202%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Sink)":<br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Source)":<br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "Min. Output Current (Source)":<br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "Min. Output Current (Sink)":<br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.1_dc/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
</details><br>


## DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.269 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.6107136,10.0,120.482528,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.6107136" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.482528" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.671 / 4.5 | uA | 1000/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.265 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="11.4762272,10.0,120.266304,10.0" style="stroke:green;stroke-width:2" /><circle cx="11.4762272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="120.266304" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 3.665 / 4.5 | uA | 1000/100.0%/0.0%/0.0% |  |
| Max. Output Current (Source) | 1.0 / 3.289 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="24.978912,10.0,112.363776,10.0" style="stroke:green;stroke-width:2" /><circle cx="24.978912" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.363776" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.392 / 16.0 | uA | 1000/100.0%/0.0%/0.0% |  |
| Min. Output Current (Source) | 0.5 / 1.233 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.174327652173913,10.0,116.7140452173913,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.174327652173913" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="116.7140452173913" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.581 / 12.0 | uA | 1000/100.0%/0.0%/0.0% |  |
| Max. Output Current (Sink) | 1.0 / 3.321 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.286159999999995,10.0,112.894272,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.286159999999995" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="112.894272" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 12.447 / 16.0 | uA | 1000/100.0%/0.0%/0.0% |  |
| Min. Output Current (Sink) | 0.5 / 1.258 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="12.488448,10.0,117.27290295652175,10.0" style="stroke:green;stroke-width:2" /><circle cx="12.488448" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="117.27290295652175" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 9.626 / 12.0 | uA | 1000/100.0%/0.0%/0.0% |  |

<br>


## DC Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.392 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,63.00587557531674,17,63.00587557531674,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="33.00293778765837,10.0,33.00293778765837,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="10.836863359537286,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="10.836863359537286" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 7.199 / 3.0 | uA | 99/70.7071%/29.2929%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.4 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,38.824252189467174,17,38.824252189467174,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="20.912126094733587,10.0,20.912126094733587,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="7.774040154674526,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="7.774040154674526" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 12.059 / 3.0 | uA | 99/67.6768%/32.3232%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Sink)":<br>
> **FAIL:** group:h-tt_l-tt_b-typ_r-typ_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-tt_l-tt_b-typ_r-typ_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-ss_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ff_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ff_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-sf_l-ff_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ff_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-fs_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-fs_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-fs_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Source)":<br>
> **FAIL:** group:h-tt_l-tt_b-typ_r-typ_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-tt_l-tt_b-typ_r-typ_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-ss_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-ss_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ss_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ss_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ff_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ff_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-ff_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-ff_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-ff_l-fs_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-ff_l-fs_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-sf_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-sf_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-sf_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ss_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ss_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ss_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ss_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-ff_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-ff_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:1 <br>
> **FAIL:** group:h-fs_l-sf_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-sf_b-typ_r-bcs_c-typ/dc.csv Index:2 <br>
> **FAIL:** group:h-fs_l-fs_b-typ_r-wcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-fs_b-typ_r-wcs_c-typ/dc.csv Index:0 <br>
> **FAIL:** group:h-fs_l-fs_b-typ_r-bcs_c-typ file:work/sim/vthref/vthref_tb.5_dcext/batch_0/h-fs_l-fs_b-typ_r-bcs_c-typ/dc.csv Index:0 <br>
</details><br>


## Transient Specification (PEX)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Startup Time | 0.0 / 9.411 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="25.585404,10.0,44.932392,10.0" style="stroke:green;stroke-width:2" /><circle cx="25.585404" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="44.932392" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 17.472 / 60.0 | us | 99/100.0%/0.0%/0.0% |  |

<br>


# PERFORMANCE CHARACTERISTICS

## DC Performance<br>

| ![xyplot_f317c35da26492f0b2564c148cb17756_ceebb7408b00e8507fe2a1764edde119](xyplot_f317c35da26492f0b2564c148cb17756_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |


| ![xyplot_5f00563900609c508dc0f840c82f10f1_ceebb7408b00e8507fe2a1764edde119](xyplot_5f00563900609c508dc0f840c82f10f1_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |


| ![xyplot_557aa1eda6d043d5cf946fe5bc580e93_ceebb7408b00e8507fe2a1764edde119](xyplot_557aa1eda6d043d5cf946fe5bc580e93_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_fb34c7afc52d0d9fcdc14f7c30f15b76_ceebb7408b00e8507fe2a1764edde119](xyplot_fb34c7afc52d0d9fcdc14f7c30f15b76_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_651cbc9a4b63ad26e4314ecc79819347_ceebb7408b00e8507fe2a1764edde119](xyplot_651cbc9a4b63ad26e4314ecc79819347_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>

| ![xyplot_2e159e36332d2cdf615a405d77819f66_ceebb7408b00e8507fe2a1764edde119](xyplot_2e159e36332d2cdf615a405d77819f66_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_1f1023e977944731c4267339fce74ed2_ceebb7408b00e8507fe2a1764edde119](xyplot_1f1023e977944731c4267339fce74ed2_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_e0c67093c799fe735d160e06f6c45278_ceebb7408b00e8507fe2a1764edde119](xyplot_e0c67093c799fe735d160e06f6c45278_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>

| ![xyplot_cbc299d7f601da37fdc8d69098eac452_ceebb7408b00e8507fe2a1764edde119](xyplot_cbc299d7f601da37fdc8d69098eac452_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_3a7bbd145bf96332fae43fc7bef80585_ceebb7408b00e8507fe2a1764edde119](xyplot_3a7bbd145bf96332fae43fc7bef80585_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_ab07605d9ba7ec46bd1078e8c415abaf_ceebb7408b00e8507fe2a1764edde119](xyplot_ab07605d9ba7ec46bd1078e8c415abaf_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>

| ![xyplot_e2cf4f3c46ec43968379404b09d2a8ac_ceebb7408b00e8507fe2a1764edde119](xyplot_e2cf4f3c46ec43968379404b09d2a8ac_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_e88c93cc2907acc9ba01551be9706bae_ceebb7408b00e8507fe2a1764edde119](xyplot_e88c93cc2907acc9ba01551be9706bae_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_35c7a2aa7454c5055f3b90887707438f_ceebb7408b00e8507fe2a1764edde119](xyplot_35c7a2aa7454c5055f3b90887707438f_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |

</details>
<br>

| ![xyplot_f4d87d732aef60de402e5bdfd2d5b74a_ceebb7408b00e8507fe2a1764edde119](xyplot_f4d87d732aef60de402e5bdfd2d5b74a_ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |


| ![occtplot_temp-sweep_('h-tt_l-tt_b-typ_r-typ_c-typ',_-2)__ceebb7408b00e8507fe2a1764edde119](occtplot_temp-sweep_('h-tt_l-tt_b-typ_r-typ_c-typ',_-2)__ceebb7408b00e8507fe2a1764edde119.png "") |
| :-- |
|  |


## DC Performance (Monte Carlo)<br>

| ![histplot_sink_ppgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_sink_ppgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


| ![histplot_source_ppgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_source_ppgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


| ![histplot_source_maxgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_source_maxgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


| ![histplot_source_mingroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_source_mingroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


| ![histplot_sink_maxgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_sink_maxgroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


| ![histplot_sink_mingroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4](histplot_sink_mingroup_('tt_typ_stat_mc',_-2),_('tt_typ_mismatch_mc',_-2)__02225623633d0f6307e0649078c055a4.png "") |
| :-- |
|  |


## Transient Performance<br>

| ![xyplot_d7a71760aa3d399d3095571e937329e3_9e35878250679f74019b3b8bd75e019a](xyplot_d7a71760aa3d399d3095571e937329e3_9e35878250679f74019b3b8bd75e019a.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_2add7d3d9c0cd245c747b5fc0545ed07_9e35878250679f74019b3b8bd75e019a](xyplot_2add7d3d9c0cd245c747b5fc0545ed07_9e35878250679f74019b3b8bd75e019a.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_332205bd2ed16523a9e91f059ae6427c_9e35878250679f74019b3b8bd75e019a](xyplot_332205bd2ed16523a9e91f059ae6427c_9e35878250679f74019b3b8bd75e019a.png "") |
| :-- |
|  |

</details>
<br>

## AC Noise<br>

| ![xyplot_77e18bab5f89f6de6a70c1bb95be60fd_75b7a2d8199a5a9a1b556c4fd90b475f](xyplot_77e18bab5f89f6de6a70c1bb95be60fd_75b7a2d8199a5a9a1b556c4fd90b475f.png "") |
| :-- |
|  |


| ![xyplot_77e18bab5f89f6de6a70c1bb95be60fd_3d26ca5289fa041cea8e36b1f835bed2](xyplot_77e18bab5f89f6de6a70c1bb95be60fd_3d26ca5289fa041cea8e36b1f835bed2.png "") |
| :-- |
|  |


## Transient Performance (PEX)<br>

| ![xyplot_d7a71760aa3d399d3095571e937329e3_3dffd9ff0eafc26799132922d571475c](xyplot_d7a71760aa3d399d3095571e937329e3_3dffd9ff0eafc26799132922d571475c.png "") |
| :-- |
|  |

<details><summary>...</summary>

| ![xyplot_2add7d3d9c0cd245c747b5fc0545ed07_3dffd9ff0eafc26799132922d571475c](xyplot_2add7d3d9c0cd245c747b5fc0545ed07_3dffd9ff0eafc26799132922d571475c.png "") |
| :-- |
|  |

</details>
<br>
<details><summary>...</summary>

| ![xyplot_332205bd2ed16523a9e91f059ae6427c_3dffd9ff0eafc26799132922d571475c](xyplot_332205bd2ed16523a9e91f059ae6427c_3dffd9ff0eafc26799132922d571475c.png "") |
| :-- |
|  |

</details>
<br>
