# Function: <code>rtc_nvram_write</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586296736,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:38",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586296736,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760256,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:38",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760256,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587032208,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:36",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587032208,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587192256,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:35",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587192256,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457728,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587458141,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587660848,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587661261,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588528160,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071588528576,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500814144,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500814144,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233320756,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233320756,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294272544,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294272544,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277632618,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277632618,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344608,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587345021,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112912,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587113325,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587612096,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587612509,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```

```json
{
  "name": "rtc_nvram_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rtc_nvram_write",
      "external": false,
      "loc": "drivers/rtc/nvmem.c:32",
      "file": "drivers/rtc/nvmem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723328,
      "name": "rtc_nvram_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071587723741,
      "name": "rtc_nvram_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t rtc_nvram_write(struct file * filp, struct kobject * kobj, struct bin_attribute * attr, char * buf, loff_t off, size_t count)
```
</details>
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
