# Function: <code>desc_reserve</code>

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
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```

```json
{
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010592,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:872",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010592,
      "name": "desc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580012790,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:872",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
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
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580144559,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:872",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```

```json
{
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:875",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580285744,
      "name": "desc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
    },
    {
      "addr": 18446744071593905969,
      "name": "desc_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```

```json
{
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:875",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580495568,
      "name": "desc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 599
    },
    {
      "addr": 18446744071595986731,
      "name": "desc_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```

```json
{
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:875",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580567360,
      "name": "desc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    },
    {
      "addr": 18446744071596504736,
      "name": "desc_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```

```json
{
  "name": "desc_reserve",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "desc_reserve",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:875",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580631600,
      "name": "desc_reserve",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 604
    },
    {
      "addr": 18446744071597402401,
      "name": "desc_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool desc_reserve(struct printk_ringbuffer * rb, long unsigned int * id_out)
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
