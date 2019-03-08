---


---

<h1 id="sellin---compras-de-fornecedor">SellIn - Compras de Fornecedor</h1>
<p>Modelo de Dados - Sellin</p>
<h3 id="sellin---cabeçalho">SellIn - Cabeçalho</h3>

<table>
<thead>
<tr>
<th>Campo</th>
<th>Descrição</th>
<th>Tipo</th>
<th>Restrições</th>
<th>Exemplo</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>store_id</strong>*</td>
<td><strong>Identificador interno da loja</strong></td>
<td><strong>integer ou string</strong></td>
<td>–</td>
<td>1</td>
</tr>
<tr>
<td><strong>id</strong>*</td>
<td><strong>Identificador (NF) da compra</strong></td>
<td><strong>string</strong></td>
<td>tamanho máximo de 50 caracteres</td>
<td>“RCNTH345987”</td>
</tr>
<tr>
<td>supplier_taxpayer_id*</td>
<td>CNPJ do Fornecedor</td>
<td>string</td>
<td>tamanho máximo de 14 caracteres</td>
<td>“14463765000172”</td>
</tr>
<tr>
<td>sellin_timestamp*</td>
<td>Data e hora da compra</td>
<td>string</td>
<td>satisfazer o padrão “YYYY-MM-DDTHH:MM:SS”</td>
<td>“2017-08-20T14:55:08”</td>
</tr>
<tr>
<td>nfe_access_key</td>
<td>Chave de acesso para NFe/SAT</td>
<td>string</td>
<td>tamanho máximo de 50 caracteres</td>
<td>“NFe31170901704848000164550020000018481058491134”</td>
</tr>
<tr>
<td>other_expenses</td>
<td>Outras despesas</td>
<td>float</td>
<td>–</td>
<td>1.99</td>
</tr>
<tr>
<td>seller_id</td>
<td>CPF do vendedor associado a esta NF, caso exista vendedor relacionado</td>
<td>string</td>
<td>tamanho máximo de 11 caracteres</td>
<td>“RCNTH345987”</td>
</tr>
<tr>
<td>ipi</td>
<td>Valor do IPI sobre a compra</td>
<td>float</td>
<td>–</td>
<td>1.87</td>
</tr>
<tr>
<td>iss</td>
<td>Valor do ISS sobre a compra</td>
<td>float</td>
<td>–</td>
<td>1.01</td>
</tr>
<tr>
<td>sales_discount</td>
<td>Valor de desconto na compra</td>
<td>float</td>
<td>–</td>
<td>5.99</td>
</tr>
<tr>
<td>insurance_price</td>
<td>Valor do seguro</td>
<td>float</td>
<td>–</td>
<td>2.0</td>
</tr>
<tr>
<td>gross_total*</td>
<td>Valor total da NF. Este valor deve vir com 4 casas decimais</td>
<td>float</td>
<td>–</td>
<td>5.99</td>
</tr>
<tr>
<td>cancellation_flag*</td>
<td>Indica se esta compra foi cancelada ou não</td>
<td>string</td>
<td>Valores aceitos: “S” — para sim e “N” — para não</td>
<td>“S”</td>
</tr>
<tr>
<td>nfe_series_number</td>
<td>Número de Série da Nota Fiscal</td>
<td>integer</td>
<td>–</td>
<td>1</td>
</tr>
<tr>
<td>nfe_number</td>
<td>Número da Nota Fiscal</td>
<td>integer</td>
<td>–</td>
<td>1267232</td>
</tr>
<tr>
<td>sales_addition</td>
<td>Valor de acréscimo na compra</td>
<td>float</td>
<td>Este valor deve vir com 4 casas decimais</td>
<td>4.55</td>
</tr>
<tr>
<td>store_taxpayer_id*</td>
<td>CNPJ da loja</td>
<td>string</td>
<td>tamanho máximo de 14 caracteres</td>
<td>“14463765000100”</td>
</tr>
<tr>
<td>net_total*</td>
<td>Valor total da NF sem impostos e frete</td>
<td>float</td>
<td>Este valor deve vir com 4 casas decimais</td>
<td>4.99</td>
</tr>
<tr>
<td>freight_price</td>
<td>Valor do frete</td>
<td>float</td>
<td>–</td>
<td>1.0</td>
</tr>
<tr>
<td>icms</td>
<td>Valor do ICMS sobre a compra</td>
<td>float</td>
<td>–</td>
<td>2.9</td>
</tr>
</tbody>
</table><hr>

<table>
<thead>
<tr>
<th>Campo</th>
<th>Descrição</th>
<th>Tipo</th>
<th>Restrições</th>
<th>Exemplo</th>
</tr>
</thead>
<tbody>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
</tbody>
</table>
