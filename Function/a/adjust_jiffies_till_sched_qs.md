# Function: <code>adjust_jiffies_till_sched_qs</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604725477,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:426",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977067,
      "name": "adjust_jiffies_till_sched_qs.part.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604826511,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:435",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580018067,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604860829,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068627,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void adjust_jiffies_till_sched_qs()
```

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580107786,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:501",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126766,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071580106224,
      "name": "adjust_jiffies_till_sched_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071580126840,
      "name": "adjust_jiffies_till_sched_qs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
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
void adjust_jiffies_till_sched_qs()
```

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580090026,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:515",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591307265,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    },
    {
      "addr": 18446744071580087632,
      "name": "adjust_jiffies_till_sched_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071591307339,
      "name": "adjust_jiffies_till_sched_qs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580109800,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:521",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591249830,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580251066,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:496",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592143719,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580419351,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:507",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593914931,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void adjust_jiffies_till_sched_qs()
```

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580616416,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:438",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616416,
      "name": "adjust_jiffies_till_sched_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void adjust_jiffies_till_sched_qs()
```

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580690096,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:419",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690096,
      "name": "adjust_jiffies_till_sched_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void adjust_jiffies_till_sched_qs()
```

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580757024,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:420",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init_geometry",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757024,
      "name": "adjust_jiffies_till_sched_qs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510893944,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491281260,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243382320,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225289268,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302529096,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284187064,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270633506,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271799604,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604765845,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037363,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604733899,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982652,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604843473,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028899,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
  "name": "adjust_jiffies_till_sched_qs",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604864971,
      "name": "adjust_jiffies_till_sched_qs",
      "external": false,
      "loc": "kernel/rcu/tree.c:442",
      "file": "kernel/rcu/tree.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ],
      "caller_func": [
        "kernel/rcu/tree.c:rcu_init",
        "kernel/rcu/tree.c:param_set_next_fqs_jiffies",
        "kernel/rcu/tree.c:param_set_first_fqs_jiffies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078902,
      "name": "adjust_jiffies_till_sched_qs.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void adjust_jiffies_till_sched_qs()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void adjust_jiffies_till_sched_qs()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void adjust_jiffies_till_sched_qs()
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
