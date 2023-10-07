# BlockFederatedFileTransfer

This MSPL Script allowed to block file transfers to specific domains. It's based on VoIPNorm:
<br/>
<br/>&nbsp;&nbsp;Blocking File Transfers to Federated Users Using Lync MSPL Scripts
<br/>&nbsp;&nbsp;https://voipnorm.blogspot.com/2011/08/blocking-file-transfers-to-federated.html
<br/>
<br/>The AllowedDomains.txt allows to specify actions per domain:
<ul>
<li>both</li>
<li>sendonly</li>
<li>receiveonly</li>
<li>block</li>
</ul>
Example:
<br/>SIPDomain,Action
<br/>contoso.com,block

<b>Release Notes</b>
<ul>
    <li>Version 1.0: 2017/02/02 - Initial release.</li>
</ul>
