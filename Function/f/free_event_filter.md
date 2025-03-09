# Function: <code>free_event_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307088,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:847",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307088,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580350112,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:844",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580350112,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580397072,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:875",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580397072,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 11
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580408195,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:875",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:create_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580408496,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580463635,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:874",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_filter.c:create_filter"
      ],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580463936,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580523648,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1029",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580523648,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580581408,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1019",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580581408,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580638448,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1038",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580638448,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685184,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685184,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580791488,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580791488,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580779504,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580779504,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580784784,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580784784,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969888,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1111",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969888,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581213744,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1134",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581213744,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531680,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1182",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531680,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650912,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1196",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650912,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581766864,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1315",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter",
        "kernel/trace/trace_eprobe.c:enable_trace_eprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581766864,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491993720,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491993720,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225928844,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225928844,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285118944,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285118944,
      "name": "free_event_filter",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272260132,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272260132,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580653984,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580653984,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580600192,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580600192,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645232,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645232,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void free_event_filter(struct event_filter * filter)
```

```json
{
  "name": "free_event_filter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580702736,
      "name": "free_event_filter",
      "external": true,
      "loc": "kernel/trace/trace_events_filter.c:1040",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:trace_module_notify",
        "kernel/trace/trace_events.c:trace_remove_event_call",
        "kernel/trace/trace_events.c:remove_event_file_dir",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter",
        "kernel/trace/trace_events_trigger.c:set_trigger_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702736,
      "name": "free_event_filter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
