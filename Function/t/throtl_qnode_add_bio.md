# Function: <code>throtl_qnode_add_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582882629,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:250",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166720,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:244",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166720,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278784,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:244",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278784,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583335264,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:410",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335264,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583528171,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:409",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583732368,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:407",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583732368,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843840,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843840,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584034256,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034256,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138096,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138096,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584537038,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:410",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536544,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584644834,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:410",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644656,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584673074,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:410",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584672896,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585090962,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:413",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090784,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585818990,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:261",
      "file": "block/blk-throttle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818768,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586601152,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:261",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601152,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586859392,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:261",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859392,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136848,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:261",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136848,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495990168,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495990168,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229329372,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229329372,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290213984,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290213984,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275086782,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275086782,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106832,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106832,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584042512,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042512,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584090592,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584090592,
      "name": "throtl_qnode_add_bio",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```

```json
{
  "name": "throtl_qnode_add_bio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192832,
      "name": "throtl_qnode_add_bio",
      "external": false,
      "loc": "block/blk-throttle.c:406",
      "file": "block/blk-throttle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_add_bio_tg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192832,
      "name": "throtl_qnode_add_bio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void throtl_qnode_add_bio(struct bio * bio, struct throtl_qnode * qn, struct list_head * queued)
```
</details>
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
