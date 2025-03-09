# Function: <code>speculation_ctrl_update</code>

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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579084560,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:466",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579084560,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579094160,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094160,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096144,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096144,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108800,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:576",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108800,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579108624,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:578",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579108624,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115232,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:590",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115232,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140672,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:607",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140672,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178352,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:623",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178352,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579233200,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:623",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579233200,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579239072,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:651",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239072,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267872,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:663",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267872,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096528,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096528,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579028576,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579028576,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579096080,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579096080,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void speculation_ctrl_update(long unsigned int tif)
```

```json
{
  "name": "speculation_ctrl_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100432,
      "name": "speculation_ctrl_update",
      "external": true,
      "loc": "arch/x86/kernel/process.c:480",
      "file": "arch/x86/kernel/process.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/process.c:speculation_ctrl_update_current",
        "arch/x86/kernel/process.c:arch_setup_new_exec",
        "arch/x86/kernel/cpu/bugs.c:x86_virt_spec_ctrl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100432,
      "name": "speculation_ctrl_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void speculation_ctrl_update(long unsigned int tif)
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
void speculation_ctrl_update(long unsigned int tif)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void speculation_ctrl_update(long unsigned int tif)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void speculation_ctrl_update(long unsigned int tif)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void speculation_ctrl_update(long unsigned int tif)
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
