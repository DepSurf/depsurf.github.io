# Function: <code>copy_string_kernel</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:603",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:__do_execve_file",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582115734,
      "name": "copy_string_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582106464,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:616",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:do_execveat_common",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591339598,
      "name": "copy_string_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582152768,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:608",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282314,
      "name": "copy_string_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582176832,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:608",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592229390,
      "name": "copy_string_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071582494320,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:613",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594008965,
      "name": "copy_string_kernel.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071583019840,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 641
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585280,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:613",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585280,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583802464,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:618",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583802464,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 599
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
```

```json
{
  "name": "copy_string_kernel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008672,
      "name": "copy_string_kernel",
      "external": true,
      "loc": "fs/exec.c:619",
      "file": "fs/exec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/exec.c:kernel_execve",
        "fs/exec.c:copy_strings_kernel",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script",
        "fs/binfmt_script.c:load_script"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008672,
      "name": "copy_string_kernel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
int copy_string_kernel(const char * arg, struct linux_binprm * bprm)
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
