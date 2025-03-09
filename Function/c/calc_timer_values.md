# Function: <code>calc_timer_values</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580400428,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4400",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580471487,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4690",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
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
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580534527,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4787",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580569024,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4879",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628048,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4830",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628048,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756912,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5186",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756912,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580823232,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5195",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580823232,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917904,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5241",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917904,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580971360,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580971360,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140560,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5605",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140560,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581180592,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5684",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581180592,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581199072,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5768",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581199072,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581444432,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4493",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:perf_event_read_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581444432,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581787392,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4391",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:perf_event_read_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581787392,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 343
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582212240,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4511",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:perf_event_read_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582212240,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412256,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4511",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:perf_event_read_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412256,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582580560,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:4546",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage",
        "kernel/events/core.c:perf_event_read_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582580560,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492322032,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492322032,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226207340,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226207340,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285562464,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285562464,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272447226,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272447226,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940160,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940160,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886224,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886224,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580931408,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580931408,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
```

```json
{
  "name": "calc_timer_values",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992176,
      "name": "calc_timer_values",
      "external": false,
      "loc": "kernel/events/core.c:5336",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_output_read",
        "kernel/events/core.c:perf_event_update_userpage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992176,
      "name": "calc_timer_values",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
void calc_timer_values(struct perf_event * event, u64 * now, u64 * enabled, u64 * running)
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
