# Function: <code>_find_key</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct dev_pm_opp * _find_key(struct device * dev, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592640528,
      "name": "_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:529",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592640528,
      "name": "_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct dev_pm_opp * _find_key(struct device * dev, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593071024,
      "name": "_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:532",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593071024,
      "name": "_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
struct dev_pm_opp * _find_key(struct device * dev, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593822336,
      "name": "_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:531",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_floor",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor_indexed",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_indexed",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact_indexed",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593822336,
      "name": "_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct dev_pm_opp * _find_key(struct device * dev, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
