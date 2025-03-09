# Function: <code>smk_import_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582395312,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:531",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582395312,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582616944,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:531",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smk_fetch",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582616944,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582710096,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:526",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582710096,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 317
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803200,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:526",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803200,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582959600,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:526",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959600,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583159840,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:526",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583159840,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276048,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:526",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276048,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463360,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463360,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583569312,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583569312,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583921424,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583921424,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041776,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:561",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041776,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584070304,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:561",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584070304,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584442128,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:563",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442128,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073920,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:560",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073920,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795904,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:557",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795904,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586027648,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:557",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_add_opt",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027648,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586276080,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:557",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:do_setattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_add_opt",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586276080,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495345480,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495345480,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228721388,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228721388,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289352528,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289352528,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274556024,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274556024,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538048,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538048,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583475104,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583475104,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583521824,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583521824,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct smack_known * smk_import_entry(const char * string, int len)
```

```json
{
  "name": "smk_import_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583618672,
      "name": "smk_import_entry",
      "external": true,
      "loc": "security/smack/smack_access.c:522",
      "file": "security/smack/smack_access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_audit_rule_init",
        "security/smack/smack_lsm.c:smack_setprocattr",
        "security/smack/smack_lsm.c:smack_inode_setsecurity",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_post_setxattr",
        "security/smack/smack_lsm.c:smack_inode_setxattr",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smack_lsm.c:smack_set_mnt_opts",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_parse_label_list",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/smack/smackfs.c:smk_fill_rule",
        "security/smack/smackfs.c:smk_fill_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583618672,
      "name": "smk_import_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
