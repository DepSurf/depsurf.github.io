# Function: <code>__cec_s_phys_addr</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587263296,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1493",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_s_phys_addr_from_edid",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587263254,
      "name": "__cec_s_phys_addr.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071587259360,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 615
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587521399,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1538",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520768,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
    },
    {
      "addr": 18446744071587531001,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071587528544,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587724471,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723840,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587733829,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587731488,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500901112,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500901112,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
    },
    {
      "addr": 18446603336500909080,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233419688,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233419688,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
    },
    {
      "addr": 3233427960,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294357360,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294357360,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 812
    },
    {
      "addr": 13835058055294368000,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277679680,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277679680,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446743936277686542,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587365415,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587364784,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587374773,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587372432,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587133639,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587133008,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587142997,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587140656,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587680615,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587679984,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587689973,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587687632,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```

```json
{
  "name": "__cec_s_phys_addr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587786999,
      "name": "__cec_s_phys_addr",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1552",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786368,
      "name": "__cec_s_phys_addr.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071587796341,
      "name": "__cec_s_phys_addr.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587794000,
      "name": "__cec_s_phys_addr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __cec_s_phys_addr(struct cec_adapter * adap, u16 phys_addr, bool block)
```
</details>
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
