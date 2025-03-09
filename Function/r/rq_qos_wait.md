# Function: <code>rq_qos_wait</code>

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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583816336,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:223",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583816336,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584006448,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:227",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006448,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109952,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109952,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505664,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505664,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584616128,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616128,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584647712,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584647712,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592319830,
      "name": "rq_qos_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071585064752,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594104299,
      "name": "rq_qos_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585787904,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:243",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596108810,
      "name": "rq_qos_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071586568384,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:243",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596632616,
      "name": "rq_qos_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071586825760,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:243",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597538934,
      "name": "rq_qos_wait.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071587102848,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495953648,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495953648,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229296816,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229296816,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290176240,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290176240,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275063458,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275063458,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078688,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078688,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584014448,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584014448,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062448,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584062448,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
```

```json
{
  "name": "rq_qos_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164944,
      "name": "rq_qos_wait",
      "external": true,
      "loc": "block/blk-rq-qos.c:249",
      "file": "block/blk-rq-qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-wbt.c:wbt_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164944,
      "name": "rq_qos_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
void rq_qos_wait(struct rq_wait * rqw, void * private_data, acquire_inflight_cb_t * acquire_inflight_cb, cleanup_cb_t * cleanup_cb)
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
