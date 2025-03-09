# Function: <code>copy_siginfo_to_external32</code>

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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579624496,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3266",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_copy_siginfo_to_user",
        "kernel/signal.c:__copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579624496,
      "name": "copy_siginfo_to_external32",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579604784,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3286",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_copy_siginfo_to_user",
        "kernel/signal.c:__copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579604784,
      "name": "copy_siginfo_to_external32",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610880,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3314",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_copy_siginfo_to_user",
        "kernel/signal.c:__copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610880,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579686928,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3402",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:x32_copy_siginfo_to_user",
        "kernel/signal.c:__copy_siginfo_to_user32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579686928,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785008,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3382",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/compat_binfmt_elf.c:fill_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785008,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579919008,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3384",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/compat_binfmt_elf.c:fill_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919008,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968896,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3408",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/compat_binfmt_elf.c:fill_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968896,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
```

```json
{
  "name": "copy_siginfo_to_external32",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008304,
      "name": "copy_siginfo_to_external32",
      "external": true,
      "loc": "kernel/signal.c:3419",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__copy_siginfo_to_user32",
        "fs/compat_binfmt_elf.c:fill_note_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008304,
      "name": "copy_siginfo_to_external32",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void copy_siginfo_to_external32(struct compat_siginfo * to, const struct kernel_siginfo * from)
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
