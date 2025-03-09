# Function: <code>hex_to_bin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583044816,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:28",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "fs/efivarfs/inode.c:efivarfs_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in4_pton",
        "net/core/utils.c:in6_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583044816,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583338235,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:28",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/uuid.c:__uuid_to_bin",
        "lib/uuid.c:__uuid_to_bin",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338144,
      "name": "hex_to_bin",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583463659,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:28",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/uuid.c:__uuid_to_bin",
        "lib/uuid.c:__uuid_to_bin",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463568,
      "name": "hex_to_bin",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583485920,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:28",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583485840,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583666960,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:29",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583666880,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583886341,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:29",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886240,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583886288,
      "name": "hex_to_bin",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583970549,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:29",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970448,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071583970496,
      "name": "hex_to_bin",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584151773,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151600,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071584151648,
      "name": "hex_to_bin",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584272888,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272688,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584683232,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_reg_set",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/firmware/efi/vars.c:validate_load_option",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681520,
      "name": "hex_to_bin",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584800912,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:26",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_reg_set",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/firmware/efi/vars.c:validate_load_option",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799184,
      "name": "hex_to_bin",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584845091,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:26",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/firmware/efi/vars.c:validate_load_option",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843376,
      "name": "hex_to_bin",
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585265011,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:26",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/firmware/efi/vars.c:validate_load_option",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263296,
      "name": "hex_to_bin",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(unsigned char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586109489,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:46",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/firmware/efi/vars.c:validate_load_option",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107584,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int hex_to_bin(unsigned char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587095089,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:46",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "fs/efivarfs/vars.c:validate_load_option",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093056,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int hex_to_bin(unsigned char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355169,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:46",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "fs/efivarfs/vars.c:validate_load_option",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:bitmap_parse",
        "lib/bitmap.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353168,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int hex_to_bin(unsigned char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587641489,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:46",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "fs/efivarfs/vars.c:validate_load_option",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap-str.c:bitmap_parse",
        "lib/bitmap-str.c:bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/net_utils.c:mac_pton",
        "lib/net_utils.c:mac_pton",
        "drivers/tty/vt/vt.c:do_con_trol",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639488,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496159256,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496159056,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336496159112,
      "name": "hex_to_bin",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229479860,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229479708,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3229479764,
      "name": "hex_to_bin",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290422860,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290422592,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 13835058055290422672,
      "name": "hex_to_bin",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275211472,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275211324,
      "name": "hex_to_bin.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446743936275211384,
      "name": "hex_to_bin",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584241624,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241424,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584176824,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/scsi/scsi_transport_fc.c:fc_parse_wwn",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176624,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584225384,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225184,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int hex_to_bin(char ch)
```

```json
{
  "name": "hex_to_bin",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584330216,
      "name": "hex_to_bin",
      "external": true,
      "loc": "lib/hexdump.c:25",
      "file": "lib/hexdump.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": [
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:kgdb_hex2long",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "kernel/debug/gdbstub.c:kgdb_hex2mem",
        "security/selinux/selinuxfs.c:sel_write_create",
        "security/selinux/selinuxfs.c:sel_write_create",
        "lib/bitmap.c:__bitmap_parse",
        "lib/string_helpers.c:string_unescape",
        "lib/string_helpers.c:string_unescape",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "drivers/nvdimm/core.c:nd_uuid_store",
        "net/core/utils.c:in6_pton",
        "net/core/utils.c:in4_pton"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330016,
      "name": "hex_to_bin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char ch</code> ➡️ <code>unsigned char ch</code>
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
