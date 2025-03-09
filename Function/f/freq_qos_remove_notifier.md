# Function: <code>freq_qos_remove_notifier</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579919776,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919776,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579964160,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579964160,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579952256,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579952256,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955056,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955056,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084240,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084240,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220432,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220432,
      "name": "freq_qos_remove_notifier",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580411056,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:648",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580411056,
      "name": "freq_qos_remove_notifier",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580479760,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:653",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580479760,
      "name": "freq_qos_remove_notifier",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580539584,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:658",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/base/power/qos.c:dev_pm_qos_remove_notifier",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580539584,
      "name": "freq_qos_remove_notifier",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491125872,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491125872,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225124992,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225124992,
      "name": "freq_qos_remove_notifier",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284016624,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284016624,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271698304,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271698304,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579891888,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891888,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579826848,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826848,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880048,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880048,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```

```json
{
  "name": "freq_qos_remove_notifier",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579925664,
      "name": "freq_qos_remove_notifier",
      "external": true,
      "loc": "kernel/power/qos.c:873",
      "file": "kernel/power/qos.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_online",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free",
        "drivers/cpufreq/cpufreq.c:cpufreq_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925664,
      "name": "freq_qos_remove_notifier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int freq_qos_remove_notifier(struct freq_constraints * qos, enum freq_qos_req_type type, struct notifier_block * notifier)
```
</details>
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
