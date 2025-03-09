# Function: <code>event_trigger_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580309536,
      "name": "event_trigger_init",
      "external": false,
      "loc": "kernel/trace/trace_events_trigger.c:404",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580309536,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580352384,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:416",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580352384,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580399344,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:416",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399344,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580410832,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:417",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580410832,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580466272,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:417",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580466272,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 12
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580529785,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:416",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526240,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580587641,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:405",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580584080,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580644849,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:405",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641232,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580691553,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687888,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580796188,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:418",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793056,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580784204,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:418",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580781072,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580789671,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:419",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786560,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580975479,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:431",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971760,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581222854,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:444",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_trigger_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215808,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int event_trigger_init(struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581541574,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:445",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_trigger_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581533680,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int event_trigger_init(struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581660966,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:447",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_trigger_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581653088,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int event_trigger_init(struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581777045,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:447",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_parse",
        "kernel/trace/trace_events_trigger.c:event_trigger_parse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581769088,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492000548,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491996424,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225935512,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225931652,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285131284,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285123264,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272265796,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272262392,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580660353,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580656688,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580606561,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602896,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580651601,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647936,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
int event_trigger_init(struct event_trigger_ops * ops, struct event_trigger_data * data)
```

```json
{
  "name": "event_trigger_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580709105,
      "name": "event_trigger_init",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:412",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_trigger.c:event_enable_trigger_func",
        "kernel/trace/trace_events_trigger.c:event_trigger_callback"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705440,
      "name": "event_trigger_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 7
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct event_trigger_ops * ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, data</code> ➡️ <code>data</code>
</li>
</ul>
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
