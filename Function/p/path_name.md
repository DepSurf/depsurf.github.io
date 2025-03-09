# Function: <code>path_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int path_name(const char * op, struct aa_label * label, struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request, bool delegate_deleted)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582547280,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_path_perm",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_path_link",
        "security/apparmor/file.c:aa_file_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582547280,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787616,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:168",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787616,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582883008,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:168",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582883008,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582953088,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:170",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582953088,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583115200,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:170",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583115200,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583320928,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:170",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583320928,
      "name": "path_name.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583439424,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:171",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439424,
      "name": "path_name.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583624448,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624448,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583730624,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730624,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584113072,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584113072,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584232160,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:156",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584232160,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584257232,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:158",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257232,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584643184,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:158",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:__file_path_perm",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643184,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585300416,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:159",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585300416,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
int path_name(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586039456,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:280",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586039456,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int path_name(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586274480,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:300",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586274480,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int path_name(const char * op, const struct cred * subj_cred, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586531232,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:302",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:aa_path_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586531232,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495527120,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495527120,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228893584,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228893584,
      "name": "path_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289607024,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289607024,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274704276,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274704276,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583699360,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583699360,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583636416,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636416,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583683136,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583683136,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "path_name",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583782880,
      "name": "path_name",
      "external": false,
      "loc": "security/apparmor/file.c:167",
      "file": "security/apparmor/file.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583782880,
      "name": "path_name.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool delegate_deleted</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, label, path, flags, buffer, name, cond, request</code> ➡️ <code>op, subj_cred, label, path, flags, buffer, name, cond, request</code>
</li>
</ul>
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int path_name(const char * op, struct aa_label * label, const struct path * path, int flags, char * buffer, const char * * name, struct path_cond * cond, u32 request)
```
</details>
</li>
</ul>
