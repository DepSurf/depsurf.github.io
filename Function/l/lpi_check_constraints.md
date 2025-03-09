# Function: <code>lpi_check_constraints</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584322877,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:838",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_s2idle_wake"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584544390,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:868",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584641638,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:865",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584841430,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:855",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584977267,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:846",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672528,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:849",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672528,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898192,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:288",
      "file": "drivers/acpi/x86/s2idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898192,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775056,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:290",
      "file": "drivers/acpi/x86/s2idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775056,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586258512,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:290",
      "file": "drivers/acpi/x86/s2idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586258512,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587500416,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:292",
      "file": "drivers/acpi/x86/s2idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587500416,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void lpi_check_constraints()
```

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772880,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:293",
      "file": "drivers/acpi/x86/s2idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772880,
      "name": "lpi_check_constraints",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589063642,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:287",
      "file": "drivers/acpi/x86/s2idle.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589368790,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/x86/s2idle.c:326",
      "file": "drivers/acpi/x86/s2idle.c",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584831075,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:846",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584928851,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:846",
      "file": "drivers/acpi/sleep.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lpi_check_constraints",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585034995,
      "name": "lpi_check_constraints",
      "external": false,
      "loc": "drivers/acpi/sleep.c:846",
      "file": "drivers/acpi/sleep.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void lpi_check_constraints()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void lpi_check_constraints()
```
</details>
</li>
</ul>
