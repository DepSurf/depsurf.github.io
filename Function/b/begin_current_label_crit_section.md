# Function: <code>begin_current_label_crit_section</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582885798,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582944339,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582980886,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582987862,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583040118,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583109057,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583144758,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583152118,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/context.h:209",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583241125,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:150",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583315313,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:150",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_ptrace_traceme",
        "security/apparmor/lsm.c:apparmor_ptrace_access_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350677,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:150",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583356645,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:150",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583359653,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:aa_write_access",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583434803,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583469333,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583475333,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583546293,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583618419,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583653733,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583659685,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583652309,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583724595,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583760021,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583765973,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584013376,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071584108675,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    },
    {
      "addr": 18446744071584150277,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151920,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584013376,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584091536,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071584151920,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584133824,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071584224885,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    },
    {
      "addr": 18446744071584268613,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584270256,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133824,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071584222816,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    },
    {
      "addr": 18446744071584270256,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584160288,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071584250453,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    },
    {
      "addr": 18446744071584293861,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584295664,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584160288,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071584248112,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071584295664,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544288,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071584636133,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr"
      ]
    },
    {
      "addr": 18446744071584680293,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584682096,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544288,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071584633792,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071584682096,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585184608,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071585276064,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_inode_create"
      ]
    },
    {
      "addr": 18446744071585340005,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585344480,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585184608,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585276064,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071585344480,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585913952,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071586011600,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_inode_create"
      ]
    },
    {
      "addr": 18446744071586080709,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586085424,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913952,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071586011600,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071586085424,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586146064,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071586245584,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_task_prctl",
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_inode_create"
      ]
    },
    {
      "addr": 18446744071586316021,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586320816,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586146064,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586245584,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586320816,
      "name": "begin_current_label_crit_section",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_label * begin_current_label_crit_section()
```

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586395248,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ]
    },
    {
      "addr": 18446744071586508595,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_alloc_security",
        "security/apparmor/lsm.c:apparmor_inode_create"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_userns_create",
        "security/apparmor/lsm.c:do_setattr",
        "security/apparmor/lsm.c:do_setattr",
        "security/apparmor/lsm.c:do_setattr"
      ]
    },
    {
      "addr": 18446744071586572581,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586577616,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/af_unix.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ]
    },
    {
      "addr": 18446744071586587504,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:147",
      "file": "security/apparmor/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/af_inet.c:aa_inet_sock_perm",
        "security/apparmor/af_inet.c:aa_inet_opt_perm",
        "security/apparmor/af_inet.c:aa_inet_msg_perm",
        "security/apparmor/af_inet.c:aa_inet_accept_perm",
        "security/apparmor/af_inet.c:aa_inet_listen_perm",
        "security/apparmor/af_inet.c:aa_inet_connect_perm",
        "security/apparmor/af_inet.c:aa_inet_bind_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395248,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071586500176,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071586577616,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071586587504,
      "name": "begin_current_label_crit_section",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495446244,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495522828,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495560204,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495566580,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228812660,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 3228889952,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 3228923332,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3228929960,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289492560,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289590628,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289651164,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289659760,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274637030,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274700810,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274730524,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274736180,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583621045,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583693331,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583728757,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583734709,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583558101,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583630387,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583665813,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583671765,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583604821,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583677107,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712533,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718485,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "begin_current_label_crit_section",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583701909,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:seq_ns_name_show",
        "security/apparmor/apparmorfs.c:seq_ns_level_show",
        "security/apparmor/apparmorfs.c:seq_ns_nsstacked_show",
        "security/apparmor/apparmorfs.c:seq_ns_stacked_show",
        "security/apparmor/apparmorfs.c:profile_remove",
        "security/apparmor/apparmorfs.c:policy_update"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583776786,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_getpeersec_stream",
        "security/apparmor/lsm.c:apparmor_socket_create",
        "security/apparmor/lsm.c:apparmor_setprocattr",
        "security/apparmor/lsm.c:apparmor_file_alloc_security"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583813029,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/net.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/net.c:aa_sk_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818997,
      "name": "begin_current_label_crit_section",
      "external": false,
      "loc": "security/apparmor/include/cred.h:160",
      "file": "security/apparmor/af_unix.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/af_unix.c:aa_unix_opt_perm",
        "security/apparmor/af_unix.c:aa_unix_accept_perm",
        "security/apparmor/af_unix.c:aa_unix_listen_perm",
        "security/apparmor/af_unix.c:aa_unix_bind_perm",
        "security/apparmor/af_unix.c:aa_unix_sock_perm"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct aa_label * begin_current_label_crit_section()
```
</details>
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
