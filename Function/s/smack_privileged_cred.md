# Function: <code>smack_privileged_cred</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160224,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:636",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160224,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276432,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:636",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276432,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463760,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463760,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569712,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569712,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921968,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921968,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584042128,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:654",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042128,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070656,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:654",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070656,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584442480,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:656",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442480,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585074304,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:653",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_uring_sqpoll",
        "security/smack/smack_lsm.c:smack_uring_override_creds",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074304,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796320,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:650",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_uring_sqpoll",
        "security/smack/smack_lsm.c:smack_uring_override_creds",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796320,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586028064,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:650",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_uring_sqpoll",
        "security/smack/smack_lsm.c:smack_uring_override_creds",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028064,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276544,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:650",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_uring_sqpoll",
        "security/smack/smack_lsm.c:smack_uring_override_creds",
        "security/smack/smack_lsm.c:smack_watch_key",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smk_tskacc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276544,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495345952,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495345952,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228721820,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228721820,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289353136,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289353136,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274556448,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274556448,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538448,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538448,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475504,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475504,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522224,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522224,
      "name": "smack_privileged_cred",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```

```json
{
  "name": "smack_privileged_cred",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619104,
      "name": "smack_privileged_cred",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_file_send_sigiotask",
        "security/smack/smack_lsm.c:smk_ptrace_rule_check",
        "security/smack/smack_access.c:smack_privileged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619104,
      "name": "smack_privileged_cred",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool smack_privileged_cred(int cap, const struct cred * cred)
```
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
