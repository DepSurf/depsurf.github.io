# Function: <code>vmcoreinfo_append_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949088,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/kexec_core.c:1327",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/kexec_core.c:crash_save_vmcoreinfo",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949088,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980384,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/kexec_core.c:1374",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980384,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580010880,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/kexec_core.c:1376",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/printk/printk.c:log_buf_kexec_setup",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo_init",
        "kernel/kexec_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580010880,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012752,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:350",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012752,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059584,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:351",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059584,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:351",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117131,
      "name": "vmcoreinfo_append_str.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580116816,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:351",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580164123,
      "name": "vmcoreinfo_append_str.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580163808,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580210123,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580209808,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580258459,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580258144,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327019,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580326720,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:351",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:add_build_id_vmcoreinfo",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591314560,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580312208,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:351",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591256993,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580315696,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:363",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592160201,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580469232,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:359",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593933307,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580662944,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:371",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595999147,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580932896,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:371",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596517258,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581019296,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:690",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/crash_core_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597417269,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581117184,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491500904,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo",
        "arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo",
        "arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo",
        "arch/arm64/kernel/crash_core.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491500904,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225482440,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225482440,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284460496,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "arch/powerpc/kernel/machine_kexec.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284460496,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271942726,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271942726,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227259,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580226944,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580174747,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580174432,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580218731,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580218416,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void vmcoreinfo_append_str(const char * fmt, void (anon))
```

```json
{
  "name": "vmcoreinfo_append_str",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmcoreinfo_append_str",
      "external": true,
      "loc": "kernel/crash_core.c:349",
      "file": "kernel/crash_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "arch/x86/kernel/machine_kexec_64.c:arch_crash_save_vmcoreinfo",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/printk/printk.c:log_buf_vmcoreinfo_setup",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/crash_core.c:crash_save_vmcoreinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271499,
      "name": "vmcoreinfo_append_str.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    },
    {
      "addr": 18446744071580271184,
      "name": "vmcoreinfo_append_str",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
