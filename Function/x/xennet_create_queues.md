# Function: <code>xennet_create_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585122038,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1758",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585515089,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1749",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585703022,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1755",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_connect"
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585789755,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1754",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586228452,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1756",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586485180,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1758",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:talk_to_netback"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1757",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586631920,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071586637222,
      "name": "xennet_create_queues.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1756",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885296,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071586890650,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1757",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587031280,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071587036634,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1762",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587857776,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071587866424,
      "name": "xennet_create_queues.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2039",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587916080,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071591533888,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2037",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587798208,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 771
    },
    {
      "addr": 18446744071591475972,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2186",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588399056,
      "name": "xennet_create_queues.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 945
    },
    {
      "addr": 18446744071592546848,
      "name": "xennet_create_queues.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2194",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589797264,
      "name": "xennet_create_queues.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 943
    },
    {
      "addr": 18446744071594426104,
      "name": "xennet_create_queues.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591445856,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2200",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591445856,
      "name": "xennet_create_queues.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1147
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591861344,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2202",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591861344,
      "name": "xennet_create_queues.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1166
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
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592601104,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:2203",
      "file": "drivers/net/xen-netfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592601104,
      "name": "xennet_create_queues.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1211
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500148896,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1757",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500148896,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1791",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586788624,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071586794062,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1757",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586985840,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071586991194,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```

```json
{
  "name": "xennet_create_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xennet_create_queues",
      "external": false,
      "loc": "drivers/net/xen-netfront.c:1757",
      "file": "drivers/net/xen-netfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:talk_to_netback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093040,
      "name": "xennet_create_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
    },
    {
      "addr": 18446744071587098369,
      "name": "xennet_create_queues.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
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
int xennet_create_queues(struct netfront_info * info, unsigned int * num_queues)
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
