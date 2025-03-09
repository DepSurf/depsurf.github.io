# Function: <code>print_tickdevice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579866144,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:206",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866144,
      "name": "print_tickdevice.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579895456,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:206",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895456,
      "name": "print_tickdevice.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579907136,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:206",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579907136,
      "name": "print_tickdevice.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915376,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:200",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915376,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579960784,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:200",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579960784,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 679
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580008432,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:198",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008432,
      "name": "print_tickdevice.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580055456,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055456,
      "name": "print_tickdevice.isra.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580099024,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580099024,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580148000,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580148000,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580209904,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580209904,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 656
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580194000,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194000,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580199328,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580199328,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580346048,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346048,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559728,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559728,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580819152,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580819152,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580902448,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580902448,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992976,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:178",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992976,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491366400,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491366400,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225366868,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225366868,
      "name": "print_tickdevice",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284304640,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284304640,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271858712,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271858712,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580117200,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117200,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580062496,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062496,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580108272,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580108272,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_tickdevice",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580160016,
      "name": "print_tickdevice",
      "external": false,
      "loc": "kernel/time/timer_list.c:193",
      "file": "kernel/time/timer_list.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:timer_list_show",
        "kernel/time/timer_list.c:sysrq_timer_list_show",
        "kernel/time/timer_list.c:timer_list_show_tickdevices_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580160016,
      "name": "print_tickdevice.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void print_tickdevice(struct seq_file * m, struct tick_device * td, int cpu)
```
</details>
</li>
</ul>
