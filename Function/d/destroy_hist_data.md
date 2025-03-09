# Function: <code>destroy_hist_data</code>

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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580359104,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:727",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580359104,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580406064,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:727",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580406064,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580419648,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:728",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580419648,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580475248,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:771",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580475248,
      "name": "destroy_hist_data",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541168,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4441",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541168,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580600560,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4527",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600560,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580669710,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5043",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580669456,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 458
    },
    {
      "addr": 18446744071580684013,
      "name": "destroy_hist_data.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580715440,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580715440,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831296,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4261",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831296,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580821616,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4286",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580821616,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825424,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4354",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825424,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581022432,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4449",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022432,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 978
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267104,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4828",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267104,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581591072,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:4959",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591072,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713056,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5036",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713056,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829008,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5028",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829008,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492028208,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492028208,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285168656,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285168656,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580684240,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684240,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580630448,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580630448,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580675488,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580675488,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "destroy_hist_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580732992,
      "name": "destroy_hist_data",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:5153",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:hist_register_trigger",
        "kernel/trace/trace_events_hist.c:event_hist_trigger_free",
        "kernel/trace/trace_events_hist.c:create_hist_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732992,
      "name": "destroy_hist_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 479
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
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
void destroy_hist_data(struct hist_trigger_data * hist_data)
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
