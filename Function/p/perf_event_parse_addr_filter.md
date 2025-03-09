# Function: <code>perf_event_parse_addr_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580466008,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:7945",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_addr_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580528680,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:8134",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_addr_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559968,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:8360",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559968,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 933
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580642368,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:8346",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580642368,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771744,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:8872",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771744,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830992,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:8912",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830992,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580926835,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9214",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580980291,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581155376,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9878",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_set_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581155376,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1026
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197424,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10162",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_set_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197424,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581215248,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10292",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581215248,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1042
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454848,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10404",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454848,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581799696,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10339",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581799696,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582229200,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10705",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582229200,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1131
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429616,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10745",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429616,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1136
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
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582596592,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:10815",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582596592,
      "name": "perf_event_parse_addr_filter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1185
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492336152,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226221920,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285583304,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272452562,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580949091,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895155,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580940339,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "perf_event_parse_addr_filter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581001923,
      "name": "perf_event_parse_addr_filter",
      "external": false,
      "loc": "kernel/events/core.c:9330",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_set_filter"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int perf_event_parse_addr_filter(struct perf_event * event, char * fstr, struct list_head * filters)
```
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
