# Function: <code>prepare_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int prepare_timeout(const struct timespec * u_abs_timeout, ktime_t * expires, struct timespec * ts)
```

```json
{
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170400,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:668",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170400,
      "name": "prepare_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int prepare_timeout(const struct timespec * u_abs_timeout, ktime_t * expires, struct timespec * ts)
```

```json
{
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582386624,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:666",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582386624,
      "name": "prepare_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int prepare_timeout(const struct timespec * u_abs_timeout, ktime_t * expires, struct timespec * ts)
```

```json
{
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582478816,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:666",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582478816,
      "name": "prepare_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int prepare_timeout(const struct timespec * u_abs_timeout, struct timespec * ts)
```

```json
{
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582559584,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:670",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582559584,
      "name": "prepare_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582722356,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:670",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582919083,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:694",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583028219,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:694",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583210011,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:749",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583315787,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583646747,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:829",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583767931,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:829",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583792124,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:829",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584154636,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:831",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584752922,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:843",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585447930,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:843",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585679162,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:843",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585926010,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:844",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495052092,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__arm64_sys_mq_timedreceive",
        "ipc/mqueue.c:__arm64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228454072,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288942112,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274325456,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583284523,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583221659,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583268555,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
  "name": "prepare_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583360075,
      "name": "prepare_timeout",
      "external": false,
      "loc": "ipc/mqueue.c:748",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__ia32_sys_mq_timedreceive",
        "ipc/mqueue.c:__x64_sys_mq_timedreceive",
        "ipc/mqueue.c:__ia32_sys_mq_timedsend",
        "ipc/mqueue.c:__x64_sys_mq_timedsend"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ktime_t * expires</code>
</li>
<li>
<b>Param reordered. </b>
<code>u_abs_timeout, expires, ts</code> ➡️ <code>u_abs_timeout, ts</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int prepare_timeout(const struct timespec * u_abs_timeout, struct timespec * ts)
```
</details>
</li>
</ul>
