# Demo of custimizations
All customizations is done in the configuration file "Reboot Dialog.exe.config"<br/>

## Colors
<table>
<thead>
<tr>
<th align="center">Original</th>
<th align="center">Black & White</th>
<th align="center">Dark Blue & White</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<pre lang="php">
TextShadows = True
FontColor = #FFFFFF
BackgroundColor = #FF303946
</pre>
</td>
<td>
<pre lang="php">
TextShadows = False
FontColor = #FFFFFF
BackgroundColor = #000000
</td>
<td>
<pre lang="php">
TextShadows = True
FontColor = #FFFFFF
BackgroundColor = #334d93
</pre>
</td>
</tr><tr>
    <td><img src=/Images/demo_Color_Original.png /></td>
    <td><img src=/Images/demo_Color_BlackWhite.png /></td>
    <td><img src=/Images/demo_Color_BlueWhite.png /></td>
</tbody></table>

## Picture/Logo
You can change the default picture with something else like your company logo by adding a Picture.PNG file to same folder as the binary.<br/>
Download example picture: [Picture.png](/Images/Picture.png)<br/>
![Picture Demo](/Images/demo_Picture.png)

## Transparency
All the pictures have a white word document in the background to show the transparency.<br/>

<table>
<thead>
<tr>
<th align="center">25%</th>
<th align="center">50%</th>
<th align="center">75%</th>
</tr>
</thead>
<tbody>
<tr>
<td>
<pre lang="php">
Transparent = 0.25
</pre>
</td>
<td>
<pre lang="php">
Transparent = 0.50
</td>
<td>
<pre lang="php">
Transparent = 0.75
</pre>
</td>
</tr><tr>
    <td><img src=/Images/demo_transparent_25.png /></td>
    <td><img src=/Images/demo_transparent_50.png /></td>
    <td><img src=/Images/demo_transparent_75.png /></td>
</tbody></table>

## Multi language
You can add any language you need or change the pre-defined languages in the "Language.xml" file.<br/>
If the file is missing or the user language is not supported then it UI will revert to default from the "Reboot Dialog.config" file.<br/>

<table>
<thead>
<tr>
<th align="center">French</th>
<th align="center">German</th>
<th align="center">Chinese</th>
<th align="center">Japanese</th>
</tr>
</thead>
<tbody>
<tr>
    <td><img src=/Images/fr-FR.PNG /></td>
    <td><img src=/Images/de-DE.PNG /></td>
    <td><img src=/Images/zh-CN.PNG /></td>
    <td><img src=/Images/ja-JP.PNG /></td>
</tbody></table>
