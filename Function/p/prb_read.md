# Function: <code>prb_read</code>

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
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008848,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1785",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008848,
      "name": "prb_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
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
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580010030,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1785",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
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
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580142830,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1785",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
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
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580287537,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1796",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1796",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497680,
      "name": "prb_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071595988049,
      "name": "prb_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1796",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569456,
      "name": "prb_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071596505771,
      "name": "prb_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "prb_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_read",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1796",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633696,
      "name": "prb_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071597403436,
      "name": "prb_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int prb_read(struct printk_ringbuffer * rb, u64 seq, struct printk_record * r, unsigned int * line_count)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
