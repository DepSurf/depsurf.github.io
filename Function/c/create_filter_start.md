# Function: <code>create_filter_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580305296,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1909",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:create_filter",
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305296,
      "name": "create_filter_start.constprop.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580345840,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1856",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580345840,
      "name": "create_filter_start.constprop.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580392336,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1889",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580392336,
      "name": "create_filter_start.constprop.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580403360,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1889",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580403360,
      "name": "create_filter_start.constprop.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1391
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580458800,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1888",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580458800,
      "name": "create_filter_start.constprop.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1391
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580518704,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1660",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580518704,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580575968,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1653",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580575968,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633120,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1675",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633120,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580679760,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580679760,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580786160,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580786160,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580774128,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1656",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774128,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580778976,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1656",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778976,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580963424,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1749",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580963424,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581206832,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1777",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581206832,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581524912,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1874",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524912,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581643520,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1965",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643520,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581755728,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:2226",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_event_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581755728,
      "name": "create_filter_start.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491987992,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491987992,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225923264,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225923264,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285112016,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285112016,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272255494,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272255494,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580648560,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648560,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580594768,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580594768,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639808,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639808,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```

```json
{
  "name": "create_filter_start",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580697312,
      "name": "create_filter_start",
      "external": false,
      "loc": "kernel/trace/trace_events_filter.c:1677",
      "file": "kernel/trace/trace_events_filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:apply_subsystem_event_filter",
        "kernel/trace/trace_events_filter.c:create_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697312,
      "name": "create_filter_start",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int create_filter_start(char * filter_string, bool set_str, struct filter_parse_error * * pse, struct event_filter * * filterp)
```
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
