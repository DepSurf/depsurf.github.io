# Function: <code>__put_compat_ipc_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__put_compat_ipc_perm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582135335,
      "name": "__put_compat_ipc_perm",
      "external": false,
      "loc": "ipc/compat.c:173",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat.c:do_compat_semctl",
        "ipc/compat.c:C_SYSC_shmctl",
        "ipc/compat.c:C_SYSC_msgctl"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __put_compat_ipc_perm(struct ipc64_perm * p, struct compat_ipc_perm * uip)
```

```json
{
  "name": "__put_compat_ipc_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582351494,
      "name": "__put_compat_ipc_perm",
      "external": false,
      "loc": "ipc/compat.c:173",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat.c:put_compat_msqid_ds",
        "ipc/compat.c:do_compat_semctl"
      ],
      "caller_func": [
        "ipc/compat.c:C_SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350848,
      "name": "__put_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __put_compat_ipc_perm(struct ipc64_perm * p, struct compat_ipc_perm * uip)
```

```json
{
  "name": "__put_compat_ipc_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582442870,
      "name": "__put_compat_ipc_perm",
      "external": false,
      "loc": "ipc/compat.c:173",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat.c:put_compat_msqid_ds",
        "ipc/compat.c:do_compat_semctl"
      ],
      "caller_func": [
        "ipc/compat.c:C_SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442224,
      "name": "__put_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __put_compat_ipc_perm(struct ipc64_perm * p, struct compat_ipc_perm * uip)
```

```json
{
  "name": "__put_compat_ipc_perm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582522102,
      "name": "__put_compat_ipc_perm",
      "external": false,
      "loc": "ipc/compat.c:173",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat.c:put_compat_msqid_ds",
        "ipc/compat.c:do_compat_semctl"
      ],
      "caller_func": [
        "ipc/compat.c:C_SYSC_shmctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521472,
      "name": "__put_compat_ipc_perm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __put_compat_ipc_perm(struct ipc64_perm * p, struct compat_ipc_perm * uip)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int __put_compat_ipc_perm(struct ipc64_perm * p, struct compat_ipc_perm * uip)
```
</details>
</li>
</ul>
