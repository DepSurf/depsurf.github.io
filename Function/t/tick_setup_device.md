# Function: <code>tick_setup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579879296,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_install_replacement",
        "kernel/time/tick-common.c:tick_check_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879296,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908816,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908816,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939264,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939264,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947184,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947184,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992880,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992880,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580044976,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:177",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044976,
      "name": "tick_setup_device.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091824,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:173",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091824,
      "name": "tick_setup_device.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580135680,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135680,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580183824,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183824,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580249040,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:204",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580249040,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232944,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232944,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580237792,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237792,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580387072,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580387072,
      "name": "tick_setup_device",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580604688,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604688,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580868368,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580868368,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580952128,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580952128,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:205",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581043504,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 477
    },
    {
      "addr": 18446744071597416136,
      "name": "tick_setup_device.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491408216,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491408216,
      "name": "tick_setup_device.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225404312,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225404312,
      "name": "tick_setup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284354400,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284354400,
      "name": "tick_setup_device.isra.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271885198,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271885198,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580153024,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580153024,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580098544,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098544,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580144096,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144096,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
  "name": "tick_setup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580196048,
      "name": "tick_setup_device",
      "external": false,
      "loc": "kernel/time/tick-common.c:201",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_install_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196048,
      "name": "tick_setup_device.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
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
void tick_setup_device(struct tick_device * td, struct clock_event_device * newdev, int cpu, const struct cpumask * cpumask)
```
</details>
</li>
</ul>
