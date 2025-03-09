# Function: <code>microcode_fini_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void microcode_fini_cpu(int cpu)
```

```json
{
  "name": "microcode_fini_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158402,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:462",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove",
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161504,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1026",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161504,
      "name": "microcode_fini_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void microcode_fini_cpu(int cpu)
```

```json
{
  "name": "microcode_fini_cpu",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579159988,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:454",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback",
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161584,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/intel.c:1084",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161584,
      "name": "microcode_fini_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167815,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:529",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167607,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:569",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579182311,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:677",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579193863,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183271,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:684",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579196088,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198344,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220232,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:688",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579214680,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:686",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579217144,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:686",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579255349,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:686",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579307412,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:585",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579372774,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:542",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579382070,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:539",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579413366,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:750",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_cpu_down_prep"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579197192,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579132184,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579198264,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
  "name": "microcode_fini_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579203544,
      "name": "microcode_fini_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/microcode/core.c:683",
      "file": "arch/x86/kernel/cpu/microcode/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/core.c:mc_device_remove"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void microcode_fini_cpu(int cpu)
```
</details>
</li>
</ul>
