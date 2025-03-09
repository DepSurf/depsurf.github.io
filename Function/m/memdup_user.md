# Function: <code>memdup_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580597600,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:128",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:strndup_user",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580597600,
      "name": "memdup_user",
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580699200,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:128",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580699200,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580765008,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:128",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580765008,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580801392,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:155",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580801392,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580890096,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:155",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:SyS_kexec_file_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580890096,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025824,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:156",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_fill_hdr",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025824,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581103360,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:149",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/bsg-lib.c:bsg_transport_fill_hdr",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/consolemap.c:con_set_unimap",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581103360,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581168256,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:161",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581168256,
      "name": "memdup_user",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226224,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226224,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413712,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:ioctl_file_dedupe_range",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:ethtool_set_tunable",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413712,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456560,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:169",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:ioctl_file_dedupe_range",
        "fs/io_uring.c:__io_uring_register",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ethtool/ioctl.c:set_phy_tunable",
        "net/ethtool/ioctl.c:ethtool_set_tunable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456560,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477504,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:169",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/io_uring.c:__io_uring_register",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477504,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581731472,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:169",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/io_uring.c:__io_uring_register",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/ethtool/ioctl.c:dev_ethtool",
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581731472,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109600,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:170",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/sed-opal.c:sed_ioctl",
        "io_uring/io_uring.c:io_register_restrictions",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109600,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582582960,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:170",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/sed-opal.c:sed_ioctl",
        "io_uring/io_uring.c:io_register_restrictions",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582582960,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582790064,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:193",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/sed-opal.c:sed_ioctl",
        "io_uring/io_uring.c:io_register_restrictions",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:update_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790064,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582964944,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:193",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec.c:__ia32_sys_kexec_load",
        "kernel/kexec.c:__x64_sys_kexec_load",
        "kernel/kexec_file.c:kimage_file_prepare_segments",
        "kernel/watch_queue.c:watch_queue_set_filter",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_write",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/security.c:security_setselfattr",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "block/bsg-lib.c:bsg_transport_sg_io_fn",
        "block/sed-opal.c:sed_ioctl",
        "io_uring/register.c:io_register_restrictions",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_debugfs.c:edid_write",
        "drivers/net/tun.c:update_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_setup_device_legacy",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/bpf/test_run.c:bpf_prog_test_run_syscall",
        "net/bpf/test_run.c:bpf_prog_test_run_raw_tp",
        "net/ethtool/ioctl.c:__dev_ethtool",
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582964944,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492615576,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "virt/kvm/kvm_main.c:kvm_vcpu_ioctl",
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492615576,
      "name": "memdup_user",
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226466644,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/mtd/mtdchar.c:mtdchar_ioctl",
        "drivers/mtd/mtdchar.c:mtdchar_ioctl",
        "drivers/mtd/mtdchar.c:mtdchar_writeoob",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user",
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "sound/core/pcm_native.c:snd_pcm_common_ioctl",
        "sound/core/compress_offload.c:snd_compr_set_params",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226466644,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285932720,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/char/nvram.c:nvram_misc_write",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285932720,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272641306,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl_rdwr",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/mmc/core/block.c:mmc_blk_ioctl_copy_from_user",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272641306,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581195072,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581195072,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141824,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141824,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581186272,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581186272,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * memdup_user(const void * src, size_t len)
```

```json
{
  "name": "memdup_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581249520,
      "name": "memdup_user",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/util.c:strndup_user",
        "fs/ioctl.c:do_vfs_ioctl",
        "fs/proc/base.c:proc_pid_attr_write",
        "fs/pstore/platform.c:pstore_write_user_compat",
        "fs/efivarfs/file.c:efivarfs_file_write",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_verify",
        "security/keys/keyctl_pkey.c:keyctl_pkey_e_d_s",
        "security/smack/smackfs.c:smk_write_revoke_subj",
        "security/apparmor/apparmorfs.c:attr_write",
        "block/sed-opal.c:sed_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/tty/vt/vt.c:con_font_op",
        "drivers/lightnvm/core.c:nvm_ctl_ioctl",
        "drivers/dma-buf/udmabuf.c:udmabuf_ioctl",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/net/ppp/ppp_generic.c:get_filter",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct",
        "drivers/usb/core/devio.c:proc_do_submiturb",
        "drivers/input/misc/uinput.c:uinput_write",
        "drivers/i2c/i2c-dev.c:i2cdev_ioctl",
        "drivers/i2c/i2c-dev.c:i2cdev_write",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "drivers/ptp/ptp_chardev.c:ptp_ioctl",
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:dev_ethtool",
        "net/xfrm/xfrm_state.c:xfrm_user_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581249520,
      "name": "memdup_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
