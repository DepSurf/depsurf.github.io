# Function: <code>__do_sys_landlock_create_ruleset</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584313442,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:156",
      "file": "security/landlock/syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
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
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584700567,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:156",
      "file": "security/landlock/syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
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
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585364807,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:157",
      "file": "security/landlock/syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
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
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586115367,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:157",
      "file": "security/landlock/syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
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
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586354119,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:157",
      "file": "security/landlock/syscalls.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_landlock_create_ruleset(const const struct landlock_ruleset_attr * attr, const size_t size, const __u32 flags)
```

```json
{
  "name": "__do_sys_landlock_create_ruleset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_landlock_create_ruleset",
      "external": false,
      "loc": "security/landlock/syscalls.c:165",
      "file": "security/landlock/syscalls.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_create_ruleset",
        "security/landlock/syscalls.c:__x64_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586621568,
      "name": "__do_sys_landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
    },
    {
      "addr": 18446744071597530818,
      "name": "__do_sys_landlock_create_ruleset.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
long int __do_sys_landlock_create_ruleset(const const struct landlock_ruleset_attr * attr, const size_t size, const __u32 flags)
```
</details>
</li>
</ul>
