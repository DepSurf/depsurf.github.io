# Function: <code>blk_mq_hctx_next_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582791648,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:835",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_queue"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582791648,
      "name": "blk_mq_hctx_next_cpu.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069055,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:913",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_queue"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068896,
      "name": "blk_mq_hctx_next_cpu.part.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583177542,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:955",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue"
      ],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583177392,
      "name": "blk_mq_hctx_next_cpu.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234832,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1127",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234832,
      "name": "blk_mq_hctx_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx * hctx)
```

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412672,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1258",
      "file": "block/blk-mq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583412672,
      "name": "blk_mq_hctx_next_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583622532,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1284",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583727380,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1408",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583915476,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1406",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584018692,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584415860,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1443",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584531780,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1534",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584563020,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1499",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584973916,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1510",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585680251,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:2033",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586457112,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:2200",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586700795,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:2171",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
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
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586972779,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:2189",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495852640,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3229197836,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055290044960,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274978464,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583987428,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583923284,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583971188,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "blk_mq_hctx_next_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584073844,
      "name": "blk_mq_hctx_next_cpu",
      "external": false,
      "loc": "block/blk-mq.c:1422",
      "file": "block/blk-mq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_delay_run_hw_queue"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx * hctx)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int blk_mq_hctx_next_cpu(struct blk_mq_hw_ctx * hctx)
```
</details>
</li>
</ul>
