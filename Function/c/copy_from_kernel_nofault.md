# Function: <code>copy_from_kernel_nofault</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581302464,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:25",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:romchecksum",
        "arch/x86/kernel/probe_roms.c:romsignature",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state",
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302464,
      "name": "copy_from_kernel_nofault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071581303136,
      "name": "copy_from_kernel_nofault",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345840,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:25",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:romchecksum",
        "arch/x86/kernel/probe_roms.c:romsignature",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev-es.c:vc_decode_insn",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_support.c:kdb_task_state",
        "kernel/trace/bpf_trace.c:bpf_seq_printf",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/btf.c:btf_show_obj_safe",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345840,
      "name": "copy_from_kernel_nofault.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071581346192,
      "name": "copy_from_kernel_nofault",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581365024,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:25",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:romchecksum",
        "arch/x86/kernel/probe_roms.c:romsignature",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/trace/ftrace.c:print_ip_ins",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581365024,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581613408,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:25",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:romchecksum",
        "arch/x86/kernel/probe_roms.c:romsignature",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/debug/kdb/kdb_main.c:kdb_ps",
        "kernel/trace/ftrace.c:print_ip_ins",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "mm/debug.c:__dump_page",
        "fs/d_path.c:simple_dname",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613408,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581973952,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:23",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:romchecksum",
        "arch/x86/kernel/probe_roms.c:romsignature",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:recover_probed_instruction",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_decode_insn",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/btf.c:btf_parse",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/d_path.c:prepend_copy",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581973952,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582408656,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:23",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_decode_insn",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/btf.c:btf_parse",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/d_path.c:prepend_copy",
        "fs/proc/kcore.c:read_kcore",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408656,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582614640,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:24",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_d_path",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/btf.c:btf_parse",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/d_path.c:prepend_copy",
        "fs/proc/kcore.c:read_kcore_iter",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582614640,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582786160,
      "name": "copy_from_kernel_nofault",
      "external": true,
      "loc": "mm/maccess.c:24",
      "file": "mm/maccess.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/xen/enlighten_pv.c:set_aliased_prot",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/dumpstack.c:show_opcodes",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:probe_roms",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/probe_roms.c:find_oprom",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/ftrace.c:addr_from_call",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:create_trampoline",
        "arch/x86/kernel/ftrace.c:ftrace_verify_code",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:__recover_probed_insn",
        "arch/x86/kernel/kprobes/opt.c:__recover_optprobed_insn",
        "arch/x86/kernel/kgdb.c:kgdb_arch_set_breakpoint",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/mm/fault.c:show_ldttss",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "arch/x86/mm/fault.c:dump_pagetable",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/workqueue.c:print_worker_info",
        "kernel/kthread.c:kthread_probe_data",
        "kernel/debug/gdbstub.c:gdb_serial_stub",
        "kernel/debug/gdbstub.c:gdb_cmd_query",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:process_fetch_insn",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_eprobe.c:get_eprobe_size",
        "kernel/trace/trace_events_synth.c:trace_event_raw_event_synth",
        "kernel/trace/trace_events_synth.c:trace_string",
        "kernel/trace/bpf_trace.c:bpf_d_path",
        "kernel/trace/bpf_trace.c:bpf_probe_read_compat",
        "kernel/trace/bpf_trace.c:bpf_probe_read_kernel",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_kprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/trace/trace_fprobe.c:process_fetch_insn",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/verifier.c:resolve_pseudo_ldimm64",
        "kernel/bpf/verifier.c:check_core_relo",
        "kernel/bpf/verifier.c:check_btf_line",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/bpf_iter.c:bpf_iter_link_attach",
        "kernel/bpf/btf.c:btf_parse",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/inode.c:dump_mapping",
        "fs/d_path.c:prepend_copy",
        "fs/proc/kcore.c:read_kcore_iter",
        "drivers/char/mem.c:read_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582786160,
      "name": "copy_from_kernel_nofault",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int copy_from_kernel_nofault(void * dst, const void * src, size_t size)
```
</details>
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
