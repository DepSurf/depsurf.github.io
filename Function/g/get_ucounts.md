# Function: <code>get_ucounts</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579555782,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:126",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579542438,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:131",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579569158,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:131",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579597317,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:132",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579634437,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:132",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579659269,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579696341,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct ucounts * get_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579736784,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:128",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736784,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct ucounts * get_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579716736,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:128",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579716736,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579724528,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:181",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "kernel/cred.c:cred_alloc_blank"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724528,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579804781,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:153",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_rlimit_get_ucounts"
      ],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "mm/mlock.c:user_shm_lock",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/process_keys.c:key_change_session_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803472,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579914557,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:159",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_rlimit_get_ucounts"
      ],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "mm/mlock.c:user_shm_lock",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/process_keys.c:key_change_session_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913184,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068749,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:155",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_rlimit_get_ucounts"
      ],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "mm/mlock.c:user_shm_lock",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/process_keys.c:key_change_session_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067040,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580122358,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:155",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_rlimit_get_ucounts"
      ],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "mm/mlock.c:user_shm_lock",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/process_keys.c:key_change_session_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580120368,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct ucounts * get_ucounts(struct ucounts * ucounts)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580167942,
      "name": "get_ucounts",
      "external": true,
      "loc": "kernel/ucount.c:156",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_rlimit_get_ucounts"
      ],
      "caller_func": [
        "kernel/cred.c:prepare_kernel_cred",
        "kernel/cred.c:prepare_creds",
        "mm/mlock.c:user_shm_lock",
        "ipc/mqueue.c:mqueue_get_inode",
        "security/keys/process_keys.c:key_change_session_keyring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165904,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct ucounts * get_ucounts(struct user_namespace * ns, kuid_t uid)
```

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490876432,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ucount.c:inc_ucount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490876432,
      "name": "get_ucounts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 544
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224894056,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283709856,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271529818,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579672661,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601013,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579669893,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
  "name": "get_ucounts",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579704037,
      "name": "get_ucounts",
      "external": false,
      "loc": "kernel/ucount.c:125",
      "file": "kernel/ucount.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/ucount.c:inc_ucount"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct ucounts * get_ucounts(struct user_namespace * ns, kuid_t uid)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucounts * ucounts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace * ns</code>
</li>
<li>
<b>Param removed. </b>
<code>kuid_t uid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct ucounts * get_ucounts(struct user_namespace * ns, kuid_t uid)
```
</details>
</li>
</ul>
