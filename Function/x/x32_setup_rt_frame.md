# Function: <code>x32_setup_rt_frame</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036069,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:470",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031954,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:534",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031554,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:535",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579023687,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:536",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579027053,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:537",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579031362,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579036041,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579043200,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579043200,
      "name": "x32_setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046059,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579054752,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:540",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054752,
      "name": "x32_setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
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
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579057392,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:541",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:setup_rt_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579057392,
      "name": "x32_setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579064304,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:557",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064304,
      "name": "x32_setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579085520,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:562",
      "file": "arch/x86/kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579085520,
      "name": "x32_setup_rt_frame",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 750
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:563",
      "file": "arch/x86/kernel/signal.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "x32_setup_rt_frame",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "x32_setup_rt_frame",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Global",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "x32_setup_rt_frame",
      "external": true,
      "loc": null,
      "file": null,
      "inline": "not seen",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579046411,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578979371,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579045995,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
  "name": "x32_setup_rt_frame",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579049752,
      "name": "x32_setup_rt_frame",
      "external": false,
      "loc": "arch/x86/kernel/signal.c:538",
      "file": "arch/x86/kernel/signal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/signal.c:do_signal"
      ],
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int x32_setup_rt_frame(struct ksignal * ksig, compat_sigset_t * set, struct pt_regs * regs)
```
</details>
</li>
</ul>
