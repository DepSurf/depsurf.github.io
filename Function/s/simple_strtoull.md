# Function: <code>simple_strtoull</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582983840,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:50",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/xen/xen-balloon.c:store_target_kb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582983840,
      "name": "simple_strtoull",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583273792,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:56",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/xen/xen-balloon.c:store_target_kb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583273792,
      "name": "simple_strtoull",
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583392544,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:56",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583392544,
      "name": "simple_strtoull",
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588248576,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:57",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248576,
      "name": "simple_strtoull",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588800128,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:59",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588800128,
      "name": "simple_strtoull",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178288,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:58",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "block/cfq-iosched.c:cfq_set_weight_on_dfl",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178288,
      "name": "simple_strtoull",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589408336,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:59",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589408336,
      "name": "simple_strtoull",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589864112,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589864112,
      "name": "simple_strtoull",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590089920,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089920,
      "name": "simple_strtoull",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585100277,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:64",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "lib/cmdline.c:memparse",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:scsi_scan",
        "drivers/scsi/scsi_sysfs.c:scsi_scan",
        "drivers/scsi/scsi_sysfs.c:scsi_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585087808,
      "name": "simple_strtoull",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585248776,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:64",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:scsi_scan",
        "drivers/scsi/scsi_sysfs.c:scsi_scan",
        "drivers/scsi/scsi_sysfs.c:scsi_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236912,
      "name": "simple_strtoull",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585124598,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:89",
      "file": "lib/vsprintf.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585124400,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585574080,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:90",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:target_kb_store",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585574080,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723136,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:94",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:target_kb_store",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723136,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595885904,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:95",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/page_alloc.c:cmdline_parse_movablecore",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:target_kb_store",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595885904,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596403280,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:95",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/mm_init.c:cmdline_parse_movablecore",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:target_kb_store",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596403280,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597298384,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:97",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "kernel/debug/kdb/kdb_main.c:kdb_rm",
        "mm/mm_init.c:cmdline_parse_movablecore",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/pnp/interface.c:resources_store",
        "drivers/pnp/interface.c:resources_store",
        "drivers/xen/xen-balloon.c:target_kb_store",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "drivers/scsi/scsi_sysfs.c:store_scan",
        "lib/cmdline.c:memparse",
        "lib/cmdline.c:get_option",
        "lib/cmdline.c:get_option"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597298384,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503868280,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503868280,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236494884,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236494884,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297728800,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtas-proc.c:parse_number",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297728800,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279763910,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279763910,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589692176,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589692176,
      "name": "simple_strtoull",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589417968,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417968,
      "name": "simple_strtoull",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590135552,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590135552,
      "name": "simple_strtoull",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long long unsigned int simple_strtoull(const char * cp, char * * endp, unsigned int base)
```

```json
{
  "name": "simple_strtoull",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590185936,
      "name": "simple_strtoull",
      "external": true,
      "loc": "lib/vsprintf.c:61",
      "file": "lib/vsprintf.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/e820.c:parse_memmap_opt",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "arch/x86/kernel/early_printk.c:early_serial_init",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "kernel/debug/kdb/kdb_main.c:kdbgetu64arg",
        "mm/page_alloc.c:cmdline_parse_core",
        "security/apparmor/procattr.c:aa_setprocattr_changehat",
        "drivers/xen/xen-balloon.c:store_target_kb",
        "drivers/tty/serial/serial_core.c:uart_parse_earlycon",
        "lib/cmdline.c:memparse",
        "lib/vsprintf.c:vsscanf",
        "lib/vsprintf.c:vsscanf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185936,
      "name": "simple_strtoull",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
