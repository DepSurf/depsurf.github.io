# Function: <code>xen_setup_vsyscall_time_info</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602609604,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:419",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602777898,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:419",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604572090,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604666979,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604679507,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
void xen_setup_vsyscall_time_info()
```

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578978823,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:440",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578978823,
      "name": "xen_setup_vsyscall_time_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void xen_setup_vsyscall_time_info()
```

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591241460,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:441",
      "file": "arch/x86/xen/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/time.c:xen_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591241460,
      "name": "xen_setup_vsyscall_time_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614233922,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:436",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615153241,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:436",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071616918300,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:436",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627517158,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:436",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619262397,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:444",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621555069,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:444",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604605779,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604683603,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
  "name": "xen_setup_vsyscall_time_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604683587,
      "name": "xen_setup_vsyscall_time_info",
      "external": false,
      "loc": "arch/x86/xen/time.c:432",
      "file": "arch/x86/xen/time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/time.c:xen_time_init"
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
void xen_setup_vsyscall_time_info()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void xen_setup_vsyscall_time_info()
```
</details>
</li>
</ul>
