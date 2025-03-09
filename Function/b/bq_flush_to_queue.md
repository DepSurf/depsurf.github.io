# Function: <code>bq_flush_to_queue</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int bq_flush_to_queue(struct bpf_cpu_map_entry * rcpu, struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580612416,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:597",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580612416,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
int bq_flush_to_queue(struct bpf_cpu_map_entry * rcpu, struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580721728,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:560",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580721728,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int bq_flush_to_queue(struct bpf_cpu_map_entry * rcpu, struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801888,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:563",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801888,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889616,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889616,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580942256,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580942256,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581105072,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:556",
      "file": "kernel/bpf/cpumap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105072,
      "name": "bq_flush_to_queue.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581132224,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:659",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581132224,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581152416,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:622",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152416,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581393728,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:689",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581393728,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581717088,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:691",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581717088,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123728,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:690",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123728,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582320000,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:711",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582320000,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480976,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:665",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480976,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492287056,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492287056,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226171548,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226171548,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285517136,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285517136,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272417776,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272417776,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580911056,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580911056,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857120,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857120,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902304,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902304,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```

```json
{
  "name": "bq_flush_to_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961040,
      "name": "bq_flush_to_queue",
      "external": false,
      "loc": "kernel/bpf/cpumap.c:602",
      "file": "kernel/bpf/cpumap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cpumap.c:__cpu_map_flush",
        "kernel/bpf/cpumap.c:cpu_map_enqueue",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961040,
      "name": "bq_flush_to_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int bq_flush_to_queue(struct bpf_cpu_map_entry * rcpu, struct xdp_bulk_queue * bq)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool in_napi_ctx</code>
</li>
</ul>
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
<code>struct bpf_cpu_map_entry * rcpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>rcpu, bq, in_napi_ctx</code> ➡️ <code>bq, in_napi_ctx</code>
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
int bq_flush_to_queue(struct xdp_bulk_queue * bq, bool in_napi_ctx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue * bq)
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
