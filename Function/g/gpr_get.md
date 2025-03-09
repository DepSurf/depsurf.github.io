# Function: <code>gpr_get</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```

```json
{
  "name": "gpr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490202080,
      "name": "gpr_get",
      "external": false,
      "loc": "arch/arm64/kernel/ptrace.c:591",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490202080,
      "name": "gpr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```

```json
{
  "name": "gpr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224420164,
      "name": "gpr_get",
      "external": false,
      "loc": "arch/arm/kernel/ptrace.c:571",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224420164,
      "name": "gpr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```

```json
{
  "name": "gpr_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282256128,
      "name": "gpr_get",
      "external": false,
      "loc": "arch/powerpc/kernel/ptrace.c:337",
      "file": "arch/powerpc/kernel/ptrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/ptrace.c:arch_ptrace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282256128,
      "name": "gpr_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int gpr_get(struct task_struct * target, const struct user_regset * regset, unsigned int pos, unsigned int count, void * kbuf, void * ubuf)
```
</details>
</li>
</ul>
