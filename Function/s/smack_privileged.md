# Function: <code>smack_privileged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395696,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:637",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_load",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395696,
      "name": "smack_privileged",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582617344,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:637",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582617344,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
int smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710496,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_file_open",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710496,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803584,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803584,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959984,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:632",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959984,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583160352,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:673",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583160352,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276560,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:673",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276560,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463888,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463888,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569840,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569840,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583922231,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922400,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584042407,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:691",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584042576,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584070935,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:691",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584071104,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584442765,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:693",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442928,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585074603,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:690",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585074784,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585796635,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:687",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796848,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586028380,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:687",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586028608,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586276860,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:687",
      "file": "security/smack/smack_access.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/smack/smack_access.c:smk_tskacc"
      ],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_key_permission",
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:do_setattr",
        "security/smack/smack_lsm.c:do_setattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586277088,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495346144,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495346144,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228721980,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228721980,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289353392,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289353392,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274556600,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274556600,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538576,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538576,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475632,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475632,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522352,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522352,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool smack_privileged(int cap)
```

```json
{
  "name": "smack_privileged",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583619248,
      "name": "smack_privileged",
      "external": true,
      "loc": "security/smack/smack_access.c:669",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_unix_may_send",
        "security/smack/smack_lsm.c:smack_unix_stream_connect",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_removexattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_syslog",
        "security/smack/smack_access.c:smk_tskacc",
        "security/smack/smackfs.c:smk_write_ptrace",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_change_rule",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/smack/smackfs.c:smk_write_load2",
        "security/smack/smackfs.c:smk_write_logging",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_mapped",
        "security/smack/smackfs.c:smk_write_direct",
        "security/smack/smackfs.c:smk_write_doi",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_write_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583619248,
      "name": "smack_privileged",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
