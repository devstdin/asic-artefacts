
# DC Specification<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.119 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.4230592,10.0,137.588736,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.4230592" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="137.588736" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.402 / 1.5 | uA | 27/100.0%/0.0%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.12 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,147.0,17,147.0,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="75.0,10.0,75.0,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="14.5368768,10.0,136.578048,10.0" style="stroke:green;stroke-width:2" /><circle cx="14.5368768" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /><circle cx="136.578048" cy="10.0" r="3" style="fill:green;stroke:green;stroke-width:0" /></svg> | 1.391 / 1.5 | uA | 27/100.0%/0.0%/0.0% |  |

<br>


# DC Specification (Monte Carlo)<br>

| Parameter | Min (Spec. / Sim.) |      | Max (Sim. / Spec.) | Unit | Checks (total/pass/fail/NaN) | Comment |
| :-------- | -----------------: | :--: | :----------------- | :--- | :--------------------------- | ------- |
| Output Current Curvature (Sink) | 0.0 / 0.044 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,13.871841126161677,17,13.871841126161677,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="8.435920563080838,10.0,8.435920563080838,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.3210923623302784,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.3210923623302784" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 19.868 / 1.5 | uA | 2000/84.05%/15.95%/0.0% |  |
| Output Current Curvature (Source) | 0.0 / 0.043 | <svg height="20" width="150"><polyline points="3.0,3,3.0,17,15.679032636769195,17,15.679032636769195,3" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="9.339516318384597,10.0,9.339516318384597,17" style="fill:none;stroke:gray;stroke-width:1" /><polyline points="3.363016257337403,10.0,147.0,10.0" style="stroke:red;stroke-width:2" /><circle cx="3.363016257337403" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /><circle cx="147.0" cy="10.0" r="3" style="fill:red;stroke:red;stroke-width:0" /></svg> | 17.036 / 1.5 | uA | 2000/83.8%/16.2%/0.0% |  |

<details><summary>Show specification violation details...</summary>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Sink)":<br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:7 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:8 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:10 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:11 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:13 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:16 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:19 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:22 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:23 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:25 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:26 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:29 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:35 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:36 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:37 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:38 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:44 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:50 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:53 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:54 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:55 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:58 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:61 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:70 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:82 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:88 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:90 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:95 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:98 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:5 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:9 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:14 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:15 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:16 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:18 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:20 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:24 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:27 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:29 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:30 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:31 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:32 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:37 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:40 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:44 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:45 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:47 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:48 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:51 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:55 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:57 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:60 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:61 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:62 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:63 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:67 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:70 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:71 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:73 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:75 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:77 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:79 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:81 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:82 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:85 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:86 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:90 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:97 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:98 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:99 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:3 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:5 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:8 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:9 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:20 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:23 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:24 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:26 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:29 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:30 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:32 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:34 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:38 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:40 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:45 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:47 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:55 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:57 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:59 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:62 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:64 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:74 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:75 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:80 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:88 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:89 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:90 <br>

> **FAIL:** Specification violation for parameter "Output Current Curvature (Source)":<br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:2 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:7 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:8 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:10 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:16 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:18 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:19 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:21 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:22 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:25 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:26 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:29 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:31 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:38 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:43 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:46 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:50 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:52 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:53 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:55 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:58 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:61 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:67 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:70 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:71 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:72 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:77 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:82 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:88 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:92 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:93 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:95 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_6/tt_typ_stat_mc/dc.csv Index:98 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:3 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:5 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:12 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:14 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:15 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:18 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:19 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:20 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:24 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:25 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:29 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:30 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:33 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:34 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:37 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:40 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:45 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:50 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:52 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:53 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:55 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:58 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:61 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:66 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:67 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:72 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:75 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:77 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:81 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:85 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:86 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:87 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:90 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:91 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_5/tt_typ_stat_mc/dc.csv Index:97 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:1 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:3 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:8 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:11 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:15 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:19 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:20 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:23 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:24 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:26 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:32 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:33 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:40 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:42 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:57 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:59 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:64 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:67 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:71 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:73 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:74 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:75 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:80 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:88 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:90 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:92 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_3/tt_typ_stat_mc/dc.csv Index:97 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_4/tt_typ_stat_mc/dc.csv Index:6 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_4/tt_typ_stat_mc/dc.csv Index:8 <br>
> **FAIL:** group:tt_typ_stat_mc file:work/sim/vthref/vthref_tb.1_dc/batch_4/tt_typ_stat_mc/dc.csv Index:10 <br>
</details><br>

