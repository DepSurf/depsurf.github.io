# Function: <code>print_hex_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583046304,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:242",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:free_debug_processing",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583046304,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583339648,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:242",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583339648,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583465072,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:242",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583465072,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487360,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:242",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487360,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583668400,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:243",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583668400,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:243",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "arch/x86/pci/early.c:early_dump_pci_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886427,
      "name": "print_hex_dump.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071583885968,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:243",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583970635,
      "name": "print_hex_dump.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071583970176,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584151815,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584151312,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584274433,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584274160,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:print_section",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_print_fw_err",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584683275,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584682816,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:240",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:print_section",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper.c:cper_print_fw_err",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591378896,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584800496,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:240",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:print_section",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591321167,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584844672,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:240",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:print_section",
        "fs/ext4/super.c:ext4_destroy_inode",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324928,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071585264592,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:261",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:print_section",
        "fs/ext4/super.c:ext4_destroy_inode",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594129417,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071586109072,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587094592,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:261",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587094592,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587354672,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:261",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "fs/ext4/super.c:ext4_destroy_inode",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587354672,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587640992,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:261",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:check_physptr",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "fs/ext4/super.c:ext4_destroy_inode",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/gpu/drm/drm_edid.c:edid_block_dump",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/cper_cxl.c:cper_print_prot_err",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/apple-properties.c:unmarshal_key_value_pairs",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587640992,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496158680,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/cper-arm.c:cper_print_proc_arm",
        "drivers/firmware/efi/cper-arm.c:cper_print_proc_arm",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496158680,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229479352,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229479352,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290422048,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/net/bpf_jit_comp64.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "security/integrity/ima/ima_kexec.c:ima_dump_measurement_list",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290422048,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275211036,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/ipv4/route.c:ip_handle_martian_source"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275211036,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243169,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584242896,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/acpi/nfit/core.c:acpi_nfit_ctl",
        "drivers/acpi/nfit/core.c:acpi_nfit_ctl",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/hv/channel_mgmt.c:vmbus_onmessage",
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "drivers/hv/channel_mgmt.c:vmbus_onoffer",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178369,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584178096,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226929,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584226656,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void print_hex_dump(const char * level, const char * prefix_str, int prefix_type, int rowsize, int groupsize, const void * buf, size_t len, bool ascii)
```

```json
{
  "name": "print_hex_dump",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_hex_dump",
      "external": true,
      "loc": "lib/hexdump.c:239",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/mpparse.c:smp_dump_mptable",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/slub.c:free_debug_processing",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "mm/slub.c:print_trailer",
        "drivers/pci/probe.c:early_dump_pci_device",
        "drivers/ata/libata-core.c:ata_dev_read_id",
        "drivers/net/tun.c:tun_do_read",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/usb/core/devio.c:snoop_urb_data",
        "drivers/firmware/efi/cper.c:cper_estatus_print_section",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:map_properties",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/apple-properties.c:unmarshal_devices",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump",
        "net/core/skbuff.c:skb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331761,
      "name": "print_hex_dump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    },
    {
      "addr": 18446744071584331488,
      "name": "print_hex_dump",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
