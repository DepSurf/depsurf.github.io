# Function: <code>dev_alloc_name_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586284933,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1101",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586713045,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1105",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586898725,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1104",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587023989,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1136",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587521376,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1112",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587521376,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1112",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587822128,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    },
    {
      "addr": 18446744071587860306,
      "name": "dev_alloc_name_ns.cold.153",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1114",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587955104,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
    },
    {
      "addr": 18446744071588000702,
      "name": "dev_alloc_name_ns.cold.159",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1110",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588269776,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071588311719,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476128,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071588518151,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1221",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589342896,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071589391996,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1223",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589350032,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071591629250,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1271",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239984,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071591572573,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1146",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964160,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    },
    {
      "addr": 18446744071592697823,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1093",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510256,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071594584185,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593281456,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1093",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593281456,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593740304,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1118",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593740304,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502004544,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502004544,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234759804,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234759804,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295441296,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_get_valid_name",
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295441296,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278295094,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278295094,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 396
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082912,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071588124887,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796480,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071587837719,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588414688,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071588456711,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```

```json
{
  "name": "dev_alloc_name_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_alloc_name_ns",
      "external": false,
      "loc": "net/core/dev.c:1028",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588553280,
      "name": "dev_alloc_name_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
    },
    {
      "addr": 18446744071588593745,
      "name": "dev_alloc_name_ns.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int dev_alloc_name_ns(struct net * net, struct net_device * dev, const char * name)
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
