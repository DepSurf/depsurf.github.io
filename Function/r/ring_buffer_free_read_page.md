# Function: <code>ring_buffer_free_read_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183088,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4438",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release",
        "kernel/trace/trace.c:tracing_buffers_splice_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183088,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580217984,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4433",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580217984,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580259344,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4402",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259344,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282544,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4438",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282544,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580324272,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4430",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580324272,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580398416,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4592",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398416,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580440208,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4661",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580440208,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580494288,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4639",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494288,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580542544,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580542544,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580638144,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4732",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638144,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628128,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5342",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628128,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580636832,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5451",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580636832,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809152,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5456",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809152,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021600,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5498",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021600,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581322592,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5605",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581322592,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416784,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5637",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416784,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void ring_buffer_free_read_page(struct trace_buffer * buffer, int cpu, struct buffer_data_read_page * data_page)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524816,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:5565",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release",
        "kernel/trace/trace.c:tracing_buffers_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524816,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491826992,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491826992,
      "name": "ring_buffer_free_read_page",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225781736,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225781736,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284909632,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284909632,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272133894,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:buffer_spd_release",
        "kernel/trace/trace.c:buffer_pipe_buf_release",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272133894,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580511344,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511344,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580458848,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458848,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580502592,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580502592,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ring_buffer_free_read_page(struct ring_buffer * buffer, int cpu, void * data)
```

```json
{
  "name": "ring_buffer_free_read_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580558928,
      "name": "ring_buffer_free_read_page",
      "external": true,
      "loc": "kernel/trace/ring_buffer.c:4640",
      "file": "kernel/trace/ring_buffer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:tracing_buffers_splice_read",
        "kernel/trace/trace.c:tracing_buffers_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580558928,
      "name": "ring_buffer_free_read_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>buffer, data</code> ➡️ <code>buffer, cpu, data</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct buffer_data_read_page * data_page</code>
</li>
<li>
<b>Param removed. </b>
<code>void * data</code>
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
