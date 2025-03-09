# Function: <code>ext4_groupinfo_create_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581807515,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2536",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582001833,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2544",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582068352,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2544",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582068352,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032784,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2558",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032784,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582183024,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2558",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582183024,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2527",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582372944,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582408809,
      "name": "ext4_groupinfo_create_slab.cold.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2527",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472576,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582508233,
      "name": "ext4_groupinfo_create_slab.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2528",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582641984,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582677199,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582743904,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582779247,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2665",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583052688,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
    },
    {
      "addr": 18446744071583091017,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583158002,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2769",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583184232,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3272",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583526372,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3292",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584059614,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3289",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584692286,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3239",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584917582,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3459",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585150558,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:3485",
      "file": "fs/ext4/mballoc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/ext4/mballoc.c:ext4_mb_init"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494407648,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494407648,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227840008,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227840008,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288147072,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288147072,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273824838,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273824838,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 314
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582712640,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582747983,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582649808,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582685151,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582702496,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582737839,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```

```json
{
  "name": "ext4_groupinfo_create_slab",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_groupinfo_create_slab",
      "external": false,
      "loc": "fs/ext4/mballoc.c:2543",
      "file": "fs/ext4/mballoc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/mballoc.c:ext4_mb_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786912,
      "name": "ext4_groupinfo_create_slab",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    },
    {
      "addr": 18446744071582823114,
      "name": "ext4_groupinfo_create_slab.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int ext4_groupinfo_create_slab(size_t size)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ext4_groupinfo_create_slab(size_t size)
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
