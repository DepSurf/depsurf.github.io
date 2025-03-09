# Function: <code>user_mode_thread</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
pid_t user_mode_thread(int (*)(void *) fn, void * arg, long unsigned int flags)
```

```json
{
  "name": "user_mode_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579680352,
      "name": "user_mode_thread",
      "external": true,
      "loc": "kernel/fork.c:2724",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579680352,
      "name": "user_mode_thread",
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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
pid_t user_mode_thread(int (*)(void *) fn, void * arg, long unsigned int flags)
```

```json
{
  "name": "user_mode_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579800800,
      "name": "user_mode_thread",
      "external": true,
      "loc": "kernel/fork.c:2756",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579800800,
      "name": "user_mode_thread",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
pid_t user_mode_thread(int (*)(void *) fn, void * arg, long unsigned int flags)
```

```json
{
  "name": "user_mode_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579848944,
      "name": "user_mode_thread",
      "external": true,
      "loc": "kernel/fork.c:2989",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579848944,
      "name": "user_mode_thread",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
pid_t user_mode_thread(int (*)(void *) fn, void * arg, long unsigned int flags)
```

```json
{
  "name": "user_mode_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579886736,
      "name": "user_mode_thread",
      "external": true,
      "loc": "kernel/fork.c:2979",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:rest_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886736,
      "name": "user_mode_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
pid_t user_mode_thread(int (*)(void *) fn, void * arg, long unsigned int flags)
```
</details>
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
