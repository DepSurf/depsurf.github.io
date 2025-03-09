# Function: <code>devm_platform_get_irqs_affinity</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:351",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591486894,
      "name": "devm_platform_get_irqs_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071587043632,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:350",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430594,
      "name": "devm_platform_get_irqs_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071586927456,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:330",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592489790,
      "name": "devm_platform_get_irqs_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071587489360,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:334",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594359449,
      "name": "devm_platform_get_irqs_affinity.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071588811952,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 551
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590309936,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:334",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590309936,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590630432,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:334",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590630432,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```

```json
{
  "name": "devm_platform_get_irqs_affinity",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590989664,
      "name": "devm_platform_get_irqs_affinity",
      "external": true,
      "loc": "drivers/base/platform.c:335",
      "file": "drivers/base/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590989664,
      "name": "devm_platform_get_irqs_affinity",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int devm_platform_get_irqs_affinity(struct platform_device * dev, struct irq_affinity * affd, unsigned int minvec, unsigned int maxvec, int * * irqs)
```
</details>
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
