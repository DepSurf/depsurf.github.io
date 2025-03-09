# Function: <code>devlink_port_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:602",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588597744,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071588619116,
      "name": "devlink_port_notify.cold",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588817232,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588817232,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589702288,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:621",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589702288,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589749584,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:821",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589749584,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589619248,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:895",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
        "net/core/devlink.c:devlink_port_function_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589619248,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590384560,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:1040",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
        "net/core/devlink.c:devlink_port_function_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590384560,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591954640,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:1262",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devl_port_unregister",
        "net/core/devlink.c:devl_port_register",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
        "net/core/devlink.c:devlink_port_function_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591954640,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593776848,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:1488",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devl_port_unregister",
        "net/core/devlink.c:devl_port_register",
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit",
        "net/core/devlink.c:devlink_port_function_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593776848,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595873008,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:955",
      "file": "net/devlink/leftover.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:__devlink_port_type_set",
        "net/devlink/leftover.c:devl_port_unregister",
        "net/devlink/leftover.c:devl_port_register_with_ops",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register",
        "net/devlink/leftover.c:devlink_nl_cmd_port_set_doit",
        "net/devlink/leftover.c:devlink_port_function_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595873008,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596698576,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/devlink/port.c:506",
      "file": "net/devlink/port.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/port.c:devlink_port_rel_notify_cb",
        "net/devlink/port.c:__devlink_port_type_set",
        "net/devlink/port.c:devl_port_unregister",
        "net/devlink/port.c:devl_port_register_with_ops",
        "net/devlink/port.c:devlink_nl_port_set_doit",
        "net/devlink/port.c:devlink_port_function_set",
        "net/devlink/port.c:devlink_ports_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596698576,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502389320,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502389320,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235126936,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235126936,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295925888,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295925888,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278601998,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278601998,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423616,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423616,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136304,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136304,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755792,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755792,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
```

```json
{
  "name": "devlink_port_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588896320,
      "name": "devlink_port_notify",
      "external": false,
      "loc": "net/core/devlink.c:604",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/core/devlink.c:devlink_port_register",
        "net/core/devlink.c:devlink_nl_cmd_port_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896320,
      "name": "devlink_port_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
void devlink_port_notify(struct devlink_port * devlink_port, enum devlink_command cmd)
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
