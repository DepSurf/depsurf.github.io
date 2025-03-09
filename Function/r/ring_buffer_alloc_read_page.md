# Function: <code>ring_buffer_alloc_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580182752,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4413",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580182752,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217648,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4408",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217648,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580259024,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4377",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259024,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580282688,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4391",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282688,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580334640,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4383",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580334640,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580397216,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4545",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397216,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580449216,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4614",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580449216,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580504080,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4592",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580504080,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580551888,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580551888,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580644208,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4685",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644208,
      "name": "ring_buffer_alloc_read_page.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071580644432,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580634928,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5295",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580634928,
      "name": "ring_buffer_alloc_read_page.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    },
    {
      "addr": 18446744071580635152,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580644224,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5404",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644224,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580816736,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5409",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816736,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581037872,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5451",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037872,
      "name": "ring_buffer_alloc_read_page.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    },
    {
      "addr": 18446744071581038160,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581338000,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5558",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581338000,
      "name": "ring_buffer_alloc_read_page.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071581338304,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581432352,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5590",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432352,
      "name": "ring_buffer_alloc_read_page.part.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071581432656,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct buffer_data_read_page * ring_buffer_alloc_read_page(struct trace_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581541488,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5511",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541488,
      "name": "ring_buffer_alloc_read_page.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071581541936,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491826360,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491826360,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225781348,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225781348,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284909072,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284909072,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 560
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272136346,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272136346,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580520688,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520688,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580461472,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461472,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580511936,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511936,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void * ring_buffer_alloc_read_page(struct ring_buffer * buffer, int cpu)
```

```json
{
  "name": "ring_buffer_alloc_read_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568272,
      "name": "ring_buffer_alloc_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4593",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568272,
      "name": "ring_buffer_alloc_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>struct buffer_data_read_page *</code>
</li>
</ul>
</details>
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
