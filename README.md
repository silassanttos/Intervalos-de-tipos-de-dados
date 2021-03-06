# Intervalos-de-tipos-de-dados


<table aria-label="Tabela 1" class="table table-sm">
<thead>
<tr>
<th>Nome do Tipo</th>
<th>Bytes</th>
<th>Outros nomes</th>
<th>Intervalo de valores</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong><code>int</code></strong></td>
<td>4</td>
<td><strong><code>signed</code></strong></td>
<td>-2.147.483.648 a 2.147.483.647</td>
</tr>
<tr>
<td><strong><code>unsigned int</code></strong></td>
<td>4</td>
<td><strong><code>unsigned</code></strong></td>
<td>0 a 4.294.967.295</td>
</tr>
<tr>
<td><strong><code>__int8</code></strong></td>
<td>1</td>
<td><strong><code>char</code></strong></td>
<td>-128 a 127</td>
</tr>
<tr>
<td><strong><code>unsigned __int8</code></strong></td>
<td>1</td>
<td><strong><code>unsigned char</code></strong></td>
<td>0 a 255</td>
</tr>
<tr>
<td><strong><code>__int16</code></strong></td>
<td>2</td>
<td><strong><code>short</code></strong>, <strong><code>short int</code></strong>, <strong><code>signed short int</code></strong></td>
<td>-32.768 a 32.767</td>
</tr>
<tr>
<td><strong><code>unsigned __int16</code></strong></td>
<td>2</td>
<td><strong><code>unsigned short</code></strong>, <strong><code>unsigned short int</code></strong></td>
<td>0 a 65.535</td>
</tr>
<tr>
<td><strong><code>__int32</code></strong></td>
<td>4</td>
<td><strong><code>signed</code></strong>, <strong><code>signed int</code></strong>, <strong><code>int</code></strong></td>
<td>-2.147.483.648 a 2.147.483.647</td>
</tr>
<tr>
<td><strong><code>unsigned __int32</code></strong></td>
<td>4</td>
<td><strong><code>unsigned</code></strong>, <strong><code>unsigned int</code></strong></td>
<td>0 a 4.294.967.295</td>
</tr>
<tr>
<td><strong><code>__int64</code></strong></td>
<td>8</td>
<td><strong><code>long long</code></strong>, <strong><code>signed long long</code></strong></td>
<td>-9.223.372.036.854.775.808 a 9.223.372.036.854.775.807</td>
</tr>
<tr>
<td><strong><code>unsigned __int64</code></strong></td>
<td>8</td>
<td><strong><code>unsigned long long</code></strong></td>
<td>0 a 18.446.744.073.709.551.615</td>
</tr>
<tr>
<td><strong><code>bool</code></strong></td>
<td>1</td>
<td>nenhum</td>
<td><strong><code>false</code></strong> ou <strong><code>true</code></strong></td>
</tr>
<tr>
<td><strong><code>char</code></strong></td>
<td>1</td>
<td>nenhum</td>
<td>-128 a 127 por padr??o<br><br> 0 a 255 quando compilado usando <a href="https://docs.microsoft.com/pt-br/cpp/build/reference/j-default-char-type-is-unsigned?view=msvc-170" data-linktype="relative-path"><code>/J</code></a></td>
</tr>
<tr>
<td><strong><code>signed char</code></strong></td>
<td>1</td>
<td>nenhum</td>
<td>-128 a 127</td>
</tr>
<tr>
<td><strong><code>unsigned char</code></strong></td>
<td>1</td>
<td>nenhum</td>
<td>0 a 255</td>
</tr>
<tr>
<td><strong><code>short</code></strong></td>
<td>2</td>
<td><strong><code>short int</code></strong>, <strong><code>signed short int</code></strong></td>
<td>-32.768 a 32.767</td>
</tr>
<tr>
<td><strong><code>unsigned short</code></strong></td>
<td>2</td>
<td><strong><code>unsigned short int</code></strong></td>
<td>0 a 65.535</td>
</tr>
<tr>
<td><strong><code>long</code></strong></td>
<td>4</td>
<td><strong><code>long int</code></strong>, <strong><code>signed long int</code></strong></td>
<td>-2.147.483.648 a 2.147.483.647</td>
</tr>
<tr>
<td><strong><code>unsigned long</code></strong></td>
<td>4</td>
<td><strong><code>unsigned long int</code></strong></td>
<td>0 a 4.294.967.295</td>
</tr>
<tr>
<td><strong><code>long long</code></strong></td>
<td>8</td>
<td>none (mas equivalente a <strong><code>__int64</code></strong>)</td>
<td>-9.223.372.036.854.775.808 a 9.223.372.036.854.775.807</td>
</tr>
<tr>
<td><strong><code>unsigned long long</code></strong></td>
<td>8</td>
<td>none (mas equivalente a <strong><code>unsigned __int64</code></strong>)</td>
<td>0 a 18.446.744.073.709.551.615</td>
</tr>
<tr>
<td><strong><code>enum</code></strong></td>
<td>varia</td>
<td>nenhum</td>
<td aria-label="Sem valor"></td>
</tr>
<tr>
<td><strong><code>float</code></strong></td>
<td>4</td>
<td>nenhum</td>
<td>3.4E +/- 38 (7 d??gitos)</td>
</tr>
<tr>
<td><strong><code>double</code></strong></td>
<td>8</td>
<td>nenhum</td>
<td>1.7E +/- 308 (15 d??gitos)</td>
</tr>
<tr>
<td><strong><code>long double</code></strong></td>
<td>mesmo que <strong><code>double</code></strong></td>
<td>nenhum</td>
<td>Mesmo que <strong><code>double</code></strong></td>
</tr>
<tr>
<td><strong><code>wchar_t</code></strong></td>
<td>2</td>
<td><strong><code>__wchar_t</code></strong></td>
<td>0 a 65.535</td>
</tr>
</tbody>
</table>
