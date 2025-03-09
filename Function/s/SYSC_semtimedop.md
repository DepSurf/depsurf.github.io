# Function: <code>SYSC_semtimedop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "SYSC_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155104,
      "name": "SYSC_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1792",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155104,
      "name": "SYSC_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3549
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
long int SYSC_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "SYSC_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582371312,
      "name": "SYSC_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1790",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371312,
      "name": "SYSC_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3475
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
long int SYSC_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "SYSC_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582463184,
      "name": "SYSC_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1755",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582463184,
      "name": "SYSC_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3577
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
long int SYSC_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```

```json
{
  "name": "SYSC_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582542560,
      "name": "SYSC_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:1768",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:SyS_semop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582542560,
      "name": "SYSC_semtimedop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4400
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "SYSC_semtimedop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582700666,
      "name": "SYSC_semtimedop",
      "external": false,
      "loc": "ipc/sem.c:2113",
      "file": "ipc/sem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/sem.c:SyS_semtimedop"
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf * tsops, unsigned int nsops, const struct timespec * timeout)
```
</details>
</li>
</ul>
