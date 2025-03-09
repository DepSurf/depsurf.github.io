# Function: <code>usb_alloc_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201856,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:64",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201856,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585594000,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:64",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594000,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781616,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781616,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585868672,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868672,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586308688,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586308688,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586567920,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567920,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586716976,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586716976,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586970096,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:69",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586970096,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169136,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169136,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588021776,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021776,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588070704,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588070704,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587953232,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587953232,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563872,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563872,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589971600,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589971600,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591564816,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:71",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591564816,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591986576,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:71",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591986576,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592726496,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:71",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/usb/core/devio.c:do_proc_bulk",
        "drivers/usb/core/devio.c:do_proc_control"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592726496,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500248496,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500248496,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232723236,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/hub.c:hub_configure",
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232723236,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293542640,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293542640,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277166554,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277166554,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586875216,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875216,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586816352,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586816352,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123696,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123696,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct urb * usb_alloc_urb(int iso_packets, gfp_t mem_flags)
```

```json
{
  "name": "usb_alloc_urb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587230800,
      "name": "usb_alloc_urb",
      "external": true,
      "loc": "drivers/usb/core/urb.c:70",
      "file": "drivers/usb/core/urb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_init",
        "drivers/usb/core/message.c:usb_bulk_msg",
        "drivers/usb/core/message.c:usb_control_msg",
        "drivers/usb/core/devio.c:proc_do_submiturb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230800,
      "name": "usb_alloc_urb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
