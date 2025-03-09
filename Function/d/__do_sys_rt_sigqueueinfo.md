# Function: <code>__do_sys_rt_sigqueueinfo</code>

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
long int __do_sys_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * uinfo)
```

```json
{
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499936,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3281",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499936,
      "name": "__do_sys_rt_sigqueueinfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579533598,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3607",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556318,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3855",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579582462,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579619710,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3881",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579600126,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3902",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579605631,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3924",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579680911,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4012",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579775407,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3995",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579907807,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3997",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579957535,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4021",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579996815,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:4032",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__arm64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224803852,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283570844,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271456566,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__se_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558766,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579487422,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579556046,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
  "name": "__do_sys_rt_sigqueueinfo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579589406,
      "name": "__do_sys_rt_sigqueueinfo",
      "external": false,
      "loc": "kernel/signal.c:3863",
      "file": "kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/signal.c:__ia32_sys_rt_sigqueueinfo",
        "kernel/signal.c:__x64_sys_rt_sigqueueinfo"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long int __do_sys_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * uinfo)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
long int __do_sys_rt_sigqueueinfo(pid_t pid, int sig, siginfo_t * uinfo)
```
</details>
</li>
</ul>
