# Function: <code>yield</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587366656,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:4689",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_kill",
        "fs/buffer.c:free_more_memory",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587366656,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867488,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:4940",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "fs/buffer.c:free_more_memory",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867488,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588082032,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:4979",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "fs/buffer.c:free_more_memory",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588082032,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588308752,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:4880",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "fs/buffer.c:free_more_memory",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308752,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588874112,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:4925",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874112,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252240,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5050",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252240,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589494480,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5033",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589494480,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589955152,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5486",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589955152,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182816,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182816,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591201024,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5910",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591201024,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591696080,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:6730",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591696080,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591638592,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:7081",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591638592,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592812384,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:8279",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592812384,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594714416,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:8571",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594714416,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596461504,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:8755",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596461504,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597003216,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:8912",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597003216,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597932416,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:8916",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597932416,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503925904,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503925904,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236535660,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236535660,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297773232,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297773232,
      "name": "yield",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279794610,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279794610,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589785104,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589785104,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589507568,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589507568,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590228512,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590228512,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void yield()
```

```json
{
  "name": "yield",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590278912,
      "name": "yield",
      "external": true,
      "loc": "kernel/sched/core.c:5677",
      "file": "kernel/sched/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill",
        "drivers/usb/core/message.c:usb_sg_wait",
        "net/sched/sch_generic.c:dev_deactivate_many",
        "net/netlink/af_netlink.c:netlink_broadcast_filtered"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590278912,
      "name": "yield",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
