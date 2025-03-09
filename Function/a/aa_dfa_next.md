# Function: <code>aa_dfa_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488288,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:425",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_to_local"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488288,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582721136,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:429",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582721136,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815792,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:429",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815792,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903552,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:429",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903552,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061664,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:429",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061664,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262736,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:483",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262736,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380592,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:483",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380592,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567344,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567344,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673072,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673072,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584036288,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:518",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584036288,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584155536,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:518",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584155536,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584182592,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:518",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584182592,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567616,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:518",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567616,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585213280,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:517",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:profile_signal_perm",
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_bind_perm",
        "security/apparmor/af_unix.c:profile_bind_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585213280,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585945408,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:517",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:profile_signal_perm",
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585945408,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586178336,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:473",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:profile_signal_perm",
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/notify.c:notification_match",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586178336,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586429616,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:473",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/capability.c:aa_profile_capget",
        "security/apparmor/capability.c:profile_capable",
        "security/apparmor/ipc.c:profile_signal_perm",
        "security/apparmor/lib.c:aa_profile_label_perm",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:find_attach",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/policy_unpack.c:unpack_pdb",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_unix.c:profile_listen_perm",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/af_inet.c:match_addr_label",
        "security/apparmor/notify.c:notification_match",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586429616,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495467648,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495467648,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228834220,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228834220,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289521616,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289521616,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274654982,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274654982,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641808,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641808,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578864,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578864,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583625584,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625584,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
unsigned int aa_dfa_next(struct aa_dfa * dfa, unsigned int state, const char c)
```

```json
{
  "name": "aa_dfa_next",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723648,
      "name": "aa_dfa_next",
      "external": true,
      "loc": "security/apparmor/match.c:494",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_profile_match_label",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/domain.c:aa_xattrs_match",
        "security/apparmor/policy_unpack.c:unpack_profile",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:match_to_local",
        "security/apparmor/af_unix.c:match_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723648,
      "name": "aa_dfa_next",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
