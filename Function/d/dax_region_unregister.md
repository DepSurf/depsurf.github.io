# Function: <code>dax_region_unregister</code>

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
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448288,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448288,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586596256,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596256,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587381899,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382144,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587447164,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:534",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587445952,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587328869,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:535",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327664,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587894528,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:533",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587894528,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589245152,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:563",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243888,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590804544,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:563",
      "file": "drivers/dax/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590803184,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591142352,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:592",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591142352,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591487392,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:593",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591487392,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499477872,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499477872,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231951292,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231951292,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292757280,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292757280,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276698958,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dax/bus.c:alloc_dax_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276698958,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586286736,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286736,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586124224,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124224,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544224,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544224,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dax_region_unregister(void * region)
```

```json
{
  "name": "dax_region_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586656000,
      "name": "dax_region_unregister",
      "external": false,
      "loc": "drivers/dax/bus.c:219",
      "file": "drivers/dax/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586656000,
      "name": "dax_region_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void dax_region_unregister(void * region)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
