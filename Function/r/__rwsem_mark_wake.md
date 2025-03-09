# Function: <code>__rwsem_mark_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct rw_semaphore * __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698432,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:125",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698432,
      "name": "__rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579726013,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:124",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725568,
      "name": "__rwsem_mark_wake.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071579726112,
      "name": "__rwsem_mark_wake.constprop.3",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579721981,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:126",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721568,
      "name": "__rwsem_mark_wake.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071579722080,
      "name": "__rwsem_mark_wake.constprop.3",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579754685,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:127",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754272,
      "name": "__rwsem_mark_wake.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
    },
    {
      "addr": 18446744071579754784,
      "name": "__rwsem_mark_wake.constprop.4",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579789090,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:127",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed"
      ],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788688,
      "name": "__rwsem_mark_wake.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071579789184,
      "name": "__rwsem_mark_wake.constprop.8",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```

```json
{
  "name": "__rwsem_mark_wake",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835152,
      "name": "__rwsem_mark_wake",
      "external": false,
      "loc": "kernel/locking/rwsem-xadd.c:127",
      "file": "kernel/locking/rwsem-xadd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem-xadd.c:rwsem_downgrade_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_wake",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_write_failed",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed_killable",
        "kernel/locking/rwsem-xadd.c:rwsem_down_read_failed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835152,
      "name": "__rwsem_mark_wake",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
    }
  ]
}
```
</details>
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
struct rw_semaphore * __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
struct rw_semaphore * __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __rwsem_mark_wake(struct rw_semaphore * sem, enum rwsem_wake_type wake_type, struct wake_q_head * wake_q)
```
</details>
</li>
</ul>
