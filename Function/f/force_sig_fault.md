# Function: <code>force_sig_fault</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int force_sig_fault(int sig, int code, void * addr, struct task_struct * t)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579500240,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1486",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500240,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int force_sig_fault(int sig, int code, void * addr, struct task_struct * t)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579533888,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1572",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533888,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559856,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1674",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559856,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579585984,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579585984,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579621968,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1675",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579621968,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602272,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1676",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:write_ok_or_segv",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602272,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579607888,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1678",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579607888,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579683760,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1721",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683760,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778800,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1722",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778800,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911504,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1723",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911504,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961296,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1729",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961296,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580000544,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1729",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall",
        "arch/x86/kernel/traps.c:handle_xfd_event",
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/cpu/intel.c:handle_bus_lock",
        "arch/x86/kernel/cpu/intel.c:handle_guest_split_lock",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev.c:user_exc_vmm_communication",
        "arch/x86/kernel/cet.c:do_user_cp_fault",
        "arch/x86/mm/fault.c:do_user_addr_fault",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:kernelmode_fixup_or_oops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580000544,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490749776,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/traps.c:bad_el0_sync"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490749776,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224799048,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:break_trap",
        "arch/arm/mm/alignment.c:do_alignment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224799048,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283574832,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/process.c:do_break",
        "arch/powerpc/kernel/traps.c:_exception",
        "arch/powerpc/kernel/traps.c:_exception",
        "arch/powerpc/kernel/traps.c:user_single_step_report",
        "arch/powerpc/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283574832,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271452576,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/riscv/kernel/traps.c:do_trap_break",
        "arch/riscv/kernel/traps.c:do_trap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271452576,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579562288,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562288,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490944,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490944,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579559568,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559568,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int force_sig_fault(int sig, int code, void * addr)
```

```json
{
  "name": "force_sig_fault",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579592960,
      "name": "force_sig_fault",
      "external": true,
      "loc": "kernel/signal.c:1679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:math_error",
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/kernel/ptrace.c:user_single_step_report",
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/mm/fault.c:mm_fault_error",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592960,
      "name": "force_sig_fault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int force_sig_fault(int sig, int code, void * addr, struct task_struct * t)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * t</code>
</li>
</ul>
</details>
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
