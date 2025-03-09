# Function: <code>rproc_alloc</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588238929,
      "name": "rproc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588233264,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589107564,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2127",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106432,
      "name": "rproc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 707
    },
    {
      "addr": 18446744071589116075,
      "name": "rproc_alloc.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589107152,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589106348,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2232",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105440,
      "name": "rproc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 710
    },
    {
      "addr": 18446744071591617569,
      "name": "rproc_alloc.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589106160,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588995964,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2479",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588995056,
      "name": "rproc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071591560443,
      "name": "rproc_alloc.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588995776,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589710467,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2508",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589709296,
      "name": "rproc_alloc.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
    },
    {
      "addr": 18446744071592681187,
      "name": "rproc_alloc.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589710016,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2518",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594566653,
      "name": "rproc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591216656,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592963344,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2442",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592963344,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593413712,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2443",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593413712,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594159424,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:2443",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594159424,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 785
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501690760,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501690760,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 680
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234215852,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234215852,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295125072,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295125072,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850625,
      "name": "rproc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587844960,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```

```json
{
  "name": "rproc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rproc_alloc",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1989",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311265,
      "name": "rproc_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588305600,
      "name": "rproc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct rproc * rproc_alloc(struct device * dev, const char * name, const struct rproc_ops * ops, const char * firmware, int len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
