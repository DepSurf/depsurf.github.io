# Function: <code>dm_get_md_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585804480,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:542",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585804480,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586199824,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:396",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199824,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586400748,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:396",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586404304,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586504108,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:391",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586507728,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586971196,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:398",
      "file": "drivers/md/dm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:__dm_destroy"
      ],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975264,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 15
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587271984,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:444",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271984,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587452512,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:444",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587452512,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587726528,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587726528,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587930880,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587930880,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588783984,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:430",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783984,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501166536,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501166536,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233676344,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233676344,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294678448,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294678448,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277874518,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277874518,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587561856,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587561856,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587329936,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587329936,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587887024,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587887024,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
struct request_queue * dm_get_md_queue(struct mapped_device * md)
```

```json
{
  "name": "dm_get_md_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588002320,
      "name": "dm_get_md_queue",
      "external": true,
      "loc": "drivers/md/dm.c:426",
      "file": "drivers/md/dm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/dm-rq.c:dm_mq_kick_requeue_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002320,
      "name": "dm_get_md_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct request_queue * dm_get_md_queue(struct mapped_device * md)
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
