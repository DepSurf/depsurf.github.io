# Struct: <code>mipi_dsi_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
    struct drm_dsc_config * dsc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
    struct drm_dsc_config * dsc;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    bool attached;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
    struct drm_dsc_config * dsc;
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
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
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
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct mipi_dsi_device {
    struct mipi_dsi_host * host;
    struct device dev;
    char[20] name;
    unsigned int channel;
    unsigned int lanes;
    enum mipi_dsi_pixel_format format;
    long unsigned int mode_flags;
    long unsigned int hs_rate;
    long unsigned int lp_rate;
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char[20] name</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int hs_rate</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int lp_rate</code>
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
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct drm_dsc_config * dsc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool attached</code>
</li>
</ul>
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
