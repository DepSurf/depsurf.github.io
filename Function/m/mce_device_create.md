# Function: <code>mce_device_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mce_device_create(unsigned int cpu)
```

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132544,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2304",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132544,
      "name": "mce_device_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int mce_device_create(unsigned int cpu)
```

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579132576,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2387",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init_device",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132576,
      "name": "mce_device_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579139912,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2450",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579138055,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2161",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153095,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2190",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579163656,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:2183",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579153144,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2206",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579165160,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167624,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184800,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2389",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579184800,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579181040,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2465",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181040,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579186864,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2476",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186864,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579221392,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2539",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221392,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579272032,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2551",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272032,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579336464,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2551",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336464,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345344,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2568",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579345344,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579371600,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2597",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371600,
      "name": "mce_device_create.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167976,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579099576,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579167544,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
  "name": "mce_device_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579172728,
      "name": "mce_device_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:2261",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_online"
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
int mce_device_create(unsigned int cpu)
```
</details>
</li>
</ul>
