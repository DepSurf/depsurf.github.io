# Function: <code>userfaultfd_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581312638,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:717",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581478697,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:721",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581559369,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:756",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581613933,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1190",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581758451,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1274",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581926295,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1279",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582012135,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1284",
      "file": "fs/userfaultfd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1300",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144368,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1250
    },
    {
      "addr": 18446744071582154398,
      "name": "userfaultfd_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582221840,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582221840,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582459136,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1304",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582459136,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1344
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582516048,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1268",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582516048,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1379
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543312,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1277",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543312,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1681
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582859360,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1272",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582859360,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1740
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583427984,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1263",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427984,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1674
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017072,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1283",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017072,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1942
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584242144,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1312",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584242144,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1973
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456112,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1314",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456112,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2046
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493793768,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493793768,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1448
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227304656,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227304656,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287402048,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287402048,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1744
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273379190,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273379190,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582190576,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582190576,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582129216,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582129216,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181056,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181056,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1246
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
```

```json
{
  "name": "userfaultfd_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582260912,
      "name": "userfaultfd_register",
      "external": false,
      "loc": "fs/userfaultfd.c:1302",
      "file": "fs/userfaultfd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/userfaultfd.c:userfaultfd_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582260912,
      "name": "userfaultfd_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1301
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
int userfaultfd_register(struct userfaultfd_ctx * ctx, long unsigned int arg)
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
