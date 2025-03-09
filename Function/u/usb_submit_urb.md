# Function: <code>usb_submit_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202496,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:324",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202496,
      "name": "usb_submit_urb.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1364
    },
    {
      "addr": 18446744071585203872,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585594640,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:324",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594640,
      "name": "usb_submit_urb.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1318
    },
    {
      "addr": 18446744071585595968,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585782240,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:327",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782240,
      "name": "usb_submit_urb.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1324
    },
    {
      "addr": 18446744071585783568,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585869280,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:327",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869280,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1369
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586309280,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586309280,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1447
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566080,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566080,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1438
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586715120,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_irq",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586715120,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1448
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970384,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:351",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970384,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169424,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169424,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588018672,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018672,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1423
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070832,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:367",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070832,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1474
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953616,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:367",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953616,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1469
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:367",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbfs_start_wait_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592566451,
      "name": "usb_submit_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071588564256,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1729
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:367",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbfs_start_wait_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594445398,
      "name": "usb_submit_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071589974912,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1761
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:368",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbfs_start_wait_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596271876,
      "name": "usb_submit_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071591568464,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1724
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:368",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbfs_start_wait_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596801682,
      "name": "usb_submit_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071591990208,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1739
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:368",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:usbfs_start_wait_urb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597725288,
      "name": "usb_submit_urb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071592730128,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1642
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500248680,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500248680,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1420
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232723528,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232723528,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293543168,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293543168,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1892
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277165028,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277165028,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1248
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875504,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875504,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816640,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816640,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123984,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123984,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
int usb_submit_urb(struct urb * urb, gfp_t mem_flags)
```

```json
{
  "name": "usb_submit_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587231088,
      "name": "usb_submit_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:352",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_resubmit_irq_urb",
        "drivers/usb/core/message.c:usb_sg_wait",
        "drivers/usb/core/message.c:usb_start_wait_urb",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587231088,
      "name": "usb_submit_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1497
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
