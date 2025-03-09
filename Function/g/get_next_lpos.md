# Function: <code>get_next_lpos</code>

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
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011216,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:999",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
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
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580011552,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:999",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```

```json
{
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:999",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140640,
      "name": "get_next_lpos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071592134298,
      "name": "get_next_lpos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```

```json
{
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1002",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284400,
      "name": "get_next_lpos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071593905178,
      "name": "get_next_lpos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```

```json
{
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1002",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494128,
      "name": "get_next_lpos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071595985940,
      "name": "get_next_lpos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```

```json
{
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1002",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565968,
      "name": "get_next_lpos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071596504236,
      "name": "get_next_lpos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```

```json
{
  "name": "get_next_lpos",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_next_lpos",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1002",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_realloc",
        "kernel/printk/printk_ringbuffer.c:data_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630208,
      "name": "get_next_lpos",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071597401901,
      "name": "get_next_lpos.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
long unsigned int get_next_lpos(struct prb_data_ring * data_ring, long unsigned int lpos, unsigned int size)
```
</details>
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
