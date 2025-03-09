# Function: <code>sidtab_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582313280,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:197",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582313280,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 960
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534464,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:197",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534464,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582627280,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:197",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582627280,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 987
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582719216,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:190",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582719216,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582875184,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:191",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582875184,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1026
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * out_sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:191",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074865,
      "name": "sidtab_context_to_sid.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071583073376,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 974
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:339",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190285,
      "name": "sidtab_context_to_sid.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583188144,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:344",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583377656,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583375392,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1697
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583483544,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583481328,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:263",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583829551,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583827552,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:263",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591364367,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583949024,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:264",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591307356,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071583976000,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1049
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:264",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592297306,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071584342144,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1061
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:264",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594078948,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584963200,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1025
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:265",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096064,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585676512,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1059
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:265",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596619285,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071585906752,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:265",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:__security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_compute_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597524975,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071586155376,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1085
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495246456,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495246456,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1540
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228628036,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid",
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228628036,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289215488,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289215488,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2908
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
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274471832,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274471832,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1312
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452280,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583450064,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389352,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583387136,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583436056,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583433840,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int sidtab_context_to_sid(struct sidtab * s, struct context * context, u32 * sid)
```

```json
{
  "name": "sidtab_context_to_sid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sidtab_context_to_sid",
      "external": true,
      "loc": "security/selinux/ss/sidtab.c:338",
      "file": "security/selinux/ss/sidtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_netlbl_secattr_to_sid",
        "security/selinux/ss/services.c:security_sid_mls_copy",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_fs_use",
        "security/selinux/ss/services.c:security_genfs_sid",
        "security/selinux/ss/services.c:security_get_user_sids",
        "security/selinux/ss/services.c:security_node_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_netif_sid",
        "security/selinux/ss/services.c:security_ib_endport_sid",
        "security/selinux/ss/services.c:security_ib_pkey_sid",
        "security/selinux/ss/services.c:security_port_sid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532312,
      "name": "sidtab_context_to_sid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583530096,
      "name": "sidtab_context_to_sid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1653
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 * sid</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 * out_sid</code>
</li>
</ul>
</details>
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
