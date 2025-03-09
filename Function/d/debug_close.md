# Function: <code>debug_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340752,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:1003",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585393840,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:727",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340752,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071585393840,
      "name": "debug_close",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585735936,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:988",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585790128,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:727",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585735936,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071585790128,
      "name": "debug_close",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585924224,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:988",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585978880,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:727",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585924224,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071585978880,
      "name": "debug_close",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586008656,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:988",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586062672,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:727",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008656,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586062672,
      "name": "debug_close",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586452800,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586507104,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586452800,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586507104,
      "name": "debug_close",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719680,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586770976,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719680,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586770976,
      "name": "debug_close",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586877440,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586928352,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586877440,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071586928352,
      "name": "debug_close",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136000,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587187936,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136000,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587187936,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587336400,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587388224,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587336400,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587388224,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588193936,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588246304,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193936,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588246304,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230528,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588281968,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230528,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588281968,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588113712,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588164592,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588113712,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588164592,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588748048,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588804256,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748048,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588804256,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590169248,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590229104,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169248,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071590229104,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591785232,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591847632,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591785232,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071591847632,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592208816,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592270144,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592208816,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071592270144,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592949536,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593011264,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592949536,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071593011264,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500454160,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336500510024,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500454160,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336500510024,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232910912,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232965108,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232910912,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3232965108,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293811568,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055293886688,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293811568,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 13835058055293886688,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277341936,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936277393128,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277341936,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936277393128,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587042480,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587094304,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587042480,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587094304,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587290960,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587342784,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587290960,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587342784,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```

```json
{
  "name": "debug_close",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399248,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ehci-dbg.c:978",
      "file": "drivers/usb/host/ehci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587449616,
      "name": "debug_close",
      "external": false,
      "loc": "drivers/usb/host/ohci-dbg.c:728",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399248,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587449616,
      "name": "debug_close",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int debug_close(struct inode * inode, struct file * file)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
