# Function: <code>SyS_semtimedop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```

```json
{
  "name": "SyS_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582161248,
      "name": "SyS_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1792",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582161248,
      "name": "SyS_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```

```json
{
  "name": "SyS_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582377478,
      "name": "SyS_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1790",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582377456,
      "name": "SyS_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```

```json
{
  "name": "SyS_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582469574,
      "name": "SyS_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1755",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582469552,
      "name": "SyS_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```

```json
{
  "name": "SyS_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582550182,
      "name": "SyS_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1768",
      "file": "ipc/sem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582550160,
      "name": "SyS_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```

```json
{
  "name": "SyS_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582700624,
      "name": "SyS_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:2113",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582700624,
      "name": "SyS_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
long int SyS_semtimedop(long int semid, long int tsops, long int nsops, long int timeout)
```
</details>
</li>
</ul>
