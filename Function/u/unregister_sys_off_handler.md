# Function: <code>unregister_sys_off_handler</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler * handler)
```

```json
{
  "name": "unregister_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:445",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:unregister_platform_power_off",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593873470,
      "name": "unregister_sys_off_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579903856,
      "name": "unregister_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void unregister_sys_off_handler(struct sys_off_handler * handler)
```

```json
{
  "name": "unregister_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:462",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:unregister_platform_power_off",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595976787,
      "name": "unregister_sys_off_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580056448,
      "name": "unregister_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void unregister_sys_off_handler(struct sys_off_handler * handler)
```

```json
{
  "name": "unregister_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:462",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:unregister_platform_power_off",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596494530,
      "name": "unregister_sys_off_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580110800,
      "name": "unregister_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void unregister_sys_off_handler(struct sys_off_handler * handler)
```

```json
{
  "name": "unregister_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "unregister_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:476",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:do_kernel_power_off",
        "kernel/reboot.c:unregister_platform_power_off",
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597391273,
      "name": "unregister_sys_off_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580155600,
      "name": "unregister_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void unregister_sys_off_handler(struct sys_off_handler * handler)
```
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
