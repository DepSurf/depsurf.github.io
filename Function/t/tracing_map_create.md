# Function: <code>tracing_map_create</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580288688,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:626",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580288688,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580332304,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:626",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580332304,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580344512,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:629",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580344512,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580397984,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:630",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397984,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580459824,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:769",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459824,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515472,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515472,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580571760,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580571760,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580618912,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580618912,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580718688,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580718688,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708128,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708128,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712208,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712208,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890720,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:763",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890720,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125984,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:763",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125984,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581436352,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:763",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581436352,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581533184,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:763",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533184,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581645248,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:768",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581645248,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491920632,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491920632,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285015504,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285015504,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580587712,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580587712,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580534336,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580534336,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580578960,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580578960,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```

```json
{
  "name": "tracing_map_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580635696,
      "name": "tracing_map_create",
      "external": true,
      "loc": "kernel/trace/tracing_map.c:760",
      "file": "kernel/trace/tracing_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635696,
      "name": "tracing_map_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct tracing_map * tracing_map_create(unsigned int map_bits, unsigned int key_size, const struct tracing_map_ops * ops, void * private_data)
```
</details>
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
