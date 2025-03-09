# Function: <code>securityfs_create_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582252720,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:166",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582252720,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582471488,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:219",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582471488,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563952,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:218",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aafs_create_dir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563952,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582653184,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:222",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582653184,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808320,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:222",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808320,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583002416,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:222",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583002416,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115744,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:223",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115744,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302688,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302688,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583407344,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583407344,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583747952,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747952,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583868096,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583868096,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583894256,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583894256,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258080,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258080,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584870416,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584870416,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585575904,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585575904,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585807168,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585807168,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586055584,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586055584,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495161368,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495161368,
      "name": "securityfs_create_dir",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228548608,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228548608,
      "name": "securityfs_create_dir",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289096704,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289096704,
      "name": "securityfs_create_dir",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274406214,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274406214,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376080,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376080,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583313184,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583313184,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583359856,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583359856,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
struct dentry * securityfs_create_dir(const char * name, struct dentry * parent)
```

```json
{
  "name": "securityfs_create_dir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583455040,
      "name": "securityfs_create_dir",
      "external": true,
      "loc": "security/inode.c:228",
      "file": "security/inode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/tomoyo/securityfs_if.c:tomoyo_initerface_init",
        "security/apparmor/apparmorfs.c:entry_create_dir",
        "security/safesetid/securityfs.c:safesetid_init_securityfs",
        "security/integrity/iint.c:integrity_fs_init",
        "security/integrity/ima/ima_fs.c:ima_fs_init",
        "security/integrity/evm/evm_secfs.c:evm_init_secfs",
        "drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583455040,
      "name": "securityfs_create_dir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
