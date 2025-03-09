# Function: <code>blk_mq_debugfs_unregister_rqos</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583888369,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:1020",
      "file": "block/blk-mq-debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888160,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078592,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078592,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201296,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201296,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596448,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:946",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596448,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584715392,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715392,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743552,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:940",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743552,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171616,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:956",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171616,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585907872,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:816",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907872,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696848,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:814",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696848,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586957360,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:788",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-rq-qos.c:rq_qos_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586957360,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587237616,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:769",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-rq-qos.c:rq_qos_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587237616,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496070816,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496070816,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229398748,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229398748,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290309552,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init",
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290309552,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275143806,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275143806,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170032,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170032,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584105280,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105280,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584153792,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584153792,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
```

```json
{
  "name": "blk_mq_debugfs_unregister_rqos",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258176,
      "name": "blk_mq_debugfs_unregister_rqos",
      "external": true,
      "loc": "block/blk-mq-debugfs.c:942",
      "file": "block/blk-mq-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-iocost.c:blk_iocost_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258176,
      "name": "blk_mq_debugfs_unregister_rqos",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos * rqos)
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
