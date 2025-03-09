# Function: <code>data_realloc</code>

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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011136,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1102",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011136,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011472,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1102",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011472,
      "name": "data_realloc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1102",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580141984,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
    },
    {
      "addr": 18446744071592135280,
      "name": "data_realloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1105",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286672,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071593906367,
      "name": "data_realloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1105",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580496528,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    },
    {
      "addr": 18446744071595987129,
      "name": "data_realloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1105",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568304,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    },
    {
      "addr": 18446744071596505028,
      "name": "data_realloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
```

```json
{
  "name": "data_realloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "data_realloc",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1105",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve_in_last"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632544,
      "name": "data_realloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
    },
    {
      "addr": 18446744071597402693,
      "name": "data_realloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
char * data_realloc(struct printk_ringbuffer * rb, unsigned int size, struct prb_data_blk_lpos * blk_lpos, long unsigned int id)
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
