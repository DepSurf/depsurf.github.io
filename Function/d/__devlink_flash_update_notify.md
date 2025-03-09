# Function: <code>__devlink_flash_update_notify</code>

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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2734",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588604336,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071588619419,
      "name": "__devlink_flash_update_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588826160,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826160,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589716800,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2889",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589716800,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589736832,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:3370",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_flash_update_timeout_notify",
        "net/core/devlink.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736832,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589621856,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:3573",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_flash_update_timeout_notify",
        "net/core/devlink.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589621856,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590367088,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:4143",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_flash_update_timeout_notify",
        "net/core/devlink.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590367088,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591952112,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:4655",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_flash_update_timeout_notify",
        "net/core/devlink.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591952112,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593758608,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:4921",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_compat_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_nl_cmd_flash_update",
        "net/core/devlink.c:devlink_flash_update_timeout_notify",
        "net/core/devlink.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593758608,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595901312,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/devlink/dev.c:891",
      "file": "net/devlink/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_nl_cmd_flash_update",
        "net/devlink/dev.c:devlink_nl_cmd_flash_update",
        "net/devlink/dev.c:devlink_flash_update_timeout_notify",
        "net/devlink/dev.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595901312,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, struct devlink_flash_notify * params)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596685648,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/devlink/dev.c:993",
      "file": "net/devlink/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_compat_flash_update",
        "net/devlink/dev.c:devlink_nl_flash_update_doit",
        "net/devlink/dev.c:devlink_nl_flash_update_doit",
        "net/devlink/dev.c:devlink_flash_update_timeout_notify",
        "net/devlink/dev.c:devlink_flash_update_status_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596685648,
      "name": "__devlink_flash_update_notify.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071596686000,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502399568,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502399568,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235133488,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235133488,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295948480,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295948480,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278611172,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278611172,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588432544,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588432544,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588145232,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588145232,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588764720,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764720,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
```

```json
{
  "name": "__devlink_flash_update_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588905248,
      "name": "__devlink_flash_update_notify",
      "external": false,
      "loc": "net/core/devlink.c:2761",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_flash_update_status_notify",
        "net/core/devlink.c:devlink_flash_update_end_notify",
        "net/core/devlink.c:devlink_flash_update_begin_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905248,
      "name": "__devlink_flash_update_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
void __devlink_flash_update_notify(struct devlink * devlink, enum devlink_command cmd, const char * status_msg, const char * component, long unsigned int done, long unsigned int total)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct devlink_flash_notify * params</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * status_msg</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * component</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int done</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int total</code>
</li>
</ul>
</details>
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
