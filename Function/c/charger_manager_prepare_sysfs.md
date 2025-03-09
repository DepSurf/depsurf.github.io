# Function: <code>charger_manager_prepare_sysfs</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587298260,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1366",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587567782,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587771270,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager * cm)
```

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588612432,
      "name": "charger_manager_prepare_sysfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071588619261,
      "name": "charger_manager_prepare_sysfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager * cm)
```

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1173",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634320,
      "name": "charger_manager_prepare_sysfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071591580752,
      "name": "charger_manager_prepare_sysfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588524538,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1173",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589198359,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1173",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590658617,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1170",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592324771,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1170",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592751474,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1170",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593499392,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1170",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500971156,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233484536,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294436716,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277728956,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587727414,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "charger_manager_prepare_sysfs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587840470,
      "name": "charger_manager_prepare_sysfs",
      "external": false,
      "loc": "drivers/power/supply/charger-manager.c:1364",
      "file": "drivers/power/supply/charger-manager.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/power/supply/charger-manager.c:charger_manager_probe"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager * cm)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int charger_manager_prepare_sysfs(struct charger_manager * cm)
```
</details>
</li>
</ul>
