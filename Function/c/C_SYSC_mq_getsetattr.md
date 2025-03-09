# Function: <code>C_SYSC_mq_getsetattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "C_SYSC_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582181233,
      "name": "C_SYSC_mq_getsetattr",
      "external": false,
      "loc": "ipc/compat_mq.c:112",
      "file": "ipc/compat_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr"
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
  "name": "C_SYSC_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582397441,
      "name": "C_SYSC_mq_getsetattr",
      "external": false,
      "loc": "ipc/compat_mq.c:112",
      "file": "ipc/compat_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr"
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
  "name": "C_SYSC_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582489553,
      "name": "C_SYSC_mq_getsetattr",
      "external": false,
      "loc": "ipc/compat_mq.c:112",
      "file": "ipc/compat_mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/compat_mq.c:compat_SyS_mq_getsetattr"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr * u_mqstat, struct compat_mq_attr * u_omqstat)
```

```json
{
  "name": "C_SYSC_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568064,
      "name": "C_SYSC_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1531",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568064,
      "name": "C_SYSC_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr * u_mqstat, struct compat_mq_attr * u_omqstat)
```

```json
{
  "name": "C_SYSC_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720560,
      "name": "C_SYSC_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1531",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:compat_SyS_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720560,
      "name": "C_SYSC_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr * u_mqstat, struct compat_mq_attr * u_omqstat)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr * u_mqstat, struct compat_mq_attr * u_omqstat)
```
</details>
</li>
</ul>
