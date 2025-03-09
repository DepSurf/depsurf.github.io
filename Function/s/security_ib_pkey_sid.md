# Function: <code>security_ib_pkey_sid</code>

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
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582759808,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2246",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582759808,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582915824,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2256",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582915824,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115824,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2319",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115824,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583231840,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2285",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583231840,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583418640,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2298",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583418640,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583524544,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583524544,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874320,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2351",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874320,
      "name": "security_ib_pkey_sid",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583994176,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2402",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid_slow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994176,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584021472,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2435",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584021472,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2477",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300625,
      "name": "security_ib_pkey_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071584391328,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2479",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081941,
      "name": "security_ib_pkey_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585017152,
      "name": "security_ib_pkey_sid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2472",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096894,
      "name": "security_ib_pkey_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585734512,
      "name": "security_ib_pkey_sid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2432",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596620089,
      "name": "security_ib_pkey_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585965280,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2442",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525759,
      "name": "security_ib_pkey_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586214128,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495292792,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495292792,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228674152,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228674152,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289276960,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289276960,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274514836,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274514836,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493280,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493280,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583430336,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583430336,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477056,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477056,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int security_ib_pkey_sid(struct selinux_state * state, u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
```

```json
{
  "name": "security_ib_pkey_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583573200,
      "name": "security_ib_pkey_sid",
      "external": true,
      "loc": "security/selinux/ss/services.c:2305",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ibpkey.c:sel_ib_pkey_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583573200,
      "name": "security_ib_pkey_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int security_ib_pkey_sid(u64 subnet_prefix, u16 pkey_num, u32 * out_sid)
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
<code>subnet_prefix, pkey_num, out_sid</code> ➡️ <code>state, subnet_prefix, pkey_num, out_sid</code>
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
<code>state, subnet_prefix, pkey_num, out_sid</code> ➡️ <code>subnet_prefix, pkey_num, out_sid</code>
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
