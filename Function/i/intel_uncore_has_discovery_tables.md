# Function: <code>intel_uncore_has_discovery_tables</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool intel_uncore_has_discovery_tables()
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578984720,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:261",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578984720,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
bool intel_uncore_has_discovery_tables()
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:261",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592046167,
      "name": "intel_uncore_has_discovery_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071578999936,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool intel_uncore_has_discovery_tables()
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:269",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593812657,
      "name": "intel_uncore_has_discovery_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579016416,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool intel_uncore_has_discovery_tables()
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:269",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595956068,
      "name": "intel_uncore_has_discovery_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579043744,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
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
bool intel_uncore_has_discovery_tables(int * ignore)
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:289",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596473418,
      "name": "intel_uncore_has_discovery_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579044032,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
bool intel_uncore_has_discovery_tables(int * ignore)
```

```json
{
  "name": "intel_uncore_has_discovery_tables",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_uncore_has_discovery_tables",
      "external": true,
      "loc": "arch/x86/events/intel/uncore_discovery.c:290",
      "file": "arch/x86/events/intel/uncore_discovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/uncore.c:intel_uncore_init",
        "arch/x86/events/intel/uncore.c:intel_uncore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597368760,
      "name": "intel_uncore_has_discovery_tables.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579069328,
      "name": "intel_uncore_has_discovery_tables",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
bool intel_uncore_has_discovery_tables()
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int * ignore</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
