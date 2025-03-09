# Function: <code>eval_replace</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580390656,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2110",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580445779,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2114",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580507349,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2114",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565061,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2115",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580622107,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2105",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580668827,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580759120,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2309",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580759120,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580747168,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2322",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580747168,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580751870,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2533",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:update_event_printk"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935518,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2538",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:update_event_printk"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581175472,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2557",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_fields",
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581175472,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581494320,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2578",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_fields",
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581494320,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581612320,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2572",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_fields",
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581612320,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```

```json
{
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581725008,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2720",
      "file": "kernel/trace/trace_events.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events.c:update_event_fields",
        "kernel/trace/trace_events.c:update_event_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581725008,
      "name": "eval_replace",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491976324,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225911252,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285093640,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272246944,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580637627,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580583867,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580628875,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
  "name": "eval_replace",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580686379,
      "name": "eval_replace",
      "external": false,
      "loc": "kernel/trace/trace_events.c:2104",
      "file": "kernel/trace/trace_events.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events.c:trace_event_eval_update"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
char * eval_replace(char * ptr, struct trace_eval_map * map, int len)
```
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
