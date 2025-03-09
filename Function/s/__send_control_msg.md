# Function: <code>__send_control_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182768,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:559",
      "file": "drivers/char/virtio_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:port_fops_release",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182768,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584521888,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:565",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521888,
      "name": "__send_control_msg.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584522128,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703968,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:564",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703968,
      "name": "__send_control_msg.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584704208,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584785344,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:564",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584785344,
      "name": "__send_control_msg.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584785584,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585205552,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:561",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585205552,
      "name": "__send_control_msg.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071585205792,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585442960,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:560",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585442960,
      "name": "__send_control_msg.part.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071585443200,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585565296,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:560",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565296,
      "name": "__send_control_msg.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071585565536,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585784768,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585784768,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071585785008,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585928176,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585928176,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071585928416,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586671565,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586667312,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071586675560,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586781437,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586777184,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071591462747,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586658704,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658704,
      "name": "__send_control_msg.isra.0",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587207120,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587207120,
      "name": "__send_control_msg.isra.0",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588505392,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:548",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505392,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589946768,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:540",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589946768,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590256032,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:541",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590256032,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590597008,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:538",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590597008,
      "name": "__send_control_msg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498753184,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498753184,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    },
    {
      "addr": 18446603336498753488,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231376452,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_restore",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:init_port_console",
        "drivers/char/virtio_console.c:port_fops_open",
        "drivers/char/virtio_console.c:port_fops_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231376452,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291914668,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:send_control_msg"
      ],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:send_control_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291914144,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 13835058055291914544,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276259196,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/char/virtio_console.c:send_control_msg"
      ],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port",
        "drivers/char/virtio_console.c:send_control_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276258836,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446743936276259080,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689152,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689152,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071585689392,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585548864,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585548864,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071585549104,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585878416,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878416,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071585878656,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
```

```json
{
  "name": "__send_control_msg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585986960,
      "name": "__send_control_msg",
      "external": false,
      "loc": "drivers/char/virtio_console.c:547",
      "file": "drivers/char/virtio_console.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:virtcons_probe",
        "drivers/char/virtio_console.c:add_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585986960,
      "name": "__send_control_msg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071585987200,
      "name": "__send_control_msg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
ssize_t __send_control_msg(struct ports_device * portdev, u32 port_id, unsigned int event, unsigned int value)
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
