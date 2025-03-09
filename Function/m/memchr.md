# Function: <code>memchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memchr(const void * s, int c, size_t n)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981712,
      "name": "memchr",
      "external": true,
      "loc": "lib/string.c:863",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:state_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/base/power/sysfs.c:async_store",
        "drivers/base/power/sysfs.c:wake_store",
        "drivers/base/power/sysfs.c:control_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981712,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void * memchr(const void * s, int c, size_t n)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270896,
      "name": "memchr",
      "external": true,
      "loc": "lib/string.c:860",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/base/power/sysfs.c:async_store",
        "drivers/base/power/sysfs.c:wake_store",
        "drivers/base/power/sysfs.c:control_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270896,
      "name": "memchr",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * memchr(const void * s, int c, size_t n)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389664,
      "name": "memchr",
      "external": true,
      "loc": "lib/string.c:860",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/base/power/sysfs.c:async_store",
        "drivers/base/power/sysfs.c:wake_store",
        "drivers/base/power/sysfs.c:control_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389664,
      "name": "memchr",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579422624,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:353",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/base/power/sysfs.c:async_store",
        "drivers/base/power/sysfs.c:wake_store",
        "drivers/base/power/sysfs.c:control_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244144,
      "name": "memchr",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579450480,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:388",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/base/power/sysfs.c:async_store",
        "drivers/base/power/sysfs.c:wake_store",
        "drivers/base/power/sysfs.c:control_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795568,
      "name": "memchr",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579465420,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:389",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/dir.c:fuse_readdir",
        "fs/fuse/dir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173728,
      "name": "memchr",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579498988,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:396",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403648,
      "name": "memchr",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517194,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:403",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859648,
      "name": "memchr",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543274,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085440,
      "name": "memchr",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579574385,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:450",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:decode_state",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:decode_suspend_state",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_parse_cache",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083248,
      "name": "memchr",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579556001,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:491",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:decode_state",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:decode_suspend_state",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:prb_read",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_parse_cache",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232416,
      "name": "memchr",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579560624,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:238",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_parse_cache",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115280,
      "name": "memchr",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579633884,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:238",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563968,
      "name": "memchr",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579729577,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:_prb_read_valid",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718432,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * memchr(const const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579859411,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:662",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:decode_state",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595880768,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * memchr(const const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579909587,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:732",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:decode_state",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/md/dm-ioctl.c:populate_table",
        "drivers/cpufreq/amd-pstate.c:status_store",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596398000,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * memchr(const const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579948835,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/fortify-string.h:677",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:decode_state",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:record_print_text",
        "kernel/printk/printk_ringbuffer.c:copy_data",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "security/tomoyo/util.c:tomoyo_correct_path2",
        "lib/nlattr.c:validate_nla",
        "drivers/pinctrl/intel/pinctrl-baytrail.c:byt_init_irq_valid_mask",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch",
        "drivers/scsi/scsi.c:scsi_get_vpd_size",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/md/dm-ioctl.c:populate_table",
        "drivers/cpufreq/amd-pstate.c:status_store",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597293232,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490690952,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "lib/fdt_ro.c:fdt_stringlist_contains",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_get_string"
      ],
      "caller_func": [
        "lib/fdt_ro.c:fdt_stringlist_contains",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_get_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503798008,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 40
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
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224759392,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "arch/arm/kernel/armksyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "lib/nlattr.c:validate_nla",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "lib/fdt_ro.c:fdt_stringlist_contains",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_get_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236421760,
      "name": "memchr",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283516036,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir_cached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:parse_dirplusfile",
        "lib/nlattr.c:validate_nla",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "lib/fdt_ro.c:fdt_stringlist_contains",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_get_string"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282852084,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 0
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
void * memchr(const void * s, int c, size_t n)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760644,
      "name": "memchr",
      "external": true,
      "loc": "lib/string.c:997",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "lib/fdt_ro.c:fdt_stringlist_contains",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_path_offset_namelen",
        "lib/fdt_ro.c:fdt_get_string"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760644,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579516938,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687696,
      "name": "memchr",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579445738,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413488,
      "name": "memchr",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579516858,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131072,
      "name": "memchr",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr(const void * p, int c, __kernel_size_t size)
```

```json
{
  "name": "memchr",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579549818,
      "name": "memchr",
      "external": true,
      "loc": "include/linux/string.h:424",
      "file": "kernel/sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/main.c:state_store",
        "kernel/power/main.c:pm_test_store",
        "kernel/power/main.c:mem_sleep_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/printk/printk.c:msg_print_text",
        "fs/readdir.c:verify_dirent_name",
        "fs/fs_context.c:legacy_parse_param",
        "fs/fuse/readdir.c:fuse_readdir",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "fs/fuse/readdir.c:fuse_readdir_uncached",
        "lib/nlattr.c:validate_nla",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write",
        "drivers/spi/spi.c:driver_override_store",
        "drivers/usb/core/sysfs.c:level_store",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/cpufreq/intel_pstate.c:store_status",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse",
        "net/dns_resolver/dns_key.c:dns_resolver_preparse"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181456,
      "name": "memchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<b>Param added. </b>
<code>const void * p</code>
</li>
<li>
<b>Param added. </b>
<code>__kernel_size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * s</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t n</code>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void * p</code> ➡️ <code>const const void * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * s</code>
</li>
<li>
<b>Param added. </b>
<code>size_t n</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>__kernel_size_t size</code>
</li>
</ul>
</details>
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
