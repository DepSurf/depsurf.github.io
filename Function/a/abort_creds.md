# Function: <code>abort_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509072,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:499",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setregid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/context.c:aa_set_current_hat",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_restore_previous_label"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509072,
      "name": "abort_creds.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579509136,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579524137,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:499",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523328,
      "name": "abort_creds.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579523392,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547785,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:499",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546976,
      "name": "abort_creds.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579547040,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579534473,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:500",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/kmod.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533600,
      "name": "abort_creds.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579533680,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560993,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:500",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:SyS_capset",
        "kernel/sys.c:SyS_setfsgid",
        "kernel/sys.c:SyS_setfsuid",
        "kernel/sys.c:SyS_setresgid",
        "kernel/sys.c:SyS_setresuid",
        "kernel/sys.c:SyS_setuid",
        "kernel/sys.c:SyS_setreuid",
        "kernel/sys.c:SyS_setgid",
        "kernel/sys.c:SyS_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_restore_previous_label",
        "security/apparmor/context.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560096,
      "name": "abort_creds.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579560176,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579588208,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:500",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588208,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625664,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:502",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579625664,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579651191,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650208,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579650288,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579688327,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579687344,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579687424,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729268,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:523",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579727504,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579708388,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:523",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579706512,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579714098,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:535",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713648,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579792306,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:533",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579791856,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579899460,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:533",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579898992,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580051444,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:533",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580050960,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580105892,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:533",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105408,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580151537,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:469",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__do_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/groups.c:set_current_groups",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_lsm_setattr",
        "security/apparmor/task.c:aa_set_current_hat",
        "security/landlock/syscalls.c:__ia32_sys_landlock_restrict_self",
        "security/landlock/syscalls.c:__x64_sys_landlock_restrict_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150320,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490864176,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__arm64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490864176,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224884344,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224882940,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3224883068,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283694944,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283694944,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271522004,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/capability.c:__se_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271522004,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579664647,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663664,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579663744,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579592999,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592016,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579592096,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579661911,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660928,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579661008,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void abort_creds(struct cred * new)
```

```json
{
  "name": "abort_creds",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579695911,
      "name": "abort_creds",
      "external": true,
      "loc": "kernel/cred.c:520",
      "file": "kernel/cred.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ],
      "caller_func": [
        "kernel/capability.c:__ia32_sys_capset",
        "kernel/capability.c:__x64_sys_capset",
        "kernel/sys.c:__sys_setfsgid",
        "kernel/sys.c:__sys_setfsuid",
        "kernel/sys.c:__sys_setresgid",
        "kernel/sys.c:__sys_setresuid",
        "kernel/sys.c:__sys_setuid",
        "kernel/sys.c:__sys_setreuid",
        "kernel/sys.c:__sys_setgid",
        "kernel/sys.c:__sys_setregid",
        "kernel/umh.c:call_usermodehelper_exec_async",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank",
        "fs/exec.c:free_bprm",
        "security/keys/keyctl.c:keyctl_set_reqkey_keyring",
        "security/keys/process_keys.c:join_session_keyring",
        "security/keys/process_keys.c:lookup_user_key",
        "security/keys/process_keys.c:lookup_user_key",
        "security/selinux/hooks.c:selinux_setprocattr",
        "security/apparmor/task.c:aa_set_current_hat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694832,
      "name": "abort_creds.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    },
    {
      "addr": 18446744071579695008,
      "name": "abort_creds",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
