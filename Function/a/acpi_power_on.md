# Function: <code>acpi_power_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583598929,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:255",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list",
        "drivers/acpi/power.c:acpi_power_transition"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583923849,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:255",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584064881,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:255",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124704,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:256",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124704,
      "name": "acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584398931,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:256",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584621686,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:256",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584720182,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:278",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584922764,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585058572,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585762057,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:397",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585881148,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:397",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585758215,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:392",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586240952,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:410",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587477569,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:410",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588745233,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:410",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589033629,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:411",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589338189,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:411",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_on_list"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497461944,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497461944,
      "name": "acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
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
int acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584986784,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584986784,
      "name": "acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int acpi_power_on(struct acpi_power_resource * resource)
```

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584902368,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584902368,
      "name": "acpi_power_on",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585010156,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
  "name": "acpi_power_on",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585116332,
      "name": "acpi_power_on",
      "external": false,
      "loc": "drivers/acpi/power.c:399",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_power_transition",
        "drivers/acpi/power.c:acpi_power_on_list"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
int acpi_power_on(struct acpi_power_resource * resource)
```
</details>
</li>
</ul>
