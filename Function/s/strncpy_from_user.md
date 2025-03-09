# Function: <code>strncpy_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583144976,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:99",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:SyS_delete_module",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583144976,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583439328,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:100",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:SyS_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439328,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 323
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565056,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:101",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:SyS_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565056,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583602592,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:101",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:SyS_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583602592,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583848688,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:102",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:SyS_prctl",
        "kernel/reboot.c:SYSC_reboot",
        "kernel/module.c:SyS_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583848688,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049104,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:102",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_uprobe_init",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:fetch_memory_string",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049104,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132064,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:102",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132064,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322384,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:103",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322384,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584457072,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584457072,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020576,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020576,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585169184,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585169184,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585049648,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585049648,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585493296,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585493296,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638192,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr_copy",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "io_uring/io_uring.c:__io_getxattr_prep",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638192,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587881600,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr_copy",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "io_uring/xattr.c:__io_getxattr_prep",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881600,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153408,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr_copy",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "io_uring/xattr.c:__io_getxattr_prep",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153408,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588443008,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:113",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__do_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_user_nofault",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr_copy",
        "security/keys/keyctl.c:keyctl_restrict_keyring",
        "security/keys/keyctl.c:keyctl_keyring_search",
        "security/keys/keyctl.c:__do_sys_request_key",
        "security/keys/keyctl.c:__do_sys_add_key",
        "io_uring/xattr.c:__io_getxattr_prep",
        "drivers/tty/vt/vt.c:con_font_op",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588443008,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496344184,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__arm64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__arm64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496344184,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229676996,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__se_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229676996,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290668464,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__se_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290668464,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275393080,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sys.c:__se_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__se_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275393080,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584425808,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584425808,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584361008,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584361008,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408720,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408720,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
long int strncpy_from_user(char * dst, const char * src, long int count)
```

```json
{
  "name": "strncpy_from_user",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584514784,
      "name": "strncpy_from_user",
      "external": true,
      "loc": "lib/strncpy_from_user.c:97",
      "file": "lib/strncpy_from_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/if.c:mtrr_write",
        "kernel/sys.c:__ia32_sys_prctl",
        "kernel/sys.c:__x64_sys_prctl",
        "kernel/reboot.c:__do_sys_reboot",
        "kernel/module.c:__ia32_sys_delete_module",
        "kernel/module.c:__x64_sys_delete_module",
        "kernel/auditsc.c:audit_log_execve_info",
        "kernel/trace/trace_event_perf.c:perf_kprobe_init",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/trace/trace_uprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/maccess.c:strncpy_from_unsafe_user",
        "fs/xattr.c:removexattr",
        "fs/xattr.c:getxattr",
        "fs/xattr.c:setxattr",
        "drivers/tty/vt/vt.c:con_font_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584514784,
      "name": "strncpy_from_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 333
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
