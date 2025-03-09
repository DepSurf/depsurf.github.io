# Function: <code>securityfs_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252752,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:187",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252752,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471520,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:240",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471520,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563984,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:239",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:aafs_remove_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_rmdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563984,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582653440,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:289",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653440,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582808576,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:289",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808576,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583002672,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:289",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002672,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583116000,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:290",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583116000,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302864,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302864,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407520,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407520,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748128,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748128,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868272,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868272,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894432,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894432,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258256,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258256,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870640,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870640,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585576160,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585576160,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585807424,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807424,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055840,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055840,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495161584,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495161584,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228548804,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228548804,
      "name": "securityfs_remove",
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289096960,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289096960,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274406398,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274406398,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376256,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376256,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313360,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313360,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583360032,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583360032,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
void securityfs_remove(struct dentry * dentry)
```

```json
{
  "name": "securityfs_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455216,
      "name": "securityfs_remove",
      "external": true,
      "loc": "security/inode.c:295",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/apparmor/apparmorfs.c:entry_remove_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_teardown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455216,
      "name": "securityfs_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
