# Function: <code>sugov_init</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579715376,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:472",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579715376,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 871
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579712256,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:489",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579712256,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579744208,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:544",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579744208,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:654",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777168,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071579779145,
      "name": "sugov_init.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:727",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819680,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 819
    },
    {
      "addr": 18446744071579822019,
      "name": "sugov_init.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:734",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579847760,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
    },
    {
      "addr": 18446744071579850196,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896000,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071579898536,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579939264,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579939264,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579926656,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:762",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579926656,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 484
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579935168,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:649",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579935168,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:656",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059600,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071592121026,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:656",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580172720,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 501
    },
    {
      "addr": 18446744071593885394,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:655",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580356288,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071595982623,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:659",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580423872,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 539
    },
    {
      "addr": 18446744071596500654,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:725",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483312,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 662
    },
    {
      "addr": 18446744071597398264,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491094160,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491094160,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
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
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225097900,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225097900,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 880
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283982912,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283982912,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1144
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868112,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071579870648,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803056,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071579805592,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579856368,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071579858808,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```

```json
{
  "name": "sugov_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sugov_init",
      "external": false,
      "loc": "kernel/sched/cpufreq_schedutil.c:737",
      "file": "kernel/sched/cpufreq_schedutil.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579901552,
      "name": "sugov_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 857
    },
    {
      "addr": 18446744071579904086,
      "name": "sugov_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int sugov_init(struct cpufreq_policy * policy)
```
</details>
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
