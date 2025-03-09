# Function: <code>security_ib_endport_sid</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int security_ib_endport_sid(const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759984,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2286",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759984,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int security_ib_endport_sid(const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582916000,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2296",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582916000,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583116000,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2365",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116000,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232032,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2331",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232032,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418832,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2344",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418832,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524736,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524736,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874512,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2397",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874512,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994352,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2454",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994352,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021696,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2493",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021696,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2531",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300645,
      "name": "security_ib_endport_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584391584,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2533",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081969,
      "name": "security_ib_endport_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585017456,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2526",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096922,
      "name": "security_ib_endport_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585734832,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int security_ib_endport_sid(const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2484",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620109,
      "name": "security_ib_endport_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585965584,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int security_ib_endport_sid(const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2494",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525779,
      "name": "security_ib_endport_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586214432,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495293104,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495293104,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228674400,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228674400,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289277264,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289277264,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 716
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274515012,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274515012,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493472,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493472,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430528,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430528,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477248,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477248,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
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
int security_ib_endport_sid(struct selinux_state * state, const char * dev_name, u8 port_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_endport_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573392,
      "name": "security_ib_endport_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/hooks.c:selinux_ib_endport_manage_subnet"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573392,
      "name": "security_ib_endport_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int security_ib_endport_sid(const char * dev_name, u8 port_num, u32 * out_sid)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev_name, port_num, out_sid</code> ➡️ <code>state, dev_name, port_num, out_sid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, dev_name, port_num, out_sid</code> ➡️ <code>dev_name, port_num, out_sid</code>
</li>
</ul>
</details>
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
