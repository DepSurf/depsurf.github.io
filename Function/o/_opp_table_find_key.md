# Function: <code>_opp_table_find_key</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * _opp_table_find_key(struct opp_table * opp_table, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_opp_table_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:495",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:_find_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592639136,
      "name": "_opp_table_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071596313221,
      "name": "_opp_table_find_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * _opp_table_find_key(struct opp_table * opp_table, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_opp_table_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:498",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:_find_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593069632,
      "name": "_opp_table_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071596842075,
      "name": "_opp_table_find_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
struct dev_pm_opp * _opp_table_find_key(struct opp_table * opp_table, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
```

```json
{
  "name": "_opp_table_find_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_opp_table_find_key",
      "external": false,
      "loc": "drivers/opp/core.c:497",
      "file": "drivers/opp/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:_find_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593820944,
      "name": "_opp_table_find_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    },
    {
      "addr": 18446744071597767076,
      "name": "_opp_table_find_key.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
struct dev_pm_opp * _opp_table_find_key(struct opp_table * opp_table, long unsigned int * key, int index, bool available, long unsigned int (*)(struct dev_pm_opp *, int) read, bool (*)(struct dev_pm_opp * *, struct dev_pm_opp *, long unsigned int, long unsigned int) compare, bool (*)(struct opp_table *) assert)
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
