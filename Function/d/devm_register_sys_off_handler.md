# Function: <code>devm_register_sys_off_handler</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_register_sys_off_handler(struct device * dev, enum sys_off_mode mode, int priority, int (*)(struct sys_off_data *) callback, void * cb_data)
```

```json
{
  "name": "devm_register_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579904838,
      "name": "devm_register_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:485",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904688,
      "name": "devm_register_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_register_sys_off_handler(struct device * dev, enum sys_off_mode mode, int priority, int (*)(struct sys_off_data *) callback, void * cb_data)
```

```json
{
  "name": "devm_register_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057686,
      "name": "devm_register_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:502",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580057376,
      "name": "devm_register_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_register_sys_off_handler(struct device * dev, enum sys_off_mode mode, int priority, int (*)(struct sys_off_data *) callback, void * cb_data)
```

```json
{
  "name": "devm_register_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112134,
      "name": "devm_register_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:502",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111808,
      "name": "devm_register_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int devm_register_sys_off_handler(struct device * dev, enum sys_off_mode mode, int priority, int (*)(struct sys_off_data *) callback, void * cb_data)
```

```json
{
  "name": "devm_register_sys_off_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580157270,
      "name": "devm_register_sys_off_handler",
      "external": true,
      "loc": "kernel/reboot.c:516",
      "file": "kernel/reboot.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/reboot.c:devm_register_restart_handler",
        "kernel/reboot.c:devm_register_power_off_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580156720,
      "name": "devm_register_sys_off_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int devm_register_sys_off_handler(struct device * dev, enum sys_off_mode mode, int priority, int (*)(struct sys_off_data *) callback, void * cb_data)
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
