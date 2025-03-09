# Function: <code>locks_remove_posix</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581341088,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2395",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file"
      ],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581341088,
      "name": "locks_remove_posix.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    },
    {
      "addr": 18446744071581341280,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581528336,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2426",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_remove_file"
      ],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581521712,
      "name": "locks_remove_posix.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
    },
    {
      "addr": 18446744071581522000,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609120,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2464",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609120,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581671040,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2427",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581671040,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581817312,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2467",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581817312,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992080,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2472",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992080,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080816,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2584",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080816,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582242576,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2602",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582242576,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342336,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342336,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582635136,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2695",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582635136,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582707280,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2698",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582707280,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736816,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2700",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736816,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 461
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583063728,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2586",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583063728,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583536880,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2572",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583536880,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584137344,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2554",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137344,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 405
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584364528,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2530",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584364528,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584582896,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2541",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_flush",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584582896,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493926392,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493926392,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227398604,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227398604,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287563024,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287563024,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273478262,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273478262,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582311072,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582311072,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582248832,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582248832,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582301552,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301552,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
void locks_remove_posix(struct file * filp, fl_owner_t owner)
```

```json
{
  "name": "locks_remove_posix",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582374848,
      "name": "locks_remove_posix",
      "external": true,
      "loc": "fs/locks.c:2692",
      "file": "fs/locks.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:filp_close",
        "fs/locks.c:locks_remove_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582374848,
      "name": "locks_remove_posix",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
