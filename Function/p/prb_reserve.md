# Function: <code>prb_reserve</code>

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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012272,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1479",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012272,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012688,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1479",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012688,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 962
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1479",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592136775,
      "name": "prb_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 630
    },
    {
      "addr": 18446744071580144448,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1094
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1485",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593907797,
      "name": "prb_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071580289216,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1485",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595988453,
      "name": "prb_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071580499456,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 603
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1485",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596506162,
      "name": "prb_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071580571232,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
```

```json
{
  "name": "prb_reserve",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "prb_reserve",
      "external": true,
      "loc": "kernel/printk/printk_ringbuffer.c:1485",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597403827,
      "name": "prb_reserve.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
    },
    {
      "addr": 18446744071580635472,
      "name": "prb_reserve",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
bool prb_reserve(struct prb_reserved_entry * e, struct printk_ringbuffer * rb, struct printk_record * r)
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
