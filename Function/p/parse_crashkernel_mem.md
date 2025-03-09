# Function: <code>parse_crashkernel_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595102730,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/kexec_core.c:1052",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595271578,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/kexec_core.c:1099",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595517350,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/kexec_core.c:1101",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596436303,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602762117,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602935966,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604733811,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604835108,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604869250,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609197527,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609197527,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 439
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612264039,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612264039,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 439
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614404985,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:38",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614404985,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 436
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615340462,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:40",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615340462,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 436
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617125521,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:40",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617125521,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 426
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627796560,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:43",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627796560,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 481
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619559584,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:43",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619559584,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 481
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
```

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621861504,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:67",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:__parse_crashkernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621861504,
      "name": "parse_crashkernel_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 481
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
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510905516,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243392796,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270643272,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604774707,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604743622,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604851894,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crashkernel_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604873392,
      "name": "parse_crashkernel_mem",
      "external": false,
      "loc": "kernel/crash_core.c:36",
      "file": "kernel/crash_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
int parse_crashkernel_mem(char * cmdline, long long unsigned int system_ram, long long unsigned int * crash_size, long long unsigned int * crash_base)
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
