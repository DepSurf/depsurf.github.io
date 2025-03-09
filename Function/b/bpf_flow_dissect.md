# Function: <code>bpf_flow_dissect</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588237568,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:786",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588237568,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588442064,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588442064,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589311600,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:837",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589311600,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589310576,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:854",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589310576,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589204624,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:866",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589204624,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589926608,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:867",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589926608,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591458912,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:869",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591458912,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 285
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
u32 bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593226992,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:893",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593226992,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
u32 bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593687472,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:927",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593687472,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
u32 bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594465632,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:971",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594465632,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501966176,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501966176,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234719736,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234719736,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295391248,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295391248,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278265824,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278265824,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588048848,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048848,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587761936,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587761936,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588380624,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588380624,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen, unsigned int flags)
```

```json
{
  "name": "bpf_flow_dissect",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588516352,
      "name": "bpf_flow_dissect",
      "external": true,
      "loc": "net/core/flow_dissector.c:827",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/flow_dissector.c:__skb_flow_dissect",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588516352,
      "name": "bpf_flow_dissect",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool bpf_flow_dissect(struct bpf_prog * prog, struct bpf_flow_dissector * ctx, __be16 proto, int nhoff, int hlen)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
