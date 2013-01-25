#Defining and attaching prevaluesources
Prevalue sources can be hooked to fields that use a list fieldtype (radiobuttonlist, checkboxlist, dropdownlist). Making it possible to retrieve a list of items from a certain source.

##Overview of the default prevalue source types
There are a couple of default prevalue source types that can be used, here is an overview:

###Get values from textfile
Upload textfile that contains the prevalues (seperated by linebreak)

###SQL Database
Connects to a OLEDB compatible Database Table and constructs a prevalue source from it, which is editable from the forms UI


###SQL Database (Read only)
Connects to a OLEDB compatible Database Table and constructs a prevalue source from it

###Umbraco data type Prevalues
Connects to an umbraco data type and uses its prevalue collection

###Umbraco data type Prevalues (Read only)
Read only version of the data type prevalues (not possible to add/edit/remove values)

###Umbraco Documents
Uses nodes from a specific source as prevalues




