# Function: <code>__kretprobe_trampoline_handler</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs * regs, void * trampoline_address, void * frame_pointer)
```

```json
{
  "name": "__kretprobe_trampoline_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kretprobe_trampoline_handler",
      "external": true,
      "loc": "kernel/kprobes.c:1863",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591316107,
      "name": "__kretprobe_trampoline_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071580497344,
      "name": "__kretprobe_trampoline_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs * regs, void * trampoline_address, void * frame_pointer)
```

```json
{
  "name": "__kretprobe_trampoline_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kretprobe_trampoline_handler",
      "external": true,
      "loc": "kernel/kprobes.c:1868",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258303,
      "name": "__kretprobe_trampoline_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071580501360,
      "name": "__kretprobe_trampoline_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
long unsigned int __kretprobe_trampoline_handler(struct pt_regs * regs, void * trampoline_address, void * frame_pointer)
```

```json
{
  "name": "__kretprobe_trampoline_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__kretprobe_trampoline_handler",
      "external": true,
      "loc": "kernel/kprobes.c:1860",
      "file": "kernel/kprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:trampoline_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592163339,
      "name": "__kretprobe_trampoline_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    },
    {
      "addr": 18446744071580668944,
      "name": "__kretprobe_trampoline_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs * regs, void * trampoline_address, void * frame_pointer)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
long unsigned int __kretprobe_trampoline_handler(struct pt_regs * regs, void * trampoline_address, void * frame_pointer)
```
</details>
</li>
</ul>
