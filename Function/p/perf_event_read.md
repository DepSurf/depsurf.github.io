# Function: <code>perf_event_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580398656,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3342",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:_perf_event_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580398656,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 324
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580468656,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3543",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580468656,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580531968,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3631",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580531968,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580562784,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3724",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:perf_event_read_value",
        "kernel/events/core.c:perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562784,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580644656,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3640",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644656,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774208,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3973",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774208,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580840816,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3974",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840816,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936608,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:3994",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936608,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580989952,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580989952,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581158752,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4314",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581158752,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581200816,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4391",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581200816,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581217664,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4471",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581217664,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581457424,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4578",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581457424,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 683
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581805088,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4476",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805088,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582235232,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4596",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582235232,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582434752,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4596",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582434752,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 637
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582603344,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4640",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582603344,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492341800,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492341800,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 640
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226229432,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226229432,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285584560,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285584560,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272460150,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272460150,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 442
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580958752,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580958752,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904880,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904880,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950000,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950000,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
int perf_event_read(struct perf_event * event, bool group)
```

```json
{
  "name": "perf_event_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581013536,
      "name": "perf_event_read",
      "external": false,
      "loc": "kernel/events/core.c:4091",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:_perf_event_reset",
        "kernel/events/core.c:__perf_read_group_add",
        "kernel/events/core.c:__perf_event_read_value",
        "kernel/events/core.c:__perf_event_read_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581013536,
      "name": "perf_event_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 587
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
