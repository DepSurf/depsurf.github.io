# Function: <code>__tasklet_hi_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579391088,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:462",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579391088,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403600,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:462",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403600,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424128,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:476",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424128,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411696,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:476",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411696,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579439232,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:476",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579439232,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579454794,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:493",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454736,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579488602,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/softirq.c:__hrtimer_tasklet_trampoline"
      ],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488544,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506688,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506688,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532736,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532736,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579563136,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:521",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563136,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579544608,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:525",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544608,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549616,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:742",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549616,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579622448,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:741",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622448,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716896,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:755",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716896,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843936,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:755",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843936,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579894160,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:737",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579894160,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579932848,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:737",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb",
        "drivers/usb/core/hcd.c:usb_giveback_urb_bh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579932848,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490677856,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/smsc/smc91x.c:smc_interrupt",
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490677856,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224748664,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224748664,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283501600,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283501600,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414402,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414402,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506400,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506400,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435200,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435200,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506320,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506320,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void __tasklet_hi_schedule(struct tasklet_struct * t)
```

```json
{
  "name": "__tasklet_hi_schedule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539024,
      "name": "__tasklet_hi_schedule",
      "external": true,
      "loc": "kernel/softirq.c:494",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hcd.c:usb_hcd_giveback_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539024,
      "name": "__tasklet_hi_schedule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
