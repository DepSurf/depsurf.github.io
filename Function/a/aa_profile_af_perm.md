# Function: <code>aa_profile_af_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582480,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:161",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582480,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582825600,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:161",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582825600,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582921472,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:161",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582921472,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980016,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980016,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583143888,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583143888,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583349760,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:163",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_label_sk_perm",
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349760,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468400,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:163",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468400,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583652768,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652768,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583759056,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583759056,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584149328,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:160",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584149328,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267664,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:162",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267664,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292912,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:162",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292912,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:162",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592306619,
      "name": "aa_profile_af_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071584679216,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 414
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:162",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594088227,
      "name": "aa_profile_af_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071585338768,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
int aa_profile_af_perm(struct aa_profile * profile, struct apparmor_audit_data * ad, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:164",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100830,
      "name": "aa_profile_af_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
    },
    {
      "addr": 18446744071586079440,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
int aa_profile_af_perm(struct aa_profile * profile, struct apparmor_audit_data * ad, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:164",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596624077,
      "name": "aa_profile_af_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071586314704,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
int aa_profile_af_perm(struct aa_profile * profile, struct apparmor_audit_data * ad, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:166",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm",
        "security/apparmor/af_inet.c:aa_inet_file_perm",
        "security/apparmor/af_inet.c:inet_label_sock_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_accept_perm",
        "security/apparmor/af_inet.c:aa_inet_listen_perm",
        "security/apparmor/af_inet.c:aa_inet_bind_perm",
        "security/apparmor/af_inet.c:aa_inet_create_perm",
        "security/apparmor/af_inet.c:profile_remote_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597530465,
      "name": "aa_profile_af_perm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071586571264,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495559216,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495559216,
      "name": "aa_profile_af_perm",
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228922360,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228922360,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289649840,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289649840,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274729684,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274729684,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727792,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727792,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583664848,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583664848,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583711568,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583711568,
      "name": "aa_profile_af_perm",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int aa_profile_af_perm(struct aa_profile * profile, struct common_audit_data * sa, u32 request, u16 family, int type)
```

```json
{
  "name": "aa_profile_af_perm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583812064,
      "name": "aa_profile_af_perm",
      "external": true,
      "loc": "security/apparmor/net.c:159",
      "file": "security/apparmor/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/net.c:aa_af_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583812064,
      "name": "aa_profile_af_perm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct apparmor_audit_data * ad</code>
</li>
<li>
<b>Param removed. </b>
<code>struct common_audit_data * sa</code>
</li>
</ul>
</details>
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
