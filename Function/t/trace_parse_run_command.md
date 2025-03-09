# Function: <code>trace_parse_run_command</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580382128,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:8295",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580382128,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:8400",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444424,
      "name": "trace_parse_run_command.cold.85",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580443584,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:8474",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500086,
      "name": "trace_parse_run_command.cold.85",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580499280,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:8979",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556636,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580555392,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604231,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580603184,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9321",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702581,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580700736,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9454",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320210,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580691584,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9776",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591262536,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580695696,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9938",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592171634,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580872448,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9984",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593945204,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581103008,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411360,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:10079",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411360,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581506336,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:10244",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581506336,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(const char *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617824,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:10439",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_synth.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617824,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491902360,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491902360,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225844796,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225844796,
      "name": "trace_parse_run_command",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284990576,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284990576,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272190264,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272190264,
      "name": "trace_parse_run_command",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573031,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580571984,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519665,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580518624,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580564279,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580563232,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```

```json
{
  "name": "trace_parse_run_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "trace_parse_run_command",
      "external": true,
      "loc": "kernel/trace/trace.c:9035",
      "file": "kernel/trace/trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:synth_events_write",
        "kernel/trace/trace_kprobe.c:probes_write",
        "kernel/trace/trace_dynevent.c:dyn_event_write",
        "kernel/trace/trace_uprobe.c:probes_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580620999,
      "name": "trace_parse_run_command.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580619952,
      "name": "trace_parse_run_command",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
ssize_t trace_parse_run_command(struct file * file, const char * buffer, size_t count, loff_t * ppos, int (*)(int, char * *) createfn)
```
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(int, char * *) createfn</code> ➡️ <code>int (*)(const char *) createfn</code>
</li>
</ul>
</details>
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
