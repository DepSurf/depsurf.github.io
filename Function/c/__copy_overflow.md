# Function: <code>__copy_overflow</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count)
```

```json
{
  "name": "__copy_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973872,
      "name": "__copy_overflow",
      "external": true,
      "loc": "mm/maccess.c:220",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:tdx_get_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_get_syscall_info",
        "kernel/ptrace.c:ptrace_readdata",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/sys.c:override_release",
        "kernel/printk/printk.c:syslog_print_all",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "drivers/pci/vgaarb.c:vga_arb_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/scsi/sg.c:sg_write",
        "net/core/sock.c:sock_getsockopt",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run",
        "net/ethtool/ioctl.c:ethtool_get_any_eeprom",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973872,
      "name": "__copy_overflow",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count)
```

```json
{
  "name": "__copy_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408544,
      "name": "__copy_overflow",
      "external": true,
      "loc": "mm/maccess.c:220",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_get_syscall_info",
        "kernel/ptrace.c:ptrace_readdata",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/sys.c:override_release",
        "kernel/printk/printk.c:syslog_print_all",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "io_uring/net.c:io_recvmsg",
        "drivers/pci/vgaarb.c:vga_arb_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/scsi/sg.c:sg_write",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run",
        "net/ethtool/ioctl.c:ethtool_get_any_eeprom",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408544,
      "name": "__copy_overflow",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count)
```

```json
{
  "name": "__copy_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614528,
      "name": "__copy_overflow",
      "external": true,
      "loc": "mm/maccess.c:226",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_get_syscall_info",
        "kernel/ptrace.c:ptrace_readdata",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/sys.c:override_release",
        "kernel/printk/printk.c:syslog_print_all",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "io_uring/net.c:io_recvmsg",
        "drivers/pci/vgaarb.c:vga_arb_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/scsi/sg.c:sg_write",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run",
        "net/ethtool/ioctl.c:ethtool_get_any_eeprom",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614528,
      "name": "__copy_overflow",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __copy_overflow(int size, long unsigned int count)
```

```json
{
  "name": "__copy_overflow",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786048,
      "name": "__copy_overflow",
      "external": true,
      "loc": "mm/maccess.c:226",
      "file": "mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "kernel/capability.c:__do_sys_capget",
        "kernel/ptrace.c:ptrace_get_syscall_info",
        "kernel/ptrace.c:ptrace_readdata",
        "kernel/signal.c:__ia32_compat_sys_rt_sigpending",
        "kernel/sys.c:override_release",
        "kernel/printk/printk.c:syslog_print_all",
        "fs/ecryptfs/miscdev.c:ecryptfs_miscdev_read",
        "io_uring/net.c:io_recvmsg",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_watch_read",
        "drivers/pci/vgaarb.c:vga_arb_read",
        "drivers/tty/tty_io.c:tty_read",
        "drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl",
        "drivers/tty/vt/keyboard.c:vt_do_diacrit",
        "drivers/scsi/sg.c:sg_write",
        "drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_read",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/core/sock.c:sk_getsockopt",
        "net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run",
        "net/ethtool/ioctl.c:ethtool_get_any_eeprom",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/ip_sockglue.c:do_ip_getsockopt",
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/ipmr.c:ip_mroute_getsockopt",
        "net/ipv4/tcp_ao.c:tcp_ao_get_repair",
        "net/ipv4/tcp_ao.c:tcp_ao_get_sock_info",
        "net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_getsockopt",
        "net/ipv6/ip6mr.c:ip6_mroute_getsockopt",
        "net/packet/af_packet.c:packet_recvmsg",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_full_info",
        "net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs",
        "net/mptcp/sockopt.c:mptcp_getsockopt_tcpinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786048,
      "name": "__copy_overflow",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __copy_overflow(int size, long unsigned int count)
```
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
