# Function: <code>apparmor_bprm_creds_for_exec</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584053376,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:852",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584053376,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2732
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
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172496,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:852",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172496,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2734
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
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199296,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:854",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199296,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2930
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:854",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592305642,
      "name": "apparmor_bprm_creds_for_exec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584584448,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3001
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:857",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594086936,
      "name": "apparmor_bprm_creds_for_exec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585231856,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2980
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:870",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596100359,
      "name": "apparmor_bprm_creds_for_exec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071585964640,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3139
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:870",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596623642,
      "name": "apparmor_bprm_creds_for_exec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586197264,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2778
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
```

```json
{
  "name": "apparmor_bprm_creds_for_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "apparmor_bprm_creds_for_exec",
      "external": true,
      "loc": "security/apparmor/domain.c:877",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597529940,
      "name": "apparmor_bprm_creds_for_exec.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586449152,
      "name": "apparmor_bprm_creds_for_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2796
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int apparmor_bprm_creds_for_exec(struct linux_binprm * bprm)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
