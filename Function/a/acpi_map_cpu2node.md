# Function: <code>acpi_map_cpu2node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579170964,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:701",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579171273,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:708",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_map_cpu2node(acpi_handle handle, int cpu, int physid)
```

```json
{
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181824,
      "name": "acpi_map_cpu2node",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:712",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "drivers/acpi/processor_core.c:set_processor_node_mapping"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181824,
      "name": "acpi_map_cpu2node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579180294,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:727",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579195766,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:745",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579207674,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:751",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579231258,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:752",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579244586,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579246778,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579271146,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:736",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579278570,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:736",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579281338,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:736",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324462,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:734",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579385006,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:802",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579462266,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:815",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579474842,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:824",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579505610,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:833",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579245626,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579181066,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579246682,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
  "name": "acpi_map_cpu2node",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252250,
      "name": "acpi_map_cpu2node",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:735",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu"
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int acpi_map_cpu2node(acpi_handle handle, int cpu, int physid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int acpi_map_cpu2node(acpi_handle handle, int cpu, int physid)
```
</details>
</li>
</ul>
