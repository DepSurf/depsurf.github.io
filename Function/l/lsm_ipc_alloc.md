# Function: <code>lsm_ipc_alloc</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_ipc_alloc(struct kern_ipc_perm * kip)
```

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582647390,
      "name": "lsm_ipc_alloc",
      "external": true,
      "loc": "security/security.c:561",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582637104,
      "name": "lsm_ipc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int lsm_ipc_alloc(struct kern_ipc_perm * kip)
```

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582802451,
      "name": "lsm_ipc_alloc",
      "external": true,
      "loc": "security/security.c:521",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582790992,
      "name": "lsm_ipc_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583110613,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:590",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583297109,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:589",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583402005,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583741653,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:687",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583861982,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:689",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583888158,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:692",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584251870,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:692",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584862318,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:720",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585567678,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:769",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585798590,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:777",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586046526,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:771",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495155012,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228542496,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289083524,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274401322,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583370741,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583307845,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583354517,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lsm_ipc_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583449701,
      "name": "lsm_ipc_alloc",
      "external": false,
      "loc": "security/security.c:623",
      "file": "security/security.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/security.c:security_sem_alloc",
        "security/security.c:security_shm_alloc",
        "security/security.c:security_msg_queue_alloc"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int lsm_ipc_alloc(struct kern_ipc_perm * kip)
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
int lsm_ipc_alloc(struct kern_ipc_perm * kip)
```
</details>
</li>
</ul>
