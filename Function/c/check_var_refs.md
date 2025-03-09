# Function: <code>check_var_refs</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537904,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1343",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537904,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580590784,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1427",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590784,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1581",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580648384,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071580683747,
      "name": "check_var_refs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694800,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694800,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811968,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:746",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811968,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802176,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:749",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802176,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580807856,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:765",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580807856,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002592,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:789",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002592,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581250608,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:963",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581250608,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581572224,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:996",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572224,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692208,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:993",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692208,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581808512,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:986",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_parse",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808512,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492004456,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492004456,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285138048,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285138048,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580663600,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580663600,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580609808,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609808,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580654848,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580654848,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool check_var_refs(struct hist_trigger_data * hist_data)
```

```json
{
  "name": "check_var_refs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580712352,
      "name": "check_var_refs",
      "external": false,
      "loc": "kernel/trace/trace_events_hist.c:1655",
      "file": "kernel/trace/trace_events_hist.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "kernel/trace/trace_events_hist.c:remove_hist_vars"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580712352,
      "name": "check_var_refs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool check_var_refs(struct hist_trigger_data * hist_data)
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
bool check_var_refs(struct hist_trigger_data * hist_data)
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
bool check_var_refs(struct hist_trigger_data * hist_data)
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
