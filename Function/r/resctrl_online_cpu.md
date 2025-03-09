# Function: <code>resctrl_online_cpu</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196352,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:684",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196352,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1174
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579209264,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579210823,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211520,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579213079,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233744,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:678",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233744,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226896,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:682",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226896,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229248,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:682",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229248,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267936,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:628",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267936,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579320288,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:628",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579320288,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386448,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:581",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386448,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579396096,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:606",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579396096,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579424544,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:610",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579424544,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210368,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579211927,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145376,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579146786,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211440,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579212999,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
int resctrl_online_cpu(unsigned int cpu)
```

```json
{
  "name": "resctrl_online_cpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_online_cpu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:676",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579216720,
      "name": "resctrl_online_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071579218279,
      "name": "resctrl_online_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int resctrl_online_cpu(unsigned int cpu)
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
