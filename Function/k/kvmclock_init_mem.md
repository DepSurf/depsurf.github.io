# Function: <code>kvmclock_init_mem</code>

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
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604668143,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604766847,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604766847,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604792685,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604792685,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609135207,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:231",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609135207,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 228
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612203865,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:230",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612203865,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614345190,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:210",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614345190,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 244
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615275792,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:201",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615275792,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 319
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617052645,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:201",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617052645,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 321
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627696624,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:201",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627696624,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 440
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619454368,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:201",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619454368,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 440
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
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621750688,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:202",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621750688,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 440
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604706627,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604706627,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604674596,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604674596,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604784194,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604784194,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void kvmclock_init_mem()
```

```json
{
  "name": "kvmclock_init_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604796826,
      "name": "kvmclock_init_mem",
      "external": false,
      "loc": "arch/x86/kernel/kvmclock.c:224",
      "file": "arch/x86/kernel/kvmclock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvmclock.c:kvm_setup_vsyscall_timeinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604796826,
      "name": "kvmclock_init_mem",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 238
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void kvmclock_init_mem()
```
</details>
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
void kvmclock_init_mem()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kvmclock_init_mem()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kvmclock_init_mem()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kvmclock_init_mem()
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
