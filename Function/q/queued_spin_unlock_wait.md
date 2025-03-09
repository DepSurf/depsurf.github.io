# Function: <code>queued_spin_unlock_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queued_spin_unlock_wait",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579384196,
      "name": "queued_spin_unlock_wait",
      "external": false,
      "loc": "include/asm-generic/qspinlock.h:108",
      "file": "kernel/exit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579494698,
      "name": "queued_spin_unlock_wait",
      "external": false,
      "loc": "include/asm-generic/qspinlock.h:108",
      "file": "kernel/task_work.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/task_work.c:task_work_run"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579646945,
      "name": "queued_spin_unlock_wait",
      "external": false,
      "loc": "include/asm-generic/qspinlock.h:108",
      "file": "kernel/sched/completion.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582150157,
      "name": "queued_spin_unlock_wait",
      "external": false,
      "loc": "include/asm-generic/qspinlock.h:108",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:exit_sem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584959466,
      "name": "queued_spin_unlock_wait",
      "external": false,
      "loc": "include/asm-generic/qspinlock.h:108",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void queued_spin_unlock_wait(struct qspinlock * lock)
```

```json
{
  "name": "queued_spin_unlock_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579693216,
      "name": "queued_spin_unlock_wait",
      "external": true,
      "loc": "kernel/locking/qspinlock.c:360",
      "file": "kernel/locking/qspinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/exit.c:do_exit",
        "kernel/task_work.c:task_work_run",
        "kernel/sched/completion.c:completion_done",
        "ipc/sem.c:exit_sem",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693216,
      "name": "queued_spin_unlock_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void queued_spin_unlock_wait(struct qspinlock * lock)
```

```json
{
  "name": "queued_spin_unlock_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579720336,
      "name": "queued_spin_unlock_wait",
      "external": true,
      "loc": "kernel/locking/qspinlock.c:360",
      "file": "kernel/locking/qspinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/task_work.c:task_work_run",
        "kernel/sched/core.c:do_task_dead",
        "kernel/sched/completion.c:completion_done",
        "ipc/sem.c:exit_sem",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579720336,
      "name": "queued_spin_unlock_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void queued_spin_unlock_wait(struct qspinlock * lock)
```

```json
{
  "name": "queued_spin_unlock_wait",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716112,
      "name": "queued_spin_unlock_wait",
      "external": true,
      "loc": "kernel/locking/qspinlock.c:361",
      "file": "kernel/locking/qspinlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/exit.c:do_exit",
        "kernel/task_work.c:task_work_run",
        "kernel/sched/core.c:do_task_dead",
        "kernel/sched/completion.c:completion_done",
        "ipc/sem.c:exit_sem",
        "drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716112,
      "name": "queued_spin_unlock_wait",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void queued_spin_unlock_wait(struct qspinlock * lock)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void queued_spin_unlock_wait(struct qspinlock * lock)
```
</details>
</li>
</ul>
