# Function: <code>data_push_tail</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011269,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:629",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_push_tail"
      ],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_push_tail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010080,
      "name": "data_push_tail.part.0",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580013481,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:629",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010720,
      "name": "data_push_tail.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 465
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580145363,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:629",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141328,
      "name": "data_push_tail.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
    },
    {
      "addr": 18446744071592134906,
      "name": "data_push_tail.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool data_push_tail(struct printk_ringbuffer * rb, long unsigned int lpos)
```

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285328,
      "name": "data_push_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071593905822,
      "name": "data_push_tail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool data_push_tail(struct printk_ringbuffer * rb, long unsigned int lpos)
```

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495136,
      "name": "data_push_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071595986584,
      "name": "data_push_tail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
bool data_push_tail(struct printk_ringbuffer * rb, long unsigned int lpos)
```

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580566912,
      "name": "data_push_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071596504608,
      "name": "data_push_tail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool data_push_tail(struct printk_ringbuffer * rb, long unsigned int lpos)
```

```json
{
  "name": "data_push_tail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_push_tail",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:632",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc",
        "kernel/printk/printk_ringbuffer.c:desc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631152,
      "name": "data_push_tail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 429
    },
    {
      "addr": 18446744071597402273,
      "name": "data_push_tail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool data_push_tail(struct printk_ringbuffer * rb, long unsigned int lpos)
```
</details>
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
