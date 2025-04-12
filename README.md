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

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Kernel</th>
      <th>Codec</th>
      <th>DTS Headphone:X</th>
      <th>DTS:X Ultra</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>4.14</td>
      <td>WCD9330</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-wcd9330">4.14-wcd9330</a></td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-dtsx-ultra">4.14-dtsx-ultra</a></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD9335</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-wcd9335">4.14-wcd9335</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD934X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-wcd934x">4.14-wcd934x</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD937X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-wcd937x">4.14-wcd937x</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD938X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.14-wcd938x">4.14-wcd938x</a></td>
      <td></td>
    </tr>

    <tr>
      <td>4.19</td>
      <td>WCD9330</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-wcd9330">4.19-wcd9330</a></td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-dtsx-ultra">4.19-dtsx-ultra</a></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD9335</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-wcd9335">4.19-wcd9335</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD934X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-wcd934x">4.19-wcd934x</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD937X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-wcd937x">4.19-wcd937x</a></td>
      <td></td>
    </tr>
    <tr>
      <td></td>
      <td>WCD938X</td>
      <td><a href="https://github.com/iDead-Project/AiDTS-Eagle/tree/4.19-wcd938x">4.19-wcd938x</a></td>
      <td></td>
    </tr>
  </tbody>
</table>

<p><em>ℹ️ DTS:X Ultra branches are universal per kernel version, so only one branch is shown per kernel.</em></p>

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
  <li>Android Integration: <a href="https://github.com/iDead-Project/AiDTS-X">AiDTS:X App</a></li>
</ul>

<hr>

<h2>💬 Contributions</h2>
<p>Have patches or want to help improve support for your codec? Feel free to open a pull request or issue!</p>

</body>
</html>
