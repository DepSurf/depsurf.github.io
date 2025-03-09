# Function: <code>throtl_charge_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582889061,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:816",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:blk_throtl_bio"
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
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583177304,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:812",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
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
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583288337,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:812",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335376,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1043",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335376,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583518560,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1041",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583518560,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732816,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1039",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732816,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840352,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1025",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840352,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030192,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1022",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030192,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584133984,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133984,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584531648,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1042",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531648,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584641680,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1052",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584641680,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584669920,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1052",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584669920,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585087344,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1063",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087344,
      "name": "throtl_charge_bio",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814800,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:918",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:__blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814800,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586616570,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:956",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:__blk_throtl_bio"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586596816,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586875074,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:955",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:__blk_throtl_bio"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586855104,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587152943,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:961",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:__blk_throtl_bio"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587132432,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495984968,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495984968,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229324720,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229324720,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290209296,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290209296,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275083384,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275083384,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584102720,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584102720,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584038400,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038400,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584086480,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086480,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```

```json
{
  "name": "throtl_charge_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584189344,
      "name": "throtl_charge_bio",
      "external": false,
      "loc": "block/blk-throttle.c:1024",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:blk_throtl_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584189344,
      "name": "throtl_charge_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void throtl_charge_bio(struct throtl_grp * tg, struct bio * bio)
```
</details>
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
