# Function: <code>blkfront_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584582180,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1993",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584929823,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2366",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585112704,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2342",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585112704,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1873
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
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585195274,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2312",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585623434,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2312",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585869280,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2315",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586005056,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkback_changed"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243392,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071586250240,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391616,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071586398442,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2342",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587172368,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071587174115,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2346",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587256608,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071591493062,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2346",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587144912,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 889
    },
    {
      "addr": 18446744071591436138,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2323",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720192,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1286
    },
    {
      "addr": 18446744071592500440,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2310",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589064160,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1363
    },
    {
      "addr": 18446744071594370540,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590593840,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2313",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590593840,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1398
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590935056,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2314",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590935056,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591278784,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2314",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591278784,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1393
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
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499239544,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499239544,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1080
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2363",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153952,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1015
    },
    {
      "addr": 18446744071586161022,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586339584,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071586346410,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```

```json
{
  "name": "blkfront_connect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "blkfront_connect",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:2334",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586451280,
      "name": "blkfront_connect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071586458103,
      "name": "blkfront_connect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void blkfront_connect(struct blkfront_info * info)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void blkfront_connect(struct blkfront_info * info)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void blkfront_connect(struct blkfront_info * info)
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
void blkfront_connect(struct blkfront_info * info)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
