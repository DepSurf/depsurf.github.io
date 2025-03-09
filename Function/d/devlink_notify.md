# Function: <code>devlink_notify</code>

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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:488",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588607344,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071588619491,
      "name": "devlink_notify.cold",
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815248,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815248,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697696,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:501",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697696,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589752896,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:639",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589752896,
      "name": "devlink_notify",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589634656,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:642",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634656,
      "name": "devlink_notify",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590388416,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:739",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590388416,
      "name": "devlink_notify",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591976128,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:956",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591976128,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593787344,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:1132",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_notify_unregister",
        "net/core/devlink.c:devlink_notify_register",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:devlink_reload",
        "net/core/devlink.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593787344,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595901840,
      "name": "devlink_notify",
      "external": true,
      "loc": "net/devlink/dev.c:177",
      "file": "net/devlink/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/leftover.c:devlink_notify_unregister",
        "net/devlink/leftover.c:devlink_notify_register",
        "net/devlink/dev.c:devlink_reload",
        "net/devlink/dev.c:__devlink_reload_stats_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595901840,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596683632,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/devlink/dev.c:199",
      "file": "net/devlink/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_reload",
        "net/devlink/dev.c:__devlink_reload_stats_update",
        "net/devlink/dev.c:devlink_notify_unregister",
        "net/devlink/dev.c:devlink_notify_register",
        "net/devlink/dev.c:devlink_rel_notify_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596683632,
      "name": "devlink_notify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
    },
    {
      "addr": 18446744071596683984,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502387200,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502387200,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235122708,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235122708,
      "name": "devlink_notify",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295930128,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295930128,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278603594,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278603594,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421632,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421632,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588134320,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588134320,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588753808,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588753808,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
```

```json
{
  "name": "devlink_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588894336,
      "name": "devlink_notify",
      "external": false,
      "loc": "net/core/devlink.c:485",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_unregister",
        "net/core/devlink.c:devlink_register",
        "net/core/devlink.c:devlink_nl_cmd_reload"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588894336,
      "name": "devlink_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void devlink_notify(struct devlink * devlink, enum devlink_command cmd)
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
