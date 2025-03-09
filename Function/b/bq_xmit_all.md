# Function: <code>bq_xmit_all</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int bq_xmit_all(struct bpf_dtab_netdev * obj, struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719024,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:219",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719024,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int bq_xmit_all(struct bpf_dtab_netdev * obj, struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580799152,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:220",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580799152,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886784,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:211",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886784,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580938032,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580938032,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581101200,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:344",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101200,
      "name": "bq_xmit_all.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581128736,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:330",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581128736,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149408,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:329",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149408,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581384304,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:364",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581384304,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581707472,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:365",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:dev_xdp_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581707472,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582114000,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:365",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582114000,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582310080,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:362",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582310080,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
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
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471104,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:361",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:bq_enqueue",
        "kernel/bpf/devmap.c:__dev_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471104,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492278968,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492278968,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226167028,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226167028,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285510464,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285510464,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272413386,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272413386,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580906832,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580906832,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852896,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852896,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580898080,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580898080,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 425
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
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```

```json
{
  "name": "bq_xmit_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580956752,
      "name": "bq_xmit_all",
      "external": false,
      "loc": "kernel/bpf/devmap.c:349",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:__dev_map_entry_free",
        "kernel/bpf/devmap.c:dev_map_enqueue",
        "kernel/bpf/devmap.c:__dev_map_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580956752,
      "name": "bq_xmit_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int bq_xmit_all(struct bpf_dtab_netdev * obj, struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_dtab_netdev * obj</code>
</li>
<li>
<b>Param reordered. </b>
<code>obj, bq, flags, in_napi_ctx</code> ➡️ <code>bq, flags, in_napi_ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue * bq, u32 flags, bool in_napi_ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue * bq, u32 flags)
```
</details>
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
