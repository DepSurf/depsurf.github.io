# Function: <code>check_and_switch_context</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void check_and_switch_context(struct mm_struct * mm, unsigned int cpu)
```

```json
{
  "name": "check_and_switch_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490351160,
      "name": "check_and_switch_context",
      "external": true,
      "loc": "arch/arm64/mm/context.c:183",
      "file": "arch/arm64/mm/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:__schedule",
        "mm/mmu_context.c:use_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490351160,
      "name": "check_and_switch_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1476
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
void check_and_switch_context(struct mm_struct * mm, struct task_struct * tsk)
```

```json
{
  "name": "check_and_switch_context",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224511072,
      "name": "check_and_switch_context",
      "external": true,
      "loc": "arch/arm/mm/context.c:237",
      "file": "arch/arm/mm/context.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:idle_task_exit",
        "kernel/sched/core.c:__schedule",
        "mm/mmu_context.c:use_mm",
        "drivers/firmware/efi/arm-runtime.c:efi_virtmap_unload",
        "drivers/firmware/efi/arm-runtime.c:efi_virtmap_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224511072,
      "name": "check_and_switch_context",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1316
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void check_and_switch_context(struct mm_struct * mm, unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void check_and_switch_context(struct mm_struct * mm, struct task_struct * tsk)
```
</details>
</li>
</ul>
