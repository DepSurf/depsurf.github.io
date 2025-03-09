# Function: <code>get_data</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008272,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1202",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_read",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008272,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009392,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1202",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009392,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1202",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142368,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 399
    },
    {
      "addr": 18446744071592135779,
      "name": "get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1205",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287088,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071593906883,
      "name": "get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1205",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496960,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071595987645,
      "name": "get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1205",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568752,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071596505428,
      "name": "get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
```

```json
{
  "name": "get_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_data",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1205",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632992,
      "name": "get_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    },
    {
      "addr": 18446744071597403093,
      "name": "get_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
const char * get_data(struct prb_data_ring * data_ring, struct prb_data_blk_lpos * blk_lpos, unsigned int * data_size)
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
