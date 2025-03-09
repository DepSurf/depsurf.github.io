# Function: <code>ktime_get_real_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580391456,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:214",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586255431,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:214",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_tcpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580391456,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580459200,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583495766,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586680200,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580459200,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580521648,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583635910,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586864840,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:230",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_sequence_number",
        "net/core/secure_seq.c:secure_tcpv6_sequence_number"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580521648,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580554240,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:219",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583675894,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:219",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586987632,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:219",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554240,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580635008,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:99",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583933590,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:99",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587485980,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:99",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635008,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580761568,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:114",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584118149,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:114",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587791166,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:114",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580761568,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580828384,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:129",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584201477,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:129",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587925262,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:129",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828384,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580923344,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584390325,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588234158,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580923344,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580977536,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584525909,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588438878,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588796362,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580977536,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581144064,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589307194,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589674706,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144064,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581184112,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:156",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585380550,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:156",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589306154,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:156",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589706322,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:156",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184112,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581202480,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585265574,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589200110,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589587833,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581202480,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581442128,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583664499,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585721651,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589922043,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590332507,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581442128,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581783376,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584233251,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586892417,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:debounce_work_func",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:edge_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591453620,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591919375,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581783376,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582209152,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584876803,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588039584,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593221364,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593724303,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209152,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582409168,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585104026,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588314224,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593681604,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595912543,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409168,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582577392,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:158",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585336394,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:158",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:ext4_run_li_request",
        "fs/ext4/super.c:ext4_run_li_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607121,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:158",
      "file": "drivers/gpio/gpiolib-cdev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib-cdev.c:line_event_timestamp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594459732,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:158",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596745825,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:158",
      "file": "net/devlink/health.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/devlink/health.c:devlink_health_do_dump"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582577392,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492326272,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336496703296,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501962164,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502367104,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492326272,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224528864,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "arch/arm/common/bL_switcher.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu",
        "arch/arm/common/bL_switcher.c:bL_switch_to",
        "arch/arm/common/bL_switcher.c:bL_switch_to"
      ],
      "caller_func": []
    },
    {
      "addr": 3226218312,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3230000460,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 3234715960,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 3235103880,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226218312,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285572576,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290795696,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295386652,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295904576,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285572576,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272451138,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275469914,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278263120,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278583268,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272451138,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580946336,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584482837,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588045662,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588402746,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580946336,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580892400,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584420965,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587758750,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588115434,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892400,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580937584,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584477573,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588377438,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588734922,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588937905,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/netfilter/nf_conntrack_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588942136,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/netfilter/nf_conntrack_standalone.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_standalone.c:ct_seq_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995277,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/netfilter/nf_conntrack_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580937584,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
u64 ktime_get_real_ns()
```

```json
{
  "name": "ktime_get_real_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580999168,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584583685,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:lineevent_irq_handler",
        "drivers/gpio/gpiolib.c:lineevent_irq_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588513134,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/secure_seq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/secure_seq.c:secure_dccpv6_sequence_number",
        "net/core/secure_seq.c:secure_dccp_sequence_number",
        "net/core/secure_seq.c:secure_tcp_seq",
        "net/core/secure_seq.c:secure_tcpv6_seq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588875386,
      "name": "ktime_get_real_ns",
      "external": false,
      "loc": "include/linux/timekeeping.h:157",
      "file": "net/core/devlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999168,
      "name": "ktime_get_real_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
