# Function: <code>__clockevents_try_unbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579876206,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:392",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579905697,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:392",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579936145,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:392",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579944254,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:392",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579989902,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:397",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580041312,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:397",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580041312,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580088160,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580088160,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580131968,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131968,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580180208,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580180208,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580245652,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580229684,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580235054,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580384128,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:386",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580601284,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:386",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580864580,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:386",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580948324,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:386",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039620,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:386",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:unbind_device_store",
        "kernel/time/clockevents.c:__clockevents_unbind"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491402376,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491402376,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225400292,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225400292,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284347168,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284347168,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271881334,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271881334,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580149408,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149408,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094912,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094912,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580140480,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140480,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
```

```json
{
  "name": "__clockevents_try_unbind",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580192560,
      "name": "__clockevents_try_unbind",
      "external": false,
      "loc": "kernel/time/clockevents.c:387",
      "file": "kernel/time/clockevents.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clockevents.c:sysfs_unbind_tick_dev",
        "kernel/time/clockevents.c:__clockevents_unbind"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192560,
      "name": "__clockevents_try_unbind",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
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
int __clockevents_try_unbind(struct clock_event_device * ced, int cpu)
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
