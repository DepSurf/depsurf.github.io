# Function: <code>kick_pending_request_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584559936,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1060",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkif_interrupt",
        "drivers/block/xen-blkfront.c:blkif_restart_queue",
        "drivers/block/xen-blkfront.c:blkif_recover",
        "drivers/block/xen-blkfront.c:blkback_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559936,
      "name": "kick_pending_request_queues.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918752,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1217",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918752,
      "name": "kick_pending_request_queues",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585102128,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1216",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585102128,
      "name": "kick_pending_request_queues",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585190288,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1226",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190288,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618448,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1226",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618448,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585861664,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1226",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585861664,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585993568,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkback_changed",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993568,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237936,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237936,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586386160,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586386160,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587172879,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1234",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587257119,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1235",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587145423,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1235",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587720510,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1185",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589064516,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1186",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590594889,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1189",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590936100,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1190",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591279828,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1190",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499239256,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499239256,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149568,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1243",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149568,
      "name": "kick_pending_request_queues",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586334128,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586334128,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```

```json
{
  "name": "kick_pending_request_queues",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447952,
      "name": "kick_pending_request_queues",
      "external": false,
      "loc": "drivers/block/xen-blkfront.c:1225",
      "file": "drivers/block/xen-blkfront.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkfront_connect",
        "drivers/block/xen-blkfront.c:blkif_restart_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447952,
      "name": "kick_pending_request_queues",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
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
void kick_pending_request_queues(struct blkfront_ring_info * rinfo)
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
