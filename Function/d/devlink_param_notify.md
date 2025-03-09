# Function: <code>devlink_param_notify</code>

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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3093",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588611248,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071588619648,
      "name": "devlink_param_notify.cold",
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588834112,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588834112,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589712384,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3258",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712384,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589742064,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3803",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589742064,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589627408,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:4006",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589627408,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590377360,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:4591",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_param_unpublish",
        "net/core/devlink.c:devlink_param_publish",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:devlink_param_register_one",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590377360,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591963952,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:5119",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591963952,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
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
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593767536,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:5643",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593767536,
      "name": "devlink_param_notify.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595864384,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/devlink/leftover.c:4125",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devl_param_value_changed",
        "net/devlink/leftover.c:devl_param_driverinit_value_set",
        "net/devlink/leftover.c:devl_params_register",
        "net/devlink/leftover.c:devlink_param_unregister",
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595864384,
      "name": "devlink_param_notify.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596729104,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/devlink/param.c:330",
      "file": "net/devlink/param.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/param.c:devl_param_value_changed",
        "net/devlink/param.c:devl_param_driverinit_value_set",
        "net/devlink/param.c:devl_params_register",
        "net/devlink/param.c:devlink_param_unregister",
        "net/devlink/param.c:devlink_params_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596729104,
      "name": "devlink_param_notify.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502407096,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502407096,
      "name": "devlink_param_notify",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235143604,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:devlink_param_unregister_one",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235143604,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295954560,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295954560,
      "name": "devlink_param_notify",
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278615560,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278615560,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588440496,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588440496,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153184,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153184,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588772672,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588772672,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
```

```json
{
  "name": "devlink_param_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588913200,
      "name": "devlink_param_notify",
      "external": false,
      "loc": "net/core/devlink.c:3125",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_port_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:devlink_param_value_changed",
        "net/core/devlink.c:__devlink_param_driverinit_value_set",
        "net/core/devlink.c:devlink_params_unpublish",
        "net/core/devlink.c:devlink_params_publish",
        "net/core/devlink.c:__devlink_params_register",
        "net/core/devlink.c:__devlink_nl_cmd_param_set_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913200,
      "name": "devlink_param_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void devlink_param_notify(struct devlink * devlink, unsigned int port_index, struct devlink_param_item * param_item, enum devlink_command cmd)
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
