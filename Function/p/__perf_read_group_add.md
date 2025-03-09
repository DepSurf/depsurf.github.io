# Function: <code>__perf_read_group_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580394016,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:3917",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580394016,
      "name": "__perf_read_group_add.part.64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580487231,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4225",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580462928,
      "name": "__perf_read_group_add.part.75",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550431,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4322",
      "file": "kernel/events/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580524160,
      "name": "__perf_read_group_add.part.78",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580563472,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4409",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580563472,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645456,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4360",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645456,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 405
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580774992,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4698",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774992,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580841600,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4699",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580841600,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580937424,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4742",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937424,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580990768,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580990768,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581159648,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5065",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read_group",
        "kernel/events/core.c:perf_read_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581159648,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581201712,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5144",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read_group",
        "kernel/events/core.c:perf_read_group"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581201712,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 387
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218560,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5228",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218560,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581458448,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5334",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581458448,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581806128,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5232",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581806128,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236304,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5444",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236304,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582435808,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5444",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582435808,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 485
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582604272,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:5493",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604272,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492342792,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492342792,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226230472,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226230472,
      "name": "__perf_read_group_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285585520,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285585520,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272460890,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272460890,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580959568,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580959568,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580905696,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580905696,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580950816,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580950816,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
```

```json
{
  "name": "__perf_read_group_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014384,
      "name": "__perf_read_group_add",
      "external": false,
      "loc": "kernel/events/core.c:4837",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:perf_read",
        "kernel/events/core.c:perf_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014384,
      "name": "__perf_read_group_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __perf_read_group_add(struct perf_event * leader, u64 read_format, u64 * values)
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
