# Function: <code>e820_end_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int e820_end_pfn(long unsigned int limit_pfn)
```

```json
{
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594997656,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:757",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_end_of_ram_pfn",
        "arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594997656,
      "name": "e820_end_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 141
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
long unsigned int e820_end_pfn(long unsigned int limit_pfn)
```

```json
{
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595161148,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:757",
      "file": "arch/x86/kernel/e820.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820_end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595161148,
      "name": "e820_end_pfn",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 144
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595404331,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:786",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820_end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820_end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595404331,
      "name": "e820_end_pfn.constprop.3",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 127
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596323803,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:783",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323803,
      "name": "e820_end_pfn.constprop.3",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602641792,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:803",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602641792,
      "name": "e820_end_pfn.constprop.3",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602811480,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:805",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602811480,
      "name": "e820_end_pfn.constprop.3",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604606527,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:804",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604606527,
      "name": "e820_end_pfn.constprop.3",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 121
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604702123,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604702123,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604714511,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604714511,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609061197,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:816",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609061197,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612124557,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612124557,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 168
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614264481,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614264481,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615185817,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615185817,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 161
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071616952329,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616952329,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 174
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627562640,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627562640,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 201
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619312016,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619312016,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621605136,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:830",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621605136,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604640801,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604640801,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604608735,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604608735,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604718593,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718593,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
  "name": "e820_end_pfn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604718623,
      "name": "e820_end_pfn",
      "external": false,
      "loc": "arch/x86/kernel/e820.c:815",
      "file": "arch/x86/kernel/e820.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:e820__end_of_low_ram_pfn",
        "arch/x86/kernel/e820.c:e820__end_of_ram_pfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604718623,
      "name": "e820_end_pfn.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 133
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
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
long unsigned int e820_end_pfn(long unsigned int limit_pfn)
```
</details>
</li>
</ul>
