# Function: <code>bpf_event_output</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580370032,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:344",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580370032,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580417776,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:338",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417776,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580429712,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:372",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429712,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485712,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:413",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485712,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580572064,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:436",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580572064,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580630192,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:472",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630192,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580691648,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:506",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580691648,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580738608,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580738608,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853472,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:902",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853472,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845280,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:985",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845280,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580848832,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:662",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580848832,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050768,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:662",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050768,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581307952,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:714",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581307952,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635680,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:718",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635680,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581777008,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:718",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581777008,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896576,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:718",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_event_output_data",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896576,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 622
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492049824,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492049824,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225949412,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225949412,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285221136,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285221136,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 672
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272278888,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/bpf/core.c:2052",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272278888,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 30
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580707408,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707408,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653616,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653616,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698656,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698656,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
```

```json
{
  "name": "bpf_event_output",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756608,
      "name": "bpf_event_output",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:513",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_sockopt_event_output",
        "net/core/filter.c:bpf_xdp_event_output",
        "net/core/filter.c:bpf_skb_event_output"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756608,
      "name": "bpf_event_output",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
u64 bpf_event_output(struct bpf_map * map, u64 flags, void * meta, u64 meta_size, void * ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy)
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
