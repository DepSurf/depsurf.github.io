# Function: <code>cap_issubset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579509726,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582230273,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_secureexec",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579523895,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582449225,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_secureexec",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579547543,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582541417,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_secureexec",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579534233,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582626361,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:164",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_secureexec",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579560729,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582780688,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579588772,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582981228,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579626523,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583092540,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:165",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579650900,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275788,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579688036,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583381884,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579728644,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583719468,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_task_setioprio",
        "security/commoncap.c:cap_task_setscheduler",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579707700,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839570,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579714906,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583865282,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579793211,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584228578,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579900365,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584833499,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052359,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585534187,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106805,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:112",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585764260,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:112",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580151058,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:112",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586011732,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:112",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_bprm_creds_from_file",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490865984,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495131088,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cap_issubset(const kernel_cap_t a, const kernel_cap_t set)
```

```json
{
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224884028,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 3228518848,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
      ],
      "caller_func": [
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228516064,
      "name": "cap_issubset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283696292,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289041164,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool cap_issubset(const kernel_cap_t a, const kernel_cap_t set)
```

```json
{
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271521172,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274383000,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
      ],
      "caller_func": [
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274380712,
      "name": "cap_issubset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579664356,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583350620,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579592708,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583287724,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579661620,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583334396,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
  "name": "cap_issubset",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579695620,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "kernel/cred.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cred.c:commit_creds"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583429467,
      "name": "cap_issubset",
      "external": false,
      "loc": "include/linux/capability.h:166",
      "file": "security/commoncap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/commoncap.c:cap_safe_nice",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_bprm_set_creds",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_capset",
        "security/commoncap.c:cap_ptrace_traceme",
        "security/commoncap.c:cap_ptrace_access_check"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool cap_issubset(const kernel_cap_t a, const kernel_cap_t set)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
bool cap_issubset(const kernel_cap_t a, const kernel_cap_t set)
```
</details>
</li>
</ul>
