# Function: <code>unshare_sighand</code>

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
int unshare_sighand(struct task_struct * me)
```

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582112592,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1277",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582112592,
      "name": "unshare_sighand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int unshare_sighand(struct task_struct * me)
```

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157232,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1189",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157232,
      "name": "unshare_sighand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582186077,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1181",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:begin_new_exec"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582503450,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1181",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:begin_new_exec"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583026702,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1188",
      "file": "fs/exec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/exec.c:begin_new_exec"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int unshare_sighand(struct task_struct * me)
```

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583579616,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1183",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583579616,
      "name": "unshare_sighand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int unshare_sighand(struct task_struct * me)
```

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583794720,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1186",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583794720,
      "name": "unshare_sighand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int unshare_sighand(struct task_struct * me)
```

```json
{
  "name": "unshare_sighand",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584000816,
      "name": "unshare_sighand",
      "external": false,
      "loc": "fs/exec.c:1201",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:begin_new_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584000816,
      "name": "unshare_sighand",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int unshare_sighand(struct task_struct * me)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int unshare_sighand(struct task_struct * me)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int unshare_sighand(struct task_struct * me)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
