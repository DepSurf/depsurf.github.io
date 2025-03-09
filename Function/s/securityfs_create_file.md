# Function: <code>securityfs_create_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252160,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:77",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/inode.c:securityfs_create_dir",
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252160,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 548
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582471497,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:190",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471456,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582563961,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:190",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563920,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582653193,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:194",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653152,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582808329,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:194",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808288,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603052709,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:194",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002384,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604853729,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:195",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115712,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604958763,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302656,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604994327,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407312,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609275138,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_create_entry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747920,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612344015,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_create_entry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868064,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614484651,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_create_entry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894224,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615431344,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_create_entry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258048,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617228319,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_create_entry",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870368,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627938719,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575840,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619701887,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807104,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622008767,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055520,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511037484,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495161272,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243518980,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228548560,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302710444,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289096672,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270750056,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274406138,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604899787,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376048,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604868839,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313152,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604976971,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359824,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct dentry * securityfs_create_file(const char * name, umode_t mode, struct dentry * parent, void * data, const struct file_operations * fops)
```

```json
{
  "name": "securityfs_create_file",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604998497,
      "name": "securityfs_create_file",
      "external": true,
      "loc": "security/inode.c:200",
      "file": "security/inode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/inode.c:securityfs_init",
        "security/inode.c:securityfs_create_dir"
      ],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:aa_create_aafs",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/lockdown/lockdown.c:lockdown_secfs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455008,
      "name": "securityfs_create_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
