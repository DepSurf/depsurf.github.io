# Function: <code>__smp_call_single_queue</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580283803,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:136",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580286016,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580267323,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:257",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580269536,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580273191,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:469",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274176,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425183,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:469",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580426432,
      "name": "__smp_call_single_queue",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648190,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:472",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580649568,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580915214,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:471",
      "file": "kernel/smp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/smp.c:generic_exec_single"
      ],
      "caller_func": [
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916752,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002400,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:334",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002400,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
```

```json
{
  "name": "__smp_call_single_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581098560,
      "name": "__smp_call_single_queue",
      "external": true,
      "loc": "kernel/smp.c:349",
      "file": "kernel/smp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/smp.c:generic_exec_single",
        "kernel/irq_work.c:irq_work_queue_on"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581098560,
      "name": "__smp_call_single_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 382
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
void __smp_call_single_queue(int cpu, struct llist_node * node)
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
