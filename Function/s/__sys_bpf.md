# Function: <code>__sys_bpf</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```

```json
{
  "name": "__sys_bpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sys_bpf",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4572",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_sys_bpf",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581152896,
      "name": "__sys_bpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3610
    },
    {
      "addr": 18446744071592180664,
      "name": "__sys_bpf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```

```json
{
  "name": "__sys_bpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581428240,
      "name": "__sys_bpf",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4863",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_sys_bpf",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428240,
      "name": "__sys_bpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3552
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
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```

```json
{
  "name": "__sys_bpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sys_bpf",
      "external": false,
      "loc": "kernel/bpf/syscall.c:4915",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_sys_bpf",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780912,
      "name": "__sys_bpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4013
    },
    {
      "addr": 18446744071596014100,
      "name": "__sys_bpf.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```

```json
{
  "name": "__sys_bpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943216,
      "name": "__sys_bpf",
      "external": false,
      "loc": "kernel/bpf/syscall.c:5098",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_sys_bpf",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943216,
      "name": "__sys_bpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2887
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
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```

```json
{
  "name": "__sys_bpf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582070000,
      "name": "__sys_bpf",
      "external": false,
      "loc": "kernel/bpf/syscall.c:5418",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:kern_sys_bpf",
        "kernel/bpf/syscall.c:bpf_sys_bpf",
        "kernel/bpf/syscall.c:__ia32_sys_bpf",
        "kernel/bpf/syscall.c:__x64_sys_bpf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070000,
      "name": "__sys_bpf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2563
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int __sys_bpf(int cmd, bpfptr_t uattr, unsigned int size)
```
</details>
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
