# Function: <code>acpi_thermal_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_thermal_check(void * data)
```

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761812,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761812,
      "name": "acpi_thermal_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void acpi_thermal_check(void * data)
```

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584087751,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584087751,
      "name": "acpi_thermal_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_thermal_check(void * data)
```

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584231198,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231198,
      "name": "acpi_thermal_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305381,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304976,
      "name": "acpi_thermal_check.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584705157,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704576,
      "name": "acpi_thermal_check.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584931381,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930768,
      "name": "acpi_thermal_check.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585035093,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:516",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034672,
      "name": "acpi_thermal_check.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585239013,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:502",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238592,
      "name": "acpi_thermal_check.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585375749,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:497",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585375328,
      "name": "acpi_thermal_check.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586084213,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:499",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode",
        "drivers/acpi/thermal.c:thermal_set_mode"
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497651176,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:497",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497650808,
      "name": "acpi_thermal_check.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585327333,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:497",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585326912,
      "name": "acpi_thermal_check.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_thermal_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585433477,
      "name": "acpi_thermal_check",
      "external": false,
      "loc": "drivers/acpi/thermal.c:497",
      "file": "drivers/acpi/thermal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ],
      "caller_func": [
        "drivers/acpi/thermal.c:acpi_thermal_check_fn",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:acpi_thermal_notify",
        "drivers/acpi/thermal.c:thermal_set_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585433056,
      "name": "acpi_thermal_check.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void acpi_thermal_check(void * data)
```
</details>
</li>
</ul>
