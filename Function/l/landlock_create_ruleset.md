# Function: <code>landlock_create_ruleset</code>

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
struct landlock_ruleset * landlock_create_ruleset(const u32 fs_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317536,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:47",
      "file": "security/landlock/ruleset.c",
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
      "addr": 18446744071584317536,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct landlock_ruleset * landlock_create_ruleset(const u32 fs_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704288,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:47",
      "file": "security/landlock/ruleset.c",
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
      "addr": 18446744071584704288,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct landlock_ruleset * landlock_create_ruleset(const access_mask_t fs_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585369040,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:49",
      "file": "security/landlock/ruleset.c",
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
      "addr": 18446744071585369040,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct landlock_ruleset * landlock_create_ruleset(const access_mask_t fs_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119856,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:49",
      "file": "security/landlock/ruleset.c",
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
      "addr": 18446744071586119856,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct landlock_ruleset * landlock_create_ruleset(const access_mask_t fs_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586358352,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:49",
      "file": "security/landlock/ruleset.c",
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
      "addr": 18446744071586358352,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
struct landlock_ruleset * landlock_create_ruleset(const access_mask_t fs_access_mask, const access_mask_t net_access_mask)
```

```json
{
  "name": "landlock_create_ruleset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586626224,
      "name": "landlock_create_ruleset",
      "external": true,
      "loc": "security/landlock/ruleset.c:54",
      "file": "security/landlock/ruleset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/landlock/syscalls.c:__do_sys_landlock_create_ruleset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586626224,
      "name": "landlock_create_ruleset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
struct landlock_ruleset * landlock_create_ruleset(const u32 fs_access_mask)
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
<code>const u32 fs_access_mask</code> ➡️ <code>const access_mask_t fs_access_mask</code>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const access_mask_t net_access_mask</code>
</li>
</ul>
</details>
</li>
</ul>
