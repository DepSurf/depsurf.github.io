# Function: <code>call_usermodehelper_setup_file</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540240,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:403",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540240,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579576912,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:407",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576912,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600352,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600352,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626208,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626208,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655536,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655536,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490792184,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490792184,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224828408,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224828408,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283618496,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283618496,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271473314,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271473314,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579602512,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579602512,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579531152,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579531152,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579599792,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579599792,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```

```json
{
  "name": "call_usermodehelper_setup_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579633408,
      "name": "call_usermodehelper_setup_file",
      "external": true,
      "loc": "kernel/umh.c:408",
      "file": "kernel/umh.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:fork_usermode_blob"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579633408,
      "name": "call_usermodehelper_setup_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
struct subprocess_info * call_usermodehelper_setup_file(struct file * file, int (*)(struct subprocess_info *, struct cred *) init, void (*)(struct subprocess_info *) cleanup, void * data)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
