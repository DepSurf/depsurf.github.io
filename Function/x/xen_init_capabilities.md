# Function: <code>xen_init_capabilities</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596301390,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:258",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602619225,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:261",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602787502,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:261",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604581682,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:283",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604676978,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:283",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604689457,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:291",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609039252,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:293",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609039252,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 272
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
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612102658,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:285",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612102658,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 272
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614243245,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:285",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615163417,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:256",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616928641,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:259",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616928641,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 256
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
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627532192,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:270",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627532192,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 323
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
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619278032,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:324",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619278032,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 322
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
void xen_init_capabilities()
```

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621571008,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:335",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621571008,
      "name": "xen_init_capabilities",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 322
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604615738,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:291",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604693553,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:291",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
  "name": "xen_init_capabilities",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604693509,
      "name": "xen_init_capabilities",
      "external": false,
      "loc": "arch/x86/xen/enlighten_pv.c:291",
      "file": "arch/x86/xen/enlighten_pv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/enlighten_pv.c:xen_start_kernel"
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
void xen_init_capabilities()
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
void xen_init_capabilities()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void xen_init_capabilities()
```
</details>
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
