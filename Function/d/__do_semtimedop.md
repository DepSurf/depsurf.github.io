# Function: <code>__do_semtimedop</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```

```json
{
  "name": "__do_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1987",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592291193,
      "name": "__do_semtimedop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446744071584124544,
      "name": "__do_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2900
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```

```json
{
  "name": "__do_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1985",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594073328,
      "name": "__do_semtimedop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071584721552,
      "name": "__do_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3059
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```

```json
{
  "name": "__do_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1985",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596093033,
      "name": "__do_semtimedop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071585414624,
      "name": "__do_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3064
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```

```json
{
  "name": "__do_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1985",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596616381,
      "name": "__do_semtimedop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071585645344,
      "name": "__do_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2961
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```

```json
{
  "name": "__do_semtimedop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_semtimedop",
      "external": true,
      "loc": "ipc/sem.c:1983",
      "file": "ipc/sem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/sem.c:do_semtimedop",
        "ipc/sem.c:do_semtimedop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597522261,
      "name": "__do_semtimedop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
    },
    {
      "addr": 18446744071585892080,
      "name": "__do_semtimedop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2961
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_semtimedop(int semid, struct sembuf * sops, unsigned int nsops, const struct timespec64 * timeout, struct ipc_namespace * ns)
```
</details>
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
