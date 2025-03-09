# Function: <code>compat_poll_select_copy_remaining</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int compat_poll_select_copy_remaining(struct timespec * end_time, void * p, int timeval, int ret)
```

```json
{
  "name": "compat_poll_select_copy_remaining",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370608,
      "name": "compat_poll_select_copy_remaining",
      "external": false,
      "loc": "fs/select.c:1105",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370608,
      "name": "compat_poll_select_copy_remaining",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int compat_poll_select_copy_remaining(struct timespec * end_time, void * p, int timeval, int ret)
```

```json
{
  "name": "compat_poll_select_copy_remaining",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581512096,
      "name": "compat_poll_select_copy_remaining",
      "external": false,
      "loc": "fs/select.c:1101",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:compat_SyS_ppoll",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_pselect6",
        "fs/select.c:compat_SyS_old_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581512096,
      "name": "compat_poll_select_copy_remaining",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int compat_poll_select_copy_remaining(struct timespec64 * end_time, void * p, int timeval, int ret)
```

```json
{
  "name": "compat_poll_select_copy_remaining",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581669632,
      "name": "compat_poll_select_copy_remaining",
      "external": false,
      "loc": "fs/select.c:1102",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:__x32_compat_sys_ppoll",
        "fs/select.c:__ia32_compat_sys_ppoll",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_pselect",
        "fs/select.c:do_compat_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581669632,
      "name": "compat_poll_select_copy_remaining",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int compat_poll_select_copy_remaining(struct timespec * end_time, void * p, int timeval, int ret)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec * end_time</code> ➡️ <code>struct timespec64 * end_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int compat_poll_select_copy_remaining(struct timespec64 * end_time, void * p, int timeval, int ret)
```
</details>
</li>
</ul>
