# Function: <code>unregister_event_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595120049,
      "name": "unregister_event_command",
      "external": false,
      "loc": "kernel/trace/trace_events_trigger.c:337",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595120049,
      "name": "unregister_event_command.isra.5",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 120
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595289532,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:350",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595289532,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595536867,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:350",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595536867,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596456933,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:351",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596456933,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602782804,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:351",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602782804,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602956714,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:350",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602956714,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604754628,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:339",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604754628,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604856883,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:339",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604856883,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604891013,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604891013,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609215407,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:352",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609215407,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612282016,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:352",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612282016,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614422034,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:353",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614422034,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615359113,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:365",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615359113,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617146044,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:379",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617146044,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627826320,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:380",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627826320,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619590256,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:382",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619590256,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621893648,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:382",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621893648,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336510928512,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336510928512,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243417348,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243417348,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302571888,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302571888,
      "name": "unregister_event_command",
      "section": ".init.text",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270662310,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270662310,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604796470,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604796470,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604765398,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604765398,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604873657,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604873657,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
```

```json
{
  "name": "unregister_event_command",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604895194,
      "name": "unregister_event_command",
      "external": true,
      "loc": "kernel/trace/trace_events_trigger.c:346",
      "file": "kernel/trace/trace_events_trigger.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_trigger.c:register_trigger_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds",
        "kernel/trace/trace_events_hist.c:register_trigger_hist_enable_disable_cmds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604895194,
      "name": "unregister_event_command",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 127
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
int unregister_event_command(struct event_command * cmd)
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
