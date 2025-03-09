# Function: <code>do_direct_IO</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581246584,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:911",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581412947,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:920",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581493587,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:905",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581548518,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:908",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581691721,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:948",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581858047,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:969",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581942834,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:970",
      "file": "fs/direct-io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/direct-io.c:do_blockdev_direct_IO"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582079728,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:963",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582079728,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3477
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157168,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157168,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3477
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582394976,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:943",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582394976,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2692
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582448912,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:924",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582448912,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2570
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582475712,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:927",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582475712,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2624
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:927",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788352,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2754
    },
    {
      "addr": 18446744071592233652,
      "name": "do_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 810
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:917",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583341024,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2408
    },
    {
      "addr": 18446744071594013835,
      "name": "do_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 838
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:920",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924912,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1944
    },
    {
      "addr": 18446744071596053869,
      "name": "do_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:902",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157792,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
    },
    {
      "addr": 18446744071596578446,
      "name": "do_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:902",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:__blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371968,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2256
    },
    {
      "addr": 18446744071597482489,
      "name": "do_direct_IO.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493711064,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493711064,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3212
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227237500,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227237500,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3508
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287316112,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287316112,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3956
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273325292,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273325292,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2646
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582125904,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582125904,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3477
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063344,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063344,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3477
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582116384,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582116384,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3477
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
```

```json
{
  "name": "do_direct_IO",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582189344,
      "name": "do_direct_IO",
      "external": false,
      "loc": "fs/direct-io.c:962",
      "file": "fs/direct-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/direct-io.c:do_blockdev_direct_IO"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582189344,
      "name": "do_direct_IO",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3507
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
int do_direct_IO(struct dio * dio, struct dio_submit * sdio, struct buffer_head * map_bh)
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
