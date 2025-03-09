# Function: <code>ext4_finish_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595264,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:61",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_release_io_end",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595264,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 556
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785968,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785968,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875552,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875552,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112096,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:61",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112096,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582261104,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582261104,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582449168,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 524
    },
    {
      "addr": 18446744071582452528,
      "name": "ext4_finish_bio.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582548640,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071582552006,
      "name": "ext4_finish_bio.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720768,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 619
    },
    {
      "addr": 18446744071582724323,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823248,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071582826892,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134896,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    },
    {
      "addr": 18446744071583138414,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215552,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071591347473,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583243056,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
    },
    {
      "addr": 18446744071591290307,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585152,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    },
    {
      "addr": 18446744071592267233,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122736,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 661
    },
    {
      "addr": 18446744071594048690,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756336,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756336,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584979808,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
    },
    {
      "addr": 18446744071596604669,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:100",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210960,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
    },
    {
      "addr": 18446744071597510099,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494494112,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494494112,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227931088,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227931088,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288258752,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288258752,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273894096,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_release_io_end"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273894096,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791984,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071582795628,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729152,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
    },
    {
      "addr": 18446744071582732780,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780864,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071582784508,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void ext4_finish_bio(struct bio * bio)
```

```json
{
  "name": "ext4_finish_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ext4_finish_bio",
      "external": false,
      "loc": "fs/ext4/page-io.c:62",
      "file": "fs/ext4/page-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ext4/page-io.c:ext4_end_bio",
        "fs/ext4/page-io.c:ext4_end_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582867184,
      "name": "ext4_finish_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 670
    },
    {
      "addr": 18446744071582870901,
      "name": "ext4_finish_bio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
