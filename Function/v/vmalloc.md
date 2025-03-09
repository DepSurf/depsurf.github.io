# Function: <code>vmalloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580742448,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1742",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/kexec_file.c:copy_file_from_fd",
        "kernel/cgroup.c:pidlist_array_load",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/frame_vector.c:frame_vector_create",
        "fs/file.c:alloc_fdmem",
        "fs/seq_file.c:seq_buf_alloc",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "fs/jbd2/journal.c:jbd2_alloc",
        "ipc/util.c:ipc_alloc",
        "security/keys/keyctl.c:SyS_add_key",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "crypto/lzo.c:lzo_init",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/iov_iter.c:get_pages_array",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/generic.c:agp_alloc_page_array",
        "drivers/base/firmware_class.c:_request_firmware",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580742448,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862192,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1763",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/hashtab.c:htab_map_alloc",
        "mm/frame_vector.c:frame_vector_create",
        "fs/seq_file.c:seq_buf_alloc",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "ipc/util.c:ipc_alloc",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:SyS_add_key",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "crypto/lzo.c:lzo_init",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/iov_iter.c:get_pages_array",
        "lib/rhashtable.c:bucket_table_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/generic.c:agp_alloc_page_array",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862192,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932496,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1776",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup.c:cgroup_pidlist_start",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "kernel/bpf/verifier.c:bpf_check",
        "mm/frame_vector.c:frame_vector_create",
        "fs/select.c:core_sys_select",
        "fs/seq_file.c:seq_buf_alloc",
        "fs/xattr.c:listxattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "ipc/util.c:ipc_alloc",
        "security/keys/keyctl.c:keyctl_instantiate_key_common",
        "security/keys/keyctl.c:SyS_add_key",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/apparmor/lib.c:__aa_kvmalloc",
        "crypto/lzo.c:lzo_alloc_ctx",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/iov_iter.c:get_pages_array",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/erst.c:erst_get_record_id_next",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/char/agp/generic.c:agp_alloc_page_array",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/nvdimm/dimm_devs.c:nvdimm_init_config_data",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932496,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580976176,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1846",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "kernel/bpf/verifier.c:bpf_check",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580976176,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078752,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1838",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/tty/n_tty.c:n_tty_open",
        "drivers/base/firmware_class.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078752,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581218192,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1825",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581218192,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581301376,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:1831",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/base/firmware_loader/fallback.c:firmware_data_write",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581301376,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581378624,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2582",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/cgroup/cgroup-v1.c:pidlist_array_load",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/clocksource/hyperv_timer.c:hv_init_clocksource",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581378624,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581439824,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581439824,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648608,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2619",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:start_bunzip",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648608,
      "name": "vmalloc",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581694992,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2652",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:start_bunzip",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unzstd.c:decompress_single",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_do_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581694992,
      "name": "vmalloc",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716848,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2999",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716848,
      "name": "vmalloc",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581989088,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3105",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581989088,
      "name": "vmalloc",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582413328,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3262",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582413328,
      "name": "vmalloc",
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582920960,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3324",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582920960,
      "name": "vmalloc",
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583137120,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3417",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/module/decompress.c:module_zstd_decompress",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583137120,
      "name": "vmalloc",
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583320240,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:3417",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/cpu/microcode/amd.c:install_equiv_cpu_table",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/kernel_read_file.c:kernel_read_file",
        "fs/configfs/file.c:configfs_bin_write_iter",
        "fs/configfs/file.c:configfs_bin_read_iter",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "fs/pstore/platform.c:pstore_register",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/selinux/ss/services.c:security_read_state_kernel",
        "lib/xz/xz_dec_lzma2.c:xz_dec_microlzma_alloc",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_fq",
        "drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/dma-buf/heaps/system_heap.c:system_heap_vmap",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_using_sections",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_coredump.c:rproc_coredump",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320240,
      "name": "vmalloc",
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492845512,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/machine_kexec_file.c:load_other_segments",
        "virt/kvm/kvm_main.c:kvm_vm_ioctl",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492845512,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226651132,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/binfmt_flat.c:load_flat_file",
        "fs/binfmt_flat.c:load_flat_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources",
        "drivers/iommu/tegra-gart.c:tegra_gart_probe",
        "drivers/mtd/mtdblock.c:mtdblock_writesect",
        "drivers/mtd/nand/raw/nand_bbt.c:nand_create_bbt",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226651132,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286233216,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan_init",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "security/integrity/ima/ima_kexec.c:ima_dump_measurement_list",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286233216,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272795280,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/binfmt_flat.c:load_flat_file",
        "fs/binfmt_flat.c:load_flat_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272795280,
      "name": "vmalloc",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581408672,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408672,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581351744,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581351744,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581399872,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581399872,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void * vmalloc(long unsigned int size)
```

```json
{
  "name": "vmalloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581464416,
      "name": "vmalloc",
      "external": true,
      "loc": "mm/vmalloc.c:2590",
      "file": "mm/vmalloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode",
        "arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/tracing_map.c:tracing_map_sort_entries",
        "kernel/bpf/core.c:bpf_prog_calc_tag",
        "fs/exec.c:kernel_read_file",
        "fs/configfs/file.c:configfs_write_bin_file",
        "fs/configfs/file.c:configfs_read_bin_file",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lz4_wrapper.c:lz4_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/lzo_wrapper.c:lzo_init",
        "fs/squashfs/zlib_wrapper.c:zlib_init",
        "fs/squashfs/zstd_wrapper.c:zstd_init",
        "security/selinux/selinuxfs.c:sel_write_load",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_reset",
        "lib/xz/xz_dec_lzma2.c:xz_dec_lzma2_create",
        "drivers/acpi/apei/ghes.c:ghes_estatus_pool_init",
        "drivers/nvdimm/bus.c:__nd_ioctl",
        "drivers/usb/host/ehci-hcd.c:debug_output",
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "net/core/sysctl_net_core.c:rps_sock_flow_sysctl",
        "net/core/net-sysfs.c:store_rps_dev_flow_table_cnt",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "lib/decompress_bunzip2.c:bunzip2",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlz4.c:unlz4",
        "lib/decompress_unlzma.c:unlzma",
        "lib/decompress_unlzma.c:unlzma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581464416,
      "name": "vmalloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
