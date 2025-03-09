# Function: <code>xmon_printf</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void xmon_printf(const char * format, void (anon))
```

```json
{
  "name": "xmon_printf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283285472,
      "name": "xmon_printf",
      "external": true,
      "loc": "arch/powerpc/xmon/nonstdio.c:167",
      "file": "arch/powerpc/xmon/nonstdio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_get_irq_config",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/sysdev/xive/common.c:xmon_xive_do_dump",
        "arch/powerpc/xmon/xmon.c:dump_segments",
        "arch/powerpc/xmon/xmon.c:dump_segments",
        "arch/powerpc/xmon/xmon.c:dump_segments",
        "arch/powerpc/xmon/xmon.c:dump_segments",
        "arch/powerpc/xmon/xmon.c:xmon_print_symbol",
        "arch/powerpc/xmon/xmon.c:xmon_print_symbol",
        "arch/powerpc/xmon/xmon.c:xmon_print_symbol",
        "arch/powerpc/xmon/xmon.c:xmon_print_symbol",
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:symbol_lookup",
        "arch/powerpc/xmon/xmon.c:scanhex",
        "arch/powerpc/xmon/xmon.c:scanhex",
        "arch/powerpc/xmon/xmon.c:scanhex",
        "arch/powerpc/xmon/xmon.c:proccall",
        "arch/powerpc/xmon/xmon.c:proccall",
        "arch/powerpc/xmon/xmon.c:show_tasks",
        "arch/powerpc/xmon/xmon.c:show_tasks",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:show_pte",
        "arch/powerpc/xmon/xmon.c:format_pte",
        "arch/powerpc/xmon/xmon.c:format_pte",
        "arch/powerpc/xmon/xmon.c:format_pte",
        "arch/powerpc/xmon/xmon.c:show_task",
        "arch/powerpc/xmon/xmon.c:dump_opal_msglog",
        "arch/powerpc/xmon/xmon.c:dump_opal_msglog",
        "arch/powerpc/xmon/xmon.c:dump_opal_msglog",
        "arch/powerpc/xmon/xmon.c:dump_opal_msglog",
        "arch/powerpc/xmon/xmon.c:dump_log_buf",
        "arch/powerpc/xmon/xmon.c:dump_log_buf",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump",
        "arch/powerpc/xmon/xmon.c:dump_one_xive",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:dump_one_paca",
        "arch/powerpc/xmon/xmon.c:memex",
        "arch/powerpc/xmon/xmon.c:memex",
        "arch/powerpc/xmon/xmon.c:memex",
        "arch/powerpc/xmon/xmon.c:memex",
        "arch/powerpc/xmon/xmon.c:memex",
        "arch/powerpc/xmon/xmon.c:mwrite",
        "arch/powerpc/xmon/xmon.c:mwrite",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:super_regs",
        "arch/powerpc/xmon/xmon.c:dump_one_spr",
        "arch/powerpc/xmon/xmon.c:dump_one_spr",
        "arch/powerpc/xmon/xmon.c:dump_one_spr",
        "arch/powerpc/xmon/xmon.c:write_spr",
        "arch/powerpc/xmon/xmon.c:write_spr",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:prregs",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:excprint",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:xmon_show_stack",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:bpt_cmds",
        "arch/powerpc/xmon/xmon.c:check_bp_loc",
        "arch/powerpc/xmon/xmon.c:check_bp_loc",
        "arch/powerpc/xmon/xmon.c:check_bp_loc",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:cmds",
        "arch/powerpc/xmon/xmon.c:show_uptime",
        "arch/powerpc/xmon/xmon.c:remove_bpts",
        "arch/powerpc/xmon/xmon.c:new_breakpoint",
        "arch/powerpc/xmon/xmon.c:xmon_irq",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_core",
        "arch/powerpc/xmon/xmon.c:xmon_is_locked_down",
        "arch/powerpc/xmon/xmon.c:xmon_is_locked_down",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc",
        "arch/powerpc/xmon/ppc-dis.c:print_insn_powerpc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283285472,
      "name": "xmon_printf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void xmon_printf(const char * format, void (anon))
```
</details>
</li>
</ul>
