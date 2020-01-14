**The use of this software subjects you to our** [Terms Of Use](https://prrvchr.github.io/KiCad-BOM-CPL-Plugin/TermsOfUse_en)

## KiCad python plugin that generate BOM and CPL files for JCLPcb, LCSC and even any other provider... such as Farnell.

### Install:

- Download the [plugin](https://github.com/prrvchr/KiCad-BOM-CPL-Plugin/releases/download/v0.0.1/bom-cpl-plugin.py)
- Put the pugin file 'bom-cpl-plugin.php' in your KiCad working directory.
- In KiCad open Eeschema go to BOM (Generate Bill Of Materials) and add A New Plugin


### Use:

It is necessary for the operation to add 4 additional fields in Eeschema, which are:
- Manufacturer
- PartNumber
- Supplier
- SupplierRef

When launching the plugin (in Eeschema BOM) it will create as many csv files as there are different ‘Supplier’ encountered.

It also creates the CPL file for JLCPcb from one of the position files found in the working directory.

### Has been tested with:

* KiCad 5.1.5 - Ubuntu 18.04 - LxQt 0.11.1
