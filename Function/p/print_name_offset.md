# Function: <code>print_name_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864240,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:51",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_cpu"
      ]
    },
    {
      "addr": 18446744071579889728,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_stats.c:270",
      "file": "kernel/time/timer_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_stats.c:tstats_show",
        "kernel/time/timer_stats.c:tstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864240,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071579889728,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579893552,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:51",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers"
      ]
    },
    {
      "addr": 18446744071579919264,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_stats.c:270",
      "file": "kernel/time/timer_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_stats.c:tstats_show",
        "kernel/time/timer_stats.c:tstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579893552,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071579919264,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579905328,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:51",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers"
      ]
    },
    {
      "addr": 18446744071579949856,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_stats.c:270",
      "file": "kernel/time/timer_stats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_stats.c:tstats_show",
        "kernel/time/timer_stats.c:tstats_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905328,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    },
    {
      "addr": 18446744071579949856,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579914016,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:52",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914016,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959424,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:52",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959424,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580007056,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:50",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007056,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054080,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054080,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097664,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097664,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146640,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146640,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580208448,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_base",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580208448,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491366248,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_active_timers",
        "kernel/time/timer_list.c:print_active_timers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491366248,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225365188,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_tickdevice",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225365188,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284303024,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284303024,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271857332,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271857332,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580115840,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580115840,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061136,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061136,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580106912,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580106912,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
void print_name_offset(struct seq_file * m, void * sym)
```

```json
{
  "name": "print_name_offset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158656,
      "name": "print_name_offset",
      "external": false,
      "loc": "kernel/time/timer_list.c:45",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu",
        "kernel/time/timer_list.c:print_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158656,
      "name": "print_name_offset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void print_name_offset(struct seq_file * m, void * sym)
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
