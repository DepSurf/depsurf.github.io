# Function: <code>new_task_smack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```

```json
{
  "name": "new_task_smack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582389888,
      "name": "new_task_smack",
      "external": false,
      "loc": "security/smack/smack_lsm.c:317",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_cred_alloc_blank",
        "security/smack/smack_lsm.c:smack_cred_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582389888,
      "name": "new_task_smack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```

```json
{
  "name": "new_task_smack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582610448,
      "name": "new_task_smack",
      "external": false,
      "loc": "security/smack/smack_lsm.c:317",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_cred_prepare",
        "security/smack/smack_lsm.c:smack_cred_alloc_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582610448,
      "name": "new_task_smack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```

```json
{
  "name": "new_task_smack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582703632,
      "name": "new_task_smack",
      "external": false,
      "loc": "security/smack/smack_lsm.c:317",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_cred_prepare",
        "security/smack/smack_lsm.c:smack_cred_alloc_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582703632,
      "name": "new_task_smack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```

```json
{
  "name": "new_task_smack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583146288,
      "name": "new_task_smack",
      "external": false,
      "loc": "security/smack/smack_lsm.c:318",
      "file": "security/smack/smack_lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/smack/smack_lsm.c:smack_init",
        "security/smack/smack_lsm.c:smack_cred_prepare",
        "security/smack/smack_lsm.c:smack_cred_alloc_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583146288,
      "name": "new_task_smack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
struct task_smack * new_task_smack(struct smack_known * task, struct smack_known * forked, gfp_t gfp)
```
</details>
</li>
</ul>
