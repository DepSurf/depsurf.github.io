# Function: <code>build_uv_gr_table</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604784719,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:423",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609126712,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:448",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609126712,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 586
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
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612194908,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:606",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612194908,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 586
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
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614335808,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:602",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614335808,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 583
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
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615265470,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:602",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615265470,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 583
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
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617041388,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:608",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617041388,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 611
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
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627675760,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:608",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627675760,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619431248,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:608",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619431248,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 724
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void build_uv_gr_table()
```

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621729376,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:609",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621729376,
      "name": "build_uv_gr_table",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 724
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "build_uv_gr_table",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604788860,
      "name": "build_uv_gr_table",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:423",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
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
void build_uv_gr_table()
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
