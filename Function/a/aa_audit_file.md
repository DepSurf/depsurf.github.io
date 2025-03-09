# Function: <code>aa_audit_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582546896,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:103",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/file.c:path_name",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582546896,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787232,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:103",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787232,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582882624,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:103",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882624,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952720,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:105",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952720,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583114832,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:105",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114832,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320560,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:105",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320560,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439056,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:106",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439056,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624096,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624096,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730272,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730272,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112720,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112720,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584231808,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:91",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584231808,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256880,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:93",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256880,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584642832,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:93",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584642832,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585300000,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:94",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585300000,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int aa_audit_file(const struct cred * subj_cred, struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error, bool prompt)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038912,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:201",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038912,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
int aa_audit_file(const struct cred * subj_cred, struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error, bool prompt)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586273712,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:194",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586273712,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
int aa_audit_file(const struct cred * subj_cred, struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error, bool prompt)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586530464,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:196",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:__aa_path_perm",
        "security/apparmor/file.c:path_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586530464,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 737
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495526696,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495526696,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228893128,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:path_name",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228893128,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289606384,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289606384,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274703932,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274703932,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583699008,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699008,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583636064,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636064,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682784,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682784,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int aa_audit_file(struct aa_profile * profile, struct aa_perms * perms, const char * op, u32 request, const char * name, const char * target, struct aa_label * tlabel, kuid_t ouid, const char * info, int error)
```

```json
{
  "name": "aa_audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583782528,
      "name": "aa_audit_file",
      "external": true,
      "loc": "security/apparmor/file.c:102",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_profile",
        "security/apparmor/domain.c:aa_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:build_change_hat",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:profile_onexec",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/domain.c:profile_transition",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_file_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782528,
      "name": "aa_audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param added. </b>
<code>bool prompt</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, perms, op, request, name, target, tlabel, ouid, info, error</code> ➡️ <code>subj_cred, profile, perms, op, request, name, target, tlabel, ouid, info, error, prompt</code>
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
