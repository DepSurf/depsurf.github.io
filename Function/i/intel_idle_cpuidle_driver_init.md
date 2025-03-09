# Function: <code>intel_idle_cpuidle_driver_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595230228,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1114",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595408403,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1312",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595658318,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596580679,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1327",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602908650,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1338",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603080548,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1338",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604882810,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1335",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604989054,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604989054,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605026322,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605026322,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609316161,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1500",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612386770,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1565",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614528508,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1566",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615478946,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1599",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617281526,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1860",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627992979,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1926",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619758609,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1957",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622065953,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:2068",
      "file": "drivers/idle/intel_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604931454,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604931454,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604900006,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604900006,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 734
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605008910,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605008910,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void intel_idle_cpuidle_driver_init()
```

```json
{
  "name": "intel_idle_cpuidle_driver_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605030502,
      "name": "intel_idle_cpuidle_driver_init",
      "external": false,
      "loc": "drivers/idle/intel_idle.c:1324",
      "file": "drivers/idle/intel_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605030502,
      "name": "intel_idle_cpuidle_driver_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_idle_cpuidle_driver_init()
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
