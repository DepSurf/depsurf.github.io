# Function: <code>_prb_read_valid</code>

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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009376,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1874",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009376,
      "name": "_prb_read_valid",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009968,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1874",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009968,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1874",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142768,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 659
    },
    {
      "addr": 18446744071592136196,
      "name": "_prb_read_valid.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1885",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287472,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
    },
    {
      "addr": 18446744071593907287,
      "name": "_prb_read_valid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498096,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1885",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498096,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580569872,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1885",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580569872,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
```

```json
{
  "name": "_prb_read_valid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580634112,
      "name": "_prb_read_valid",
      "external": false,
      "loc": "kernel/printk/printk_ringbuffer.c:1885",
      "file": "kernel/printk/printk_ringbuffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_ringbuffer.c:prb_next_seq",
        "kernel/printk/printk_ringbuffer.c:prb_first_valid_seq",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid_info",
        "kernel/printk/printk_ringbuffer.c:prb_read_valid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634112,
      "name": "_prb_read_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
bool _prb_read_valid(struct printk_ringbuffer * rb, u64 * seq, struct printk_record * r, unsigned int * line_count)
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
