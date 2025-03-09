# Function: <code>wbt_exit</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void wbt_exit(struct request_queue * q)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583346288,
      "name": "wbt_exit",
      "external": true,
      "loc": "block/blk-wbt.c:742",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_init_allocated_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-mq.c:blk_mq_free_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583346288,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void wbt_exit(struct request_queue * q)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583404368,
      "name": "wbt_exit",
      "external": true,
      "loc": "block/blk-wbt.c:748",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-wbt.c:wbt_disable_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583404368,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wbt_exit(struct request_queue * q)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583583904,
      "name": "wbt_exit",
      "external": true,
      "loc": "block/blk-wbt.c:753",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-wbt.c:wbt_disable_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583583904,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wbt_exit(struct request_queue * q)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583800688,
      "name": "wbt_exit",
      "external": true,
      "loc": "block/blk-wbt.c:784",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-sysfs.c:blk_unregister_queue",
        "block/blk-wbt.c:wbt_disable_default"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583800688,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583878976,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583878976,
      "name": "wbt_exit",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069264,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:692",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069264,
      "name": "wbt_exit",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584191968,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584191968,
      "name": "wbt_exit",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584586640,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:683",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584586640,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705184,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:683",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705184,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584733392,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:688",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584733392,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585161104,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:690",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585161104,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585898016,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:690",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585898016,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586685712,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:708",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685712,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586947136,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:770",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586947136,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587227568,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:762",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587227568,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496057312,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496057312,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229387692,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229387692,
      "name": "wbt_exit",
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290293856,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290293856,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275133574,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275133574,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584160704,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160704,
      "name": "wbt_exit",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584095968,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584095968,
      "name": "wbt_exit",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144464,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144464,
      "name": "wbt_exit",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos * rqos)
```

```json
{
  "name": "wbt_exit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584248432,
      "name": "wbt_exit",
      "external": false,
      "loc": "block/blk-wbt.c:691",
      "file": "block/blk-wbt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584248432,
      "name": "wbt_exit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void wbt_exit(struct request_queue * q)
```
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos * rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
</ul>
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
