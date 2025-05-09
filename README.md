<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

<h1>🎧 AiDTS-Eagle</h1>

<p>DTS Eagle Project from <a href="https://gitlab.com/dts_project">DTS GitLab Project</a><br>
Initial bring-up for <strong>Linux kernel 4.14+</strong>, ported to <strong>Qualcomm techpack-audio</strong>.</p>

<hr>

<h2>📌 Description</h2>
<p><strong>AiDTS-Eagle</strong> is a ported DTS Eagle implementation for Android devices running custom kernels on Snapdragon SoCs.<br>
It enables advanced DTS audio features such as <strong>DTS Headphone:X</strong> and <strong>DTS:X Ultra</strong>, adapted for Qualcomm's <code>techpack/audio</code> structure.</p>

<hr>

<h2>🛠️ Supported Branches</h2>

<table class="tg"><thead>
  <tr>
    <th class="tg-0pky">Kernel Version</th>
    <th class="tg-c3ow">Codec</th>
    <th class="tg-c3ow">DTS Headphone:X</th>
    <th class="tg-c3ow">DTS:X Ultra</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-9wq8" rowspan="5">4.14</td>
    <td class="tg-0pky">WCD9330</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd9330-hpx" target="_blank" rel="noopener noreferrer">4.14-wcd9330-hpx</a></td>
    <td class="tg-9wq8" rowspan="5"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd93xx-ultra" target="_blank" rel="noopener noreferrer">4.14-wcd93xx-ultra</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">WCD9335</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd9335-hpx" target="_blank" rel="noopener noreferrer">4.14-wcd9335-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">WCD934X</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd934x-hpx" target="_blank" rel="noopener noreferrer">4.14-wcd934x-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0lax">WCD937X</td>
    <td class="tg-baqh"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd937x-hpx" target="_blank" rel="noopener noreferrer">4.14-wcd937x-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0lax">WCD938X</td>
    <td class="tg-baqh"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.14-wcd938x-hpx" target="_blank" rel="noopener noreferrer">4.14-wcd938x-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-9wq8" rowspan="5">4.19</td>
    <td class="tg-0pky">WCD9330</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd9330-hpx" target="_blank" rel="noopener noreferrer">4.19-wcd9330-hpx</a></td>
    <td class="tg-9wq8" rowspan="5"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd93xx-ultra" target="_blank" rel="noopener noreferrer">4.19-wcd93xx-ultra</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">WCD9335</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd9335-hpx" target="_blank" rel="noopener noreferrer">4.19-wcd9335-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">WCD934X</td>
    <td class="tg-c3ow"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd934x-hpx" target="_blank" rel="noopener noreferrer">4.19-wcd934x-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0lax">WCD937X</td>
    <td class="tg-baqh"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd937x-hpx" target="_blank" rel="noopener noreferrer">4.19-wcd937x-hpx</a></td>
  </tr>
  <tr>
    <td class="tg-0lax">WCD938X</td>
    <td class="tg-baqh"><a href="https://github.com/iDead-Project/ai-dts-eagle-techpack/tree/4.19-wcd938x-hpx" target="_blank" rel="noopener noreferrer">4.19-wcd938x-hpx</a></td>
  </tr>
</tbody></table>

<p><em>ℹ️ DTS:X Ultra branches are universal per kernel version, so only one branch is shown per kernel.</em></p>
<p><em>ℹ️ GKI support soon!!</em></p>

<div style="background-color: #ffeeba; border: 1px solid #f0ad4e; padding: 10px; margin-top: 20px;">
  <strong>⚠️ Warning:</strong> Some kernel sources might be a result of retrofit bring-up (e.g., from 4.4 to 4.19, commonly found on SDM660-based devices).<br>
  If you're using such a kernel, make sure to use a dedicated branch that ends with the <code>-shpx</code> suffix (e.g., <code>4.19-wcd937x-shpx</code>) to ensure compatibility.
</div>
<hr>

<h2>🎧 DTS Variant Requirements</h2>

<h3>📀 DTS Headphone:X</h3>
<ul>
  <li>You need to request your <strong>kernel developer</strong> to add this in</li>
  <li>Preferably used with a <strong>custom ROM</strong></li>
  <li>Requires <strong>Android 11</strong> or higher</li>
  <li>Device must use a <strong>Snapdragon SoC</strong> with:
    <ul>
      <li>At least <strong>WCD9330 codec</strong></li>
      <li><strong>Hexagon DSP</strong> support</li>
    </ul>
  </li>
</ul>

<h3>💽 DTS:X Ultra</h3>
<ul>
  <li>You need to request your <strong>kernel developer</strong> to add this in</li>
  <li>Requires <strong>Android 11</strong> or higher</li>
  <li>Universal variant compatible with any supported codec</li>
</ul>

<hr>

<h2>🔗 References</h2>
<ul>
  <li>DTS GitLab Source: <a href="https://gitlab.com/dts_project">https://gitlab.com/dts_project</a></li>
  <li>Android Integration: <a href="https://github.com/iDead-Project/ai-dtsx-app-adv">AiDTS:X App</a></li>
</ul>

<hr>

<h2>💬 Contributions</h2>
<p>Have patches or want to help improve support for your codec? Feel free to open a pull request or issue!</p>

<h2>🙌 Credits</h2>
<ul>
  <li><a href="https://github.com/asterixiverz">@asterixiverz</a> — for the <em>4.19 base kernel source</em></li>
  <li><a href="https://github.com/user-why-red">@user-why-red</a> — for the <em>4.19-retrofit base kernel source</em></li>
  <li><strong>DTS-Eagle team</strong> — original developers and visionaries behind the DTS-Eagle feature set</li>
</ul>

</body>
</html>
