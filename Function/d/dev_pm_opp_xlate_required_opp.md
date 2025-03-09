# Function: <code>dev_pm_opp_xlate_required_opp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2478",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591539686,
      "name": "dev_pm_opp_xlate_required_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588770800,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2488",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:devfreq_passive_get_target_freq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592654085,
      "name": "dev_pm_opp_xlate_required_opp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589462624,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590942992,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2628",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590942992,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592643360,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2625",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592643360,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593073376,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2633",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593073376,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```

```json
{
  "name": "dev_pm_opp_xlate_required_opp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593825296,
      "name": "dev_pm_opp_xlate_required_opp",
      "external": true,
      "loc": "drivers/opp/core.c:2718",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_passive.c:get_target_freq_by_required_opp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593825296,
      "name": "dev_pm_opp_xlate_required_opp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct dev_pm_opp * dev_pm_opp_xlate_required_opp(struct opp_table * src_table, struct opp_table * dst_table, struct dev_pm_opp * src_opp)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
