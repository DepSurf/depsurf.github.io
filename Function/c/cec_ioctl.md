# Function: <code>cec_ioctl</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:491",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587265248,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3392
    },
    {
      "addr": 18446744071587269213,
      "name": "cec_ioctl.cold.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533856,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071587537801,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587736608,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071587740534,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
    }
  ]
}
```
</details>
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500914288,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500914288,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3280
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233431640,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233431640,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4120
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294373264,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294373264,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3648
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277689762,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277689762,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2520
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587377552,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071587381478,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587145776,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071587149702,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692752,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3335
    },
    {
      "addr": 18446744071587696678,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```

```json
{
  "name": "cec_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_ioctl",
      "external": false,
      "loc": "drivers/media/cec/cec-api.c:483",
      "file": "drivers/media/cec/cec-api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587799104,
      "name": "cec_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3327
    },
    {
      "addr": 18446744071587803120,
      "name": "cec_ioctl.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
long int cec_ioctl(struct file * filp, unsigned int cmd, long unsigned int arg)
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
