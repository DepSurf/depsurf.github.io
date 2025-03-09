# Function: <code>tick_check_preferred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878912,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_replacement",
        "kernel/time/tick-common.c:tick_check_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579878912,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579908432,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908432,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938880,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579938880,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579946800,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946800,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579992496,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992496,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044576,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:263",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044576,
      "name": "tick_check_preferred",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580091424,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:259",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580091424,
      "name": "tick_check_preferred",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580135280,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580135280,
      "name": "tick_check_preferred",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580183424,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580183424,
      "name": "tick_check_preferred",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580248656,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580248656,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580232560,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580232560,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580238347,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580387704,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580605378,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580869090,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:304",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580952850,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:303",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581044434,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:303",
      "file": "kernel/time/tick-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-common.c:tick_check_replacement"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491407104,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491407104,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225403752,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225403752,
      "name": "tick_check_preferred",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284353616,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284353616,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271884144,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271884144,
      "name": "tick_check_preferred",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580152624,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580152624,
      "name": "tick_check_preferred",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098144,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098144,
      "name": "tick_check_preferred",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143696,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143696,
      "name": "tick_check_preferred",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
```

```json
{
  "name": "tick_check_preferred",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195648,
      "name": "tick_check_preferred",
      "external": false,
      "loc": "kernel/time/tick-common.c:301",
      "file": "kernel/time/tick-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-common.c:tick_check_new_device",
        "kernel/time/tick-common.c:tick_check_replacement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195648,
      "name": "tick_check_preferred",
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
bool tick_check_preferred(struct clock_event_device * curdev, struct clock_event_device * newdev)
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
