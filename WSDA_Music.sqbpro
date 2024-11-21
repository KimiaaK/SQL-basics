<?xml version="1.0" encoding="UTF-8"?><sqlb_project><db path="WSDA_Music.db" readonly="0" foreign_keys="1" case_sensitive_like="0" temp_store="0" wal_autocheckpoint="1000" synchronous="2"/><attached/><window><main_tabs open="structure browser pragmas query" current="3"/></window><tab_structure><column_width id="0" width="300"/><column_width id="1" width="0"/><column_width id="2" width="100"/><column_width id="3" width="3370"/><column_width id="4" width="0"/><expanded_item id="0" parent="1"/><expanded_item id="1" parent="1"/><expanded_item id="2" parent="1"/><expanded_item id="3" parent="1"/></tab_structure><tab_browse><table title="Album" custom_title="0" dock_id="6" table="4,5:mainAlbum"/><dock_state state="000000ff00000000fd0000000100000002000002a60000025bfc0100000002fb000000160064006f0063006b00420072006f00770073006500310100000000000002a60000000000000000fb000000160064006f0063006b00420072006f00770073006500360100000000ffffffff0000010100ffffff000002a60000000000000004000000040000000800000008fc00000000"/><default_encoding codec=""/><browse_table_settings/></tab_browse><tab_sql><sql name="SQL 1">/*
CREATED BY: @KimiaaK
DATE CREATE: 04//11/2024
*/

SELECT 
	FirstName AS [Customer First Name],
	LastName AS [Customer Last Name],
	Email

FROM 
	Customer
ORDER BY
	FirstName
LIMIT 5
	
	</sql><sql name="SQL 2">/*
HOW MANY CUSTOMERS PURCHASED TWO SONGS AT 0,99$ EACH?
*/

SELECT
	InvoiceDate,
	BillingAddress,
	BillingCity,
	total

FROM
	Invoice

WHERE
	total = 1.98

ORDER BY 
	InvoiceDate
	
</sql><sql name="SQL 5*">SELECT
	InvoiceDate,
	BillingAddress,
	BillingCity,
	total

FROM
	Invoice
/*
--HOW MANY INVOICES EXIST BETWEEN 1.98$ AND 5$?

WHERE
	total BETWEEN 1.98 AND 5.00

ORDER BY 
	InvoiceDate
	
*/


/*
--HOW MANY INVOICES EXIST THAT  ARE EXACTLY 1.98$ OR 3.96$?

WHERE
	total IN(1.98, 3.96)

ORDER BY 
	InvoiceDate
	
*/


/*
--HOW MANY INVOICES BILLED IN BRUSSELS?

WHERE
	BillingCity = &quot;Brussels&quot;

ORDER BY 
	InvoiceDate
	
*/


/*
--HOW MANY INVOICES BILLED IN CITIES OF BRUSSELS, ORLANDO, AND PARIS?

WHERE
	BillingCity IN (&quot;Brussels&quot;,&quot;Paris&quot;, &quot;Orlando&quot;)

ORDER BY 
	BillingCity ASC
*/


--HOW MANY OF THE BILLED CITIES START WITH THE LETTER B?

WHERE
		BillingCity LIKE 'B%'
ORDER BY
	BillingCity ASC
</sql><current_tab id="2"/></tab_sql></sqlb_project>
