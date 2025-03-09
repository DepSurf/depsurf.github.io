# Function: <code>regset_get</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579717840,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717840,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725232,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725232,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805264,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579805264,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915184,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915184,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580069424,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580069424,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123296,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123296,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
```

```json
{
  "name": "regset_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580168880,
      "name": "regset_get",
      "external": true,
      "loc": "kernel/regset.c:33",
      "file": "kernel/regset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/binfmt_elf.c:fill_thread_core_info",
        "fs/compat_binfmt_elf.c:fill_thread_core_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580168880,
      "name": "regset_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int regset_get(struct task_struct * target, const struct user_regset * regset, unsigned int size, void * data)
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
