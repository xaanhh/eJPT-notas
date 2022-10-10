# eJPT-apuntes



### Networking

<table>
<thead>
<tr>
<th>Puertos</th>
<th>Protocolo</th>
<th>Insinuación</th>
</tr>
</thead>
<tbody>
<tr>
<td>22</td>
<td>SSH</td>
<td></td>
</tr>
<tr>
<td>25</td>
<td>SMTP</td>
<td></td>
</tr>
<tr>
<td>110</td>
<td>POP3</td>
<td></td>
</tr>
<tr>
<td>115</td>
<td>SFTP</td>
<td></td>
</tr>
<tr>
<td>143</td>
<td>IMAP</td>
<td></td>
</tr>
<tr>
<td>80</td>
<td>HTTP</td>
<td></td>
</tr>
<tr>
<td>443</td>
<td>HTTPS</td>
<td></td>
</tr>
<tr>
<td>23</td>
<td>TELNET</td>
<td></td>
</tr>
<tr>
<td>21</td>
<td>FTP</td>
<td></td>
</tr>
<tr>
<td>3389</td>
<td>RDP</td>
<td></td>
</tr>
<tr>
<td>3306</td>
<td>MYSQL</td>
<td></td>
</tr>
<tr>
<td>1433</td>
<td>MS SQL</td>
<td></td>
</tr>
<tr>
<td>137</td>
<td>NETBIOS</td>
<td>encontrar grupos de trabajo
</td>
</tr>
<tr>
<td>138</td>
<td>NETBIOS</td>
<td>lista compartida &amp; máquinas</td>
</tr>
<tr>
<td>139</td>
<td>NETBIOS</td>
<td>tránsito de datos</td>
</tr>
<tr>
<td>53</td>
<td>DNS</td>
<td></td>
</tr>
</tbody>
</table>

## Routing

![route](https://user-images.githubusercontent.com/115037568/193952770-95bf0ff2-92c4-4f9b-873c-2a531c7e6bbe.png)

Para ver nuestra tabla de enrutamiento 
- ip route **en Linux**
<pre class="notranslate"><code># Agregar una nueva ruta
ip route add 192.168.222.0/24 via 10.175.34.1
</code></pre>
