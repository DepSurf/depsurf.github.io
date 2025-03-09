# Function: <code>find_mem_target</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct memory_target * find_mem_target(unsigned int mem_pxm)
```

```json
{
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605008822,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:66",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605008822,
      "name": "find_mem_target",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585378524,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:78",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_callback",
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586087116,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:85",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:hmat_parse_subtable",
        "drivers/acpi/numa/hmat.c:alloc_memory_target"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586208492,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:93",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:hmat_parse_subtable",
        "drivers/acpi/numa/hmat.c:alloc_memory_target"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586083180,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:93",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/numa/hmat.c:hmat_parse_subtable"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586580348,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:93",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587840428,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:93",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589182668,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:92",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589476748,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:92",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:srat_parse_mem_affinity"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622096530,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/numa/hmat.c:101",
      "file": "drivers/acpi/numa/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/hmat.c:hmat_init",
        "drivers/acpi/numa/hmat.c:hmat_calculate_adistance",
        "drivers/acpi/numa/hmat.c:hmat_callback",
        "drivers/acpi/numa/hmat.c:alloc_target"
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
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497652748,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:78",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_callback",
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585170492,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:78",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_callback",
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585113484,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:78",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_callback",
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_mem_target",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585436252,
      "name": "find_mem_target",
      "external": false,
      "loc": "drivers/acpi/hmat/hmat.c:78",
      "file": "drivers/acpi/hmat/hmat.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/hmat/hmat.c:hmat_callback",
        "drivers/acpi/hmat/hmat.c:srat_parse_mem_affinity",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable",
        "drivers/acpi/hmat/hmat.c:hmat_parse_subtable"
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct memory_target * find_mem_target(unsigned int mem_pxm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
struct memory_target * find_mem_target(unsigned int mem_pxm)
```
</details>
</li>
</ul>
