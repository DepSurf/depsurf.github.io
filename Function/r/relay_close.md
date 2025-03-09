# Function: <code>relay_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144288,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:812",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144288,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580178400,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:843",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580178400,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220480,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:832",
      "file": "kernel/relay.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220480,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580228800,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:832",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228800,
      "name": "relay_close",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580281552,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:831",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580281552,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:832",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580343783,
      "name": "relay_close.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580343360,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580399368,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399655,
      "name": "relay_close.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071580399232,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580450616,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452421,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580450592,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580499576,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501381,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580499552,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580585312,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:840",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580585056,
      "name": "relay_close.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071580587528,
      "name": "relay_close.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580585312,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580575056,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:755",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580574800,
      "name": "relay_close.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071591317633,
      "name": "relay_close.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580575056,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580578695,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:755",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:sysfs_blk_trace_attr_store",
        "kernel/trace/blktrace.c:blk_trace_setup_queue",
        "kernel/trace/blktrace.c:blk_trace_shutdown",
        "kernel/trace/blktrace.c:do_blk_trace_setup",
        "kernel/trace/blktrace.c:blk_trace_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259761,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580578672,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580748825,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:755",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592165329,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580748800,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963017,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:755",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593938715,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580962992,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581258096,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:752",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258096,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581353200,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:752",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581353200,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581459168,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:752",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581459168,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491778144,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491778144,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225725224,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225725224,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284822816,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284822816,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272094734,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272094734,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 282
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468376,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470181,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580468352,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580415352,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580417157,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580415328,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459624,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580461429,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580459600,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void relay_close(struct rchan * chan)
```

```json
{
  "name": "relay_close",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580515288,
      "name": "relay_close",
      "external": true,
      "loc": "kernel/relay.c:834",
      "file": "kernel/relay.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/blktrace.c:blk_trace_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517093,
      "name": "relay_close.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580515264,
      "name": "relay_close",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
