# A T-SQL PROJECT
---
## <ins>Getting Started:</ins>
---
In order to run the queries with the data provided, a suitable tool for T-SQL queries is required.

## <ins>Installation Instructions:</ins>
---
### <ins>Installation instructions for new users:</ins>

- Step 1: Install Microsoft.Net Framework 4.0 or enable Microsoft.Net Framework 3.5 SP1.
__Note:__ the SQL Server Express (database engine only) can run on either.NET 3.5 SP1 or.NET 4, therefore both are not required.


- Step 2: Download Microsoft SQL Server 2014 Express from the link provided earlier, start it, and install it according to the setup wizard's instructions.
__Note:__ If you download using Microsoft Edge in Windows 10, the "Choose Directory for Extracted Files" window may appear, with a default/proposed path that includes System32. If this happens, modify the route to a different location on your computer before clicking 'OK.'



### <ins>Installation for Current Users:</ins>

If you already have an Express with Tools, SQL Server Management Studio Express, or Express with Advanced Services installation and want to add the full SQL Server Management Studio capability to it, follow these steps:


- Step 1: Click the right link earlier to download the required Microsoft SQL Server 2014 Express file to update your current SQL Server Express installation.


- Step 2: Run the file and follow the setup wizard's instructions to complete the installation. Select Add features to an existing instance of SQL Server on the Installation Type page, then select the instance you want to upgrade.
__Note:__ If you download using Microsoft Edge in Windows 10, the "Choose Directory for Extracted Files" window may appear, with a default/proposed path that includes System32. If this happens, modify the route to a different location on your computer before clicking 'OK.'



- Step 3: Select the Management Tools – Complete check box on the Feature Selection page, and then complete the installation.


__Note:__ Both 32-bit and 64-bit versions of Microsoft® SQL Server® 2014 Express are available. SQLEXPR32 x86 is a reduced package for installing SQL Server 2014 Express on 32-bit OS systems exclusively. The SQLEXPR x86 product is the same as SQLEXPR, except it may be installed on both 32-bit and 64-bit (WoW) operating systems. SQLEXPR x64 is a native 64-bit version of SQL Server 2014 Express that can only be installed on 64-bit OS systems. Other than that, both packages are identical. On IA64 platforms, Microsoft® SQL Server® 2014 Express is not supported.


### <ins>Using the Data and importing into the SQL Server:</ins>
- [ ] Clone the repo and save into your desired location on your machine.
- [ ] Launch SQL Server create a database connection
- [ ] Import the csv files in the repo into the database using the __import and export wizard__
- [ ] Copy the commands in the text file to test the database.

__NOTE:__ Change the database name in the query to the database name that you create.