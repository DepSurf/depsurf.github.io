# Function: <code>set_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397528,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile",
        "arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579433094,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579798032,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580045901,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580486708,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size",
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580693405,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580757438,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581417628,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581448316,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581639169,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581680940,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836758,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581849326,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583161856,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587385996,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_sock_ioctl",
        "net/socket.c:kernel_sock_ioctl",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587723098,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588189147,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588374650,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588539308,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv6/exthdrs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_renew_options_kern",
        "net/ipv6/exthdrs.c:ipv6_renew_options_kern"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448310,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579831584,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580104194,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574033,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/trace/trace_kprobe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size",
        "kernel/trace/trace_kprobe.c:fetch_memory_string_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580810804,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580825423,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580893506,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581576716,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581606108,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802383,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842252,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582016015,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582030759,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583367344,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587693130,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588057559,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/compat.c:__compat_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588540445,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588732698,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579481782,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579878320,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580151671,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580877444,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892189,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968146,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581662476,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581691388,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581889388,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581930044,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582103967,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582118823,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486096,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587827226,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:compat_sock_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588233351,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_getsockopt",
        "net/compat.c:__compat_sys_setsockopt",
        "net/compat.c:__compat_sys_setsockopt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588738925,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588952730,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:30",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499813,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579913215,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580049718,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580197787,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580911261,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580973791,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989711,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063798,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581770620,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809503,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013888,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582070943,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190314,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582266209,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582280952,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582405175,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583672192,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588132618,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589171160,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589395939,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525928,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579963311,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580098822,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246010,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964109,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027919,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043695,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119766,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842844,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882095,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091856,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582148527,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582270616,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365599,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582380038,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582504135,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583779200,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588339290,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589395784,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589620515,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558121,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579701378,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_unuse_mm",
        "kernel/kthread.c:kthread_use_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580161358,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147351,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223083,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303819,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strnlen_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:strncpy_from_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_to_user_nofault",
        "mm/maccess.c:copy_from_user_nofault",
        "mm/maccess.c:copy_from_user_nofault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582063627,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_read",
        "fs/read_write.c:__kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582115216,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:begin_new_exec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582326044,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589196889,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void set_fs(mm_segment_t fs)
```

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490215360,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace",
        "arch/arm64/kernel/ptrace.c:compat_arch_ptrace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336490668744,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491472920,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:flush_module_icache",
        "kernel/module.c:flush_module_icache",
        "kernel/module.c:flush_module_icache",
        "kernel/module.c:flush_module_icache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492310696,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492352496,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492399148,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492490636,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493307784,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493357944,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493627988,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493697896,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493850780,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493961524,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493976032,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494129388,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495581660,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501476924,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "drivers/firmware/arm_sdei.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_sdei.c:sdei_event_handler",
        "drivers/firmware/arm_sdei.c:sdei_event_handler",
        "drivers/firmware/arm_sdei.c:sdei_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501833012,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__arm64_sys_setsockopt",
        "net/socket.c:__arm64_sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": [
        "net/socket.c:__arm64_sys_setsockopt"
      ]
    },
    {
      "addr": 18446603336503049380,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503301752,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm64/include/asm/uaccess.h:28",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501831920,
      "name": "set_fs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224434104,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "arch/arm/kernel/traps.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:die",
        "arch/arm/kernel/traps.c:die",
        "arch/arm/kernel/traps.c:dump_mem",
        "arch/arm/kernel/traps.c:dump_mem"
      ],
      "caller_func": []
    },
    {
      "addr": 3224740792,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 3225470204,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 3226198096,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 3226266480,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 3226284640,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 3226362048,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3226910624,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3226946684,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 3227167496,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3227226468,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 3227344004,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 3227422624,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 3227426152,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/binfmt_elf_fdpic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump",
        "fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 3227579784,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 3228943208,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3234610332,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 3235729456,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 3235970216,
      "name": "set_fs",
      "external": false,
      "loc": "arch/arm/include/asm/uaccess.h:65",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283491044,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284444124,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285549808,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285581764,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample_ustack",
        "kernel/events/core.c:perf_output_sample_ustack"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285661288,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285776272,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286848476,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286903584,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287218040,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287299792,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287467852,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287603132,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287618516,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287807836,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289679608,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295231088,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296743652,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297056316,
      "name": "set_fs",
      "external": false,
      "loc": "arch/powerpc/include/asm/uaccess.h:34",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271341974,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "arch/riscv/kernel/process.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/riscv/kernel/process.c:start_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271407990,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271932690,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272436196,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272492932,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272506792,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272552624,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273049464,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273083452,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:__do_execve_file",
        "fs/exec.c:__do_execve_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273267570,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273313790,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273415048,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273487570,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273610864,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274747748,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278175026,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:__se_sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279106680,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279319486,
      "name": "set_fs",
      "external": false,
      "loc": "arch/riscv/include/asm/uaccess.h:41",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499592,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579932047,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068022,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580214810,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932909,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996767,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012543,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088614,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811580,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850831,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060592,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117263,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239352,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582334335,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582348774,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582472871,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583747936,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587946074,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589001064,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224883,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579428472,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579870319,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580012838,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580162250,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580878973,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942959,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958671,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035798,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749244,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581788495,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581998144,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054703,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582177096,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582272063,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582286486,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582410103,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583684992,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587659178,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588724120,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588949875,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499512,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579923583,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580059094,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580206282,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580924157,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580987967,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003743,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581079814,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581802892,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842143,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582051872,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107743,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229832,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582324815,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582339254,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463351,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583731712,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588277850,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589437448,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589661747,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_fs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579532136,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579969599,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/power/user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl",
        "kernel/power/user.c:snapshot_compat_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109926,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/stacktrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/stacktrace.c:stack_trace_save_user",
        "kernel/stacktrace.c:stack_trace_save_user"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580258736,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/module.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/module.c:load_module",
        "kernel/module.c:load_module"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580984493,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl",
        "kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sysctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048911,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_output_sample",
        "kernel/events/core.c:perf_output_sample"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064943,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "kernel/events/callchain.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/callchain.c:get_perf_callchain",
        "kernel/events/callchain.c:get_perf_callchain"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581141702,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "mm/maccess.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strnlen_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:strncpy_from_unsafe",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_user_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_kernel_write",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_user_read",
        "mm/maccess.c:__probe_kernel_read",
        "mm/maccess.c:__probe_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581872108,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/read_write.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:__kernel_write",
        "fs/read_write.c:kernel_read",
        "fs/read_write.c:kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911727,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/exec.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/exec.c:copy_strings_kernel",
        "fs/exec.c:copy_strings_kernel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582123552,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/splice.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/splice.c:default_file_splice_read",
        "fs/splice.c:default_file_splice_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582182239,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:ioctl_by_bdev",
        "fs/block_dev.c:ioctl_by_bdev"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582306472,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_wq_submit_work",
        "fs/io_uring.c:io_sq_wq_submit_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582404079,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump",
        "fs/binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582418582,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/compat_binfmt_elf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump",
        "fs/compat_binfmt_elf.c:elf_core_dump"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582546119,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583832592,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "security/integrity/iint.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/integrity/iint.c:integrity_kernel_read",
        "security/integrity/iint.c:integrity_kernel_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413002,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/socket.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_setsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:kernel_getsockopt",
        "net/socket.c:routing_ioctl",
        "net/socket.c:routing_ioctl",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:__sys_setsockopt",
        "net/socket.c:kernel_recvmsg",
        "net/socket.c:kernel_recvmsg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589482040,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv4/ipmr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_new_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel",
        "net/ipv4/ipmr.c:ipmr_del_tunnel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589710691,
      "name": "set_fs",
      "external": false,
      "loc": "arch/x86/include/asm/uaccess.h:29",
      "file": "net/ipv6/addrconf.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/addrconf.c:addrconf_set_dstaddr",
        "net/ipv6/addrconf.c:addrconf_set_dstaddr"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void set_fs(mm_segment_t fs)
```
</details>
</li>
</ul>
