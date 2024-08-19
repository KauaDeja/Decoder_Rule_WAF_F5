<h1>Log Parsing</h1>
<h2>WAF F5 BIG-IP</h2>
<text>O WAF envia para um servidor syslog que armazena os logs em um lugar específico e em seguida o servidor syslog encaminha para o SIEM que decodifica a informação, relaciona a uma regra e indexa nos security events dele próprio.</text>
<h2>Logs de exemplo que esse decoder vai funcionar</h2>
<text>waf: Jul  1 14:49:25 10.20.30.40 ASM "SQL Injection","2024-07-01 14:49:24","10.20.30.40","443","BR","/url-random.contoso/policy","N/A","10.20.30.40","10.20.30.40%0",""</text>
<h2>Referências</h2>
<text>https://www.youtube.com/watch?v=1x3MfuhC8yI</text>
<text>https://www.youtube.com/watch?v=7MRIwEgMU_A</text>
<text>https://documentation.wazuh.com/current/user-manual/ruleset/ruleset-xml-syntax/regex.html</text>
