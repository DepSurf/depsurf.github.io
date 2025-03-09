# Function: <code>do_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582586432,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:177",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071582586432,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582829504,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:177",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071582829504,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925376,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:177",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071582925376,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981680,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:177",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981680,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583145648,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:177",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583145648,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583351120,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583351120,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469744,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583469744,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583654144,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583654144,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583760432,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583760432,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584156096,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584272064,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584299840,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584686272,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585343696,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:187",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_sk_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585343696,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct apparmor_audit_data * ad)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586084576,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:195",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586084576,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586320528,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:195",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320528,
      "name": "do_perms.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct apparmor_audit_data * ad)
```

```json
{
  "name": "do_perms",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586577328,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:195",
      "file": "security/apparmor/af_unix.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_create_perm"
      ]
    },
    {
      "addr": 18446744071586586240,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_inet.c:244",
      "file": "security/apparmor/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071586577328,
      "name": "do_perms.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
    },
    {
      "addr": 18446744071586586240,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495560856,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446603336495560856,
      "name": "do_perms",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228923768,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 3228923768,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289651808,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 13835058055289651808,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274731010,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446743936274731010,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583729168,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583729168,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583666224,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583666224,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583712944,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583712944,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```

```json
{
  "name": "do_perms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583813440,
      "name": "do_perms",
      "external": false,
      "loc": "security/apparmor/af_unix.c:178",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
      "addr": 18446744071583813440,
      "name": "do_perms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int do_perms(struct aa_profile * profile, unsigned int state, u32 request, struct common_audit_data * sa)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct common_audit_data * sa)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct apparmor_audit_data * ad)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int do_perms(struct aa_profile * profile, struct aa_ruleset * rule, unsigned int state, u32 request, struct apparmor_audit_data * ad)
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
