# Function: <code>vga_arb_select_default_device</code>

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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602984778,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1405",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603156360,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1405",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604961213,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1405",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605069826,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605107211,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
void vga_arb_select_default_device()
```

```json
{
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609387810,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609387810,
      "name": "vga_arb_select_default_device",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 429
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
void vga_arb_select_default_device()
```

```json
{
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612459265,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1453",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612459265,
      "name": "vga_arb_select_default_device",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 429
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
void vga_arb_select_default_device()
```

```json
{
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614601365,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1468",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614601365,
      "name": "vga_arb_select_default_device",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 509
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
void vga_arb_select_default_device()
```

```json
{
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615558535,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1447",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615558535,
      "name": "vga_arb_select_default_device",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 621
    }
  ]
}
```
</details>
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511238656,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243884904,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302804496,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270812410,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605007304,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604971635,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605087750,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
  "name": "vga_arb_select_default_device",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605111405,
      "name": "vga_arb_select_default_device",
      "external": false,
      "loc": "drivers/gpu/vga/vgaarb.c:1454",
      "file": "drivers/gpu/vga/vgaarb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpu/vga/vgaarb.c:vga_arb_device_init"
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
void vga_arb_select_default_device()
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void vga_arb_select_default_device()
```
</details>
</li>
</ul>
