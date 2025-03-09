# Function: <code>desc_read</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009845,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:data_make_reusable"
      ],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last",
        "kernel/printk/printk_ringbuffer.c:desc_push_tail",
        "kernel/printk/printk_ringbuffer.c:desc_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008512,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580009632,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009632,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140944,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071592134789,
      "name": "desc_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:data_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284896,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071593905707,
      "name": "desc_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:data_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494672,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071595986469,
      "name": "desc_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:data_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566448,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071596504512,
      "name": "desc_read.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
```

```json
{
  "name": "desc_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:432",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:desc_read_finalized_seq",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:desc_reserve",
        "kernel/printk/printk_ringbuffer.c:data_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630688,
      "name": "desc_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071597402177,
      "name": "desc_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
enum desc_state desc_read(struct prb_desc_ring * desc_ring, long unsigned int id, struct prb_desc * desc_out, u64 * seq_out, u32 * caller_id_out)
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
