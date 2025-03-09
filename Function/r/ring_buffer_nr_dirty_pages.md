# Function: <code>ring_buffer_nr_dirty_pages</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580455056,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:555",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580455056,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580509808,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:532",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580509808,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580559316,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580557376,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651094,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:535",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580652048,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580641253,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:771",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642336,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580637779,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:857",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645040,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580809983,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:857",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817632,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581036321,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:893",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042064,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581342480,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:895",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581342480,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436816,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:893",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436816,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
size_t ring_buffer_nr_dirty_pages(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581546064,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:702",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_poll_wait",
        "kernel/trace/ring_buffer.c:rb_watermark_hit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581546064,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491844728,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491844728,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225792204,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225792204,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284915008,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284915008,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272146370,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit",
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272146370,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580528116,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526176,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580474996,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473056,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580519364,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517424,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_nr_dirty_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580575796,
      "name": "ring_buffer_nr_dirty_pages",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:533",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ring_buffer.c:ring_buffer_wait"
      ],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_write",
        "kernel/trace/ring_buffer.c:ring_buffer_unlock_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573792,
      "name": "ring_buffer_nr_dirty_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
size_t ring_buffer_nr_dirty_pages(struct ring_buffer * buffer, int cpu)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer * buffer</code> ➡️ <code>struct trace_buffer * buffer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
