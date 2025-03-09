# Function: <code>sync_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579065590,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:574",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early",
        "arch/x86/kernel/alternative.c:apply_alternatives",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115535,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:574",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579128470,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:574",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161169,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:574",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216145,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:574",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061990,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:585",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke_early",
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579115491,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:585",
      "file": "arch/x86/kernel/cpu/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel.c:early_init_intel"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579129379,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:585",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579161211,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:585",
      "file": "arch/x86/kernel/cpu/microcode/intel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel",
        "arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_early",
        "arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579216257,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:585",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579061241,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579136562,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579228052,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:638",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053097,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579134688,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579225748,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:649",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062329,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:671",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579149648,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:671",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579242420,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:671",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579066805,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:687",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579159562,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:687",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579254992,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:687",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579612775,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:687",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579071397,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:682",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579150507,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:682",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579278720,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:682",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579651085,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:682",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579080277,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579163190,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579293232,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579674631,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082277,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165658,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579298864,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579713132,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579093653,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:695",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591159180,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:695",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579759072,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:695",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core()
```

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579094853,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579182122,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe"
      ]
    },
    {
      "addr": 18446744071579724551,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579929298,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172576,
      "name": "sync_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core()
```

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579101157,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579188442,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe"
      ]
    },
    {
      "addr": 18446744071579731934,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579937209,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579179600,
      "name": "sync_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core()
```

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125077,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579223306,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe"
      ]
    },
    {
      "addr": 18446744071579811950,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580062025,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/membarrier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/membarrier.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213792,
      "name": "sync_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void sync_core()
```

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579158789,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579274244,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe"
      ]
    },
    {
      "addr": 18446744071579919644,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580139671,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264992,
      "name": "sync_core",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579208805,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579330044,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580074460,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580314807,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579215157,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579338855,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580127964,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381479,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579244197,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early",
        "arch/x86/kernel/alternative.c:optimize_nops_inplace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579368727,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:kill_me_maybe",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580172508,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:sync_core_before_usermode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438679,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/sync_core.h:58",
      "file": "kernel/sched/build_utility.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/build_utility.c:ipi_sync_core"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082629,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579166010,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579294672,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579689308,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579016421,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579097610,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579230192,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579617835,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579082213,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579165578,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579295872,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579686284,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
  "name": "sync_core",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579086309,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:do_sync_core",
        "arch/x86/kernel/alternative.c:text_poke_early"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579170762,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579304704,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "arch/x86/kernel/ftrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/ftrace.c:do_sync_core",
        "arch/x86/kernel/ftrace.c:ftrace_modify_code_direct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579715801,
      "name": "sync_core",
      "external": false,
      "loc": "arch/x86/include/asm/processor.h:672",
      "file": "kernel/sched/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/core.c:finish_task_switch"
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
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void sync_core()
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void sync_core()
```
</details>
</li>
</ul>
