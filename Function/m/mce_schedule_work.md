# Function: <code>mce_schedule_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579125856,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:449",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125856,
      "name": "mce_schedule_work.part.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595176397,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:492",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579125936,
      "name": "mce_schedule_work.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595419662,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:517",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579133136,
      "name": "mce_schedule_work.part.18",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596339665,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:448",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579132256,
      "name": "mce_schedule_work.part.16",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602657898,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:457",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146640,
      "name": "mce_schedule_work.part.16",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602829222,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:454",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check",
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156976,
      "name": "mce_schedule_work.part.18",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604623193,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:452",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146464,
      "name": "mce_schedule_work.part.17",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604720372,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158672,
      "name": "mce_schedule_work.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604733496,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161168,
      "name": "mce_schedule_work.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_schedule_work()
```

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579181653,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:451",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181312,
      "name": "mce_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void mce_schedule_work()
```

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579178053,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:517",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177520,
      "name": "mce_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void mce_schedule_work()
```

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579184053,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:517",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183520,
      "name": "mce_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void mce_schedule_work()
```

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579218101,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:526",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217760,
      "name": "mce_schedule_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616980688,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:451",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627601400,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:451",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
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
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619355464,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:445",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
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
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621649480,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:476",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
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
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604659799,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161536,
      "name": "mce_schedule_work.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604627496,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093056,
      "name": "mce_schedule_work.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604737562,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579161088,
      "name": "mce_schedule_work.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_schedule_work",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604737608,
      "name": "mce_schedule_work",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mce/core.c:469",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_late_init",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579166224,
      "name": "mce_schedule_work.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mce_schedule_work()
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void mce_schedule_work()
```
</details>
</li>
</ul>
