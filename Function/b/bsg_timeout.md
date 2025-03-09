# Function: <code>bsg_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826880,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:314",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826880,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584017088,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:333",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584017088,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584120608,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584120608,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518496,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518496,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584627280,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:338",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627280,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584655456,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:338",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655456,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int bsg_timeout(struct bsg_device * bd, struct sg_io_v4 * hdr)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585068284,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg.c:45",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_sg_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069024,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:339",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069024,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int bsg_timeout(struct bsg_device * bd, struct sg_io_v4 * hdr)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585793212,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg.c:45",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_sg_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585793920,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:334",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585793920,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int bsg_timeout(struct bsg_device * bd, struct sg_io_v4 * hdr)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586574268,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg.c:45",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_sg_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586575056,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575056,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int bsg_timeout(struct bsg_device * bd, struct sg_io_v4 * hdr)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586832059,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg.c:45",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_sg_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586832816,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832816,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
unsigned int bsg_timeout(struct bsg_device * bd, struct sg_io_v4 * hdr)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587109179,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg.c:45",
      "file": "block/bsg.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_sg_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587109936,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109936,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495966936,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495966936,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229309268,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229309268,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290187488,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290187488,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275069836,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275069836,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584089344,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584089344,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025104,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025104,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073104,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073104,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
```

```json
{
  "name": "bsg_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175680,
      "name": "bsg_timeout",
      "external": false,
      "loc": "block/bsg-lib.c:335",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175680,
      "name": "bsg_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
enum blk_eh_timer_return bsg_timeout(struct request * rq, bool reserved)
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
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bsg_device * bd</code>
</li>
<li>
<b>Param added. </b>
<code>struct sg_io_v4 * hdr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request * rq</code>
</li>
<li>
<b>Param removed. </b>
<code>bool reserved</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum blk_eh_timer_return</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
