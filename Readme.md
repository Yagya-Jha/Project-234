<h1>Project-234</h1>

<table>
  <tr>
    <td>Code</td>
    <td>Output</td>
  </tr>
  <tr>
    <td>select customers.last_name as customer_last_name, customers.phone as customer_phone, company_products.name as product_name, suppliers.contact_name as supplier_contact_name from customers left join suppliers on customers.id=suppliers.id left join company_products on suppliers.id=company_products.supplier_id;</td>
    <td><img src="https://github-production-user-asset-6210df.s3.amazonaws.com/74773203/256797235-a290d766-b845-401c-b382-d0624e60efce.png"></td>
  </tr>
</table>
