# Function: <code>put_compat_msqid64_ds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_compat_msqid64_ds",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582138223,
      "name": "put_compat_msqid64_ds",
      "external": false,
      "loc": "ipc/compat.c:460",
      "file": "ipc/compat.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int put_compat_msqid64_ds(struct msqid64_ds * m64, struct compat_msqid64_ds * up64)
```

```json
{
  "name": "put_compat_msqid64_ds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351136,
      "name": "put_compat_msqid64_ds",
      "external": false,
      "loc": "ipc/compat.c:460",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:C_SYSC_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351136,
      "name": "put_compat_msqid64_ds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int put_compat_msqid64_ds(struct msqid64_ds * m64, struct compat_msqid64_ds * up64)
```

```json
{
  "name": "put_compat_msqid64_ds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582442512,
      "name": "put_compat_msqid64_ds",
      "external": false,
      "loc": "ipc/compat.c:460",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:C_SYSC_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582442512,
      "name": "put_compat_msqid64_ds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int put_compat_msqid64_ds(struct msqid64_ds * m64, struct compat_msqid64_ds * up64)
```

```json
{
  "name": "put_compat_msqid64_ds",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582521744,
      "name": "put_compat_msqid64_ds",
      "external": false,
      "loc": "ipc/compat.c:460",
      "file": "ipc/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/compat.c:C_SYSC_msgctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582521744,
      "name": "put_compat_msqid64_ds",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
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
int put_compat_msqid64_ds(struct msqid64_ds * m64, struct compat_msqid64_ds * up64)
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
int put_compat_msqid64_ds(struct msqid64_ds * m64, struct compat_msqid64_ds * up64)
```
</details>
</li>
</ul>
