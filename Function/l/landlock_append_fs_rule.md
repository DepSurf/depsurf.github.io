# Function: <code>landlock_append_fs_rule</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, u32 access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584321648,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:157",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_add_rule",
        "security/landlock/syscalls.c:__x64_sys_landlock_add_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584321648,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, u32 access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584708784,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:157",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_add_rule",
        "security/landlock/syscalls.c:__x64_sys_landlock_add_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584708784,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585382432,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:155",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_add_rule",
        "security/landlock/syscalls.c:__x64_sys_landlock_add_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382432,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586134016,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:166",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_add_rule",
        "security/landlock/syscalls.c:__x64_sys_landlock_add_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134016,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586371888,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:166",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__ia32_sys_landlock_add_rule",
        "security/landlock/syscalls.c:__x64_sys_landlock_add_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586371888,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, access_mask_t access_rights)
```

```json
{
  "name": "landlock_append_fs_rule",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586635760,
      "name": "landlock_append_fs_rule",
      "external": true,
      "loc": "security/landlock/fs.c:156",
      "file": "security/landlock/fs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:add_rule_path_beneath"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635760,
      "name": "landlock_append_fs_rule",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int landlock_append_fs_rule(const struct landlock_ruleset * ruleset, const const struct path * path, u32 access_rights)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 access_rights</code> ➡️ <code>access_mask_t access_rights</code>
</li>
</ul>
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
