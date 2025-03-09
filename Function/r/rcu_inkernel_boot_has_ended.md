# Function: <code>rcu_inkernel_boot_has_ended</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089232,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:216",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089232,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072432,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:204",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072432,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580073248,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:206",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580073248,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:206",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592140565,
      "name": "rcu_inkernel_boot_has_ended.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071580208976,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:206",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593911487,
      "name": "rcu_inkernel_boot_has_ended.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580366208,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:206",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595990242,
      "name": "rcu_inkernel_boot_has_ended.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580588000,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:244",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596508355,
      "name": "rcu_inkernel_boot_has_ended.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580661456,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool rcu_inkernel_boot_has_ended()
```

```json
{
  "name": "rcu_inkernel_boot_has_ended",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rcu_inkernel_boot_has_ended",
      "external": true,
      "loc": "kernel/rcu/update.c:245",
      "file": "kernel/rcu/update.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:check_cpu_stall",
        "kernel/rcu/tree.c:print_cpu_stall",
        "kernel/rcu/tree.c:print_other_cpu_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597406020,
      "name": "rcu_inkernel_boot_has_ended.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071580727168,
      "name": "rcu_inkernel_boot_has_ended",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool rcu_inkernel_boot_has_ended()
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
