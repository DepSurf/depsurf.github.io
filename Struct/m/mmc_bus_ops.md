# Struct: <code>mmc_bus_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) power_save;
    int (*)(struct mmc_host *) power_restore;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
    int (*)(struct mmc_host *) flush_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
    int (*)(struct mmc_host *) flush_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
    int (*)(struct mmc_host *) flush_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
    int (*)(struct mmc_host *) flush_cache;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
    bool (*)(struct mmc_host *) cache_enabled;
    int (*)(struct mmc_host *) flush_cache;
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
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *) hw_reset</code>
</li>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *) sw_reset</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct mmc_host *) reset</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>int (*)(struct mmc_host *) power_save</code>
</li>
<li>
<b>Field removed. </b>
<code>int (*)(struct mmc_host *) power_restore</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool (*)(struct mmc_host *) cache_enabled</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int (*)(struct mmc_host *) flush_cache</code>
</li>
</ul>
</details>
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
struct mmc_bus_ops {
    void (*)(struct mmc_host *) remove;
    void (*)(struct mmc_host *) detect;
    int (*)(struct mmc_host *) pre_suspend;
    int (*)(struct mmc_host *) suspend;
    int (*)(struct mmc_host *) resume;
    int (*)(struct mmc_host *) runtime_suspend;
    int (*)(struct mmc_host *) runtime_resume;
    int (*)(struct mmc_host *) alive;
    int (*)(struct mmc_host *) shutdown;
    int (*)(struct mmc_host *) hw_reset;
    int (*)(struct mmc_host *) sw_reset;
}
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
