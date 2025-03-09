# Function: <code>suspend_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579689883,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:313",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579709178,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:315",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579736715,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:338",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579732574,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:363",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765597,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:390",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579799870,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579846494,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:397",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:401",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880352,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1345
    },
    {
      "addr": 18446744071579882471,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579930512,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    },
    {
      "addr": 18446744071579932680,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975056,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
    },
    {
      "addr": 18446744071579976979,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961904,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    },
    {
      "addr": 18446744071591292319,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964640,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 803
    },
    {
      "addr": 18446744071591235142,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:389",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094272,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446744071592123284,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:390",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580231792,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 974
    },
    {
      "addr": 18446744071593892653,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:397",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580425088,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
    },
    {
      "addr": 18446744071595983837,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:397",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580494432,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071596502213,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:397",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554320,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
    },
    {
      "addr": 18446744071597399899,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491141448,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491141448,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225137872,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284034060,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579837846,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890784,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    },
    {
      "addr": 18446744071579892952,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```

```json
{
  "name": "suspend_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "suspend_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:391",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936624,
      "name": "suspend_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
    },
    {
      "addr": 18446744071579938936,
      "name": "suspend_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
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
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int suspend_enter(suspend_state_t state, bool * wakeup)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
